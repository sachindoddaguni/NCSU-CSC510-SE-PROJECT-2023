# Project Description 

Team 33 has chosen the [project](https://github.com/kingan1/application-tracking-system) for SE project1. The **J-tracker** application is a job  application tracking assistant. It provides users with various functionalities which makes tracking job applications much easier. As we know for all students tracking their job application is of most importance, J-tracker provides features such as job search with filters such as salary, a wishlist to save your favorite jobs and move your application between various status. 

**Youtube video showing the application running: [link](https://www.youtube.com/watch?v=JZGqmLN6dsc)**

The project has a [setup script](https://github.com/kingan1/application-tracking-system/blob/main/setup.sh) which installs python dependencies for backend component and node dependencies for frontend component. The project also has a [startup bash script](https://github.com/kingan1/application-tracking-system/blob/main/startup.sh) which creates various components required for the system. The startup script is supposed to be run after running the setup script. 


When our team chose the project, we thoroughly reviewed the project in order to establish an effective development strategy. While trying to run the application on our local systems, we came across a number of hurdles. 

* The first issue we faced was that the python flask component failed to run notifying import erros that it had missing class "escape" from jinja2. To resolve this we had to update our flask version to 2.3.x as "escape" module was dropped from newer versions of Jinja.  

* The second issue that we faced was while installing dependencies for the fronend component. My local system had node 20 installed. Some packages failed to install with the version of node and npm that was present in the local system. After downgrading node to node 16 and npm to 6.14.x, things worked well. The README mentions that any version above node 16 works well, but as we saw the application failed to work for node 20.

* The third difficulty that we faced was while installing MongoDB. Starting MongoDB within MongoDB bin failed to work as it required us to provide a path for db content. We were able to overcome this issue by using the brew command to start the service. 

* Fourth difficulty we saw was that while trying to understand the code we found out that most of the backend code was in a single [python module](https://github.com/kingan1/application-tracking-system/blob/main/backend/app.py) . This non-modular approach hindered the ability to understand the code easily.

We can overcome all of the above faced issue by containerizing the application. Containerization bundles applications code, files and libraries into a single container that can be run in isolation. Containerization helps us in having individual containers for each component of the system which further removes the need to install dependencies globally in our system. Installing dependencies globally comes with its own sets of problems. 

Using virtual environment could be a solution, but when we containerize it, it removes the need for virtual environments as we have the whole container for the python component. Having a specific container for MongoDB will remove the need to use install mongo db separately in our system. Containerization will prevent us from installing the software in our system just for running a single application.  

A very thorough documentation can help us to ease the process of running the application and tackle problems that we faced like version dependencies. A list of all dependencies with their version number being used to run the project can benefit a developed massively to run the code and also contribute.


For Project 2, we propose to improve the application in as many ways as possible such as:

* Containerizing the application so that the application can be run easily in isolation without having to worry about any dependencies.

* We also commit to have a very thorough documentation which has every specific detail including the versions being used for the dependencies.

* We could also see that most of the application backend code resides in a single python module. Non-modular code can cause a number of problems like, if a new developer wants to contribute to the codebase they might have difficulty understanding the code. We commit to make the application more modular which can make the code more reusable, scalable and decrease testing complexity.

* The present code coverage for the application is 74%. We plan on increasing the code coverage by writing comprehensive test cases for all the API endpoints to test all the code paths.
