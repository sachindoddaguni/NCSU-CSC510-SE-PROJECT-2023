## Grading Rubric

### Project t - [J-Tracker](https://github.com/kingan1/application-tracking-system)

|Notes|Score|evidence|
|-----|-----|---------|
|Video|3|7min video |
|Workload is spread over the whole team (one team member is often Xtimes more productive than the others... 
but nevertheless, here is a track record that everyone is contributing a lot)|3|evidence in GH|
|Number of commits|3|in GH 428 commits|
|Number of commits: by different people|3|In GH contributors - All teammates have contributed|
|Issues reports: there are **somewhat**|2| 10 issues |
|Issues are being closed|3|24 issues closed|
|DOI badge: exists|3|in GH|
|Docs: doco generated, format not ugly |2|in GH. Formatting can be better|
|Docs: what: point descriptions of each class/function (in isolation) |3 | 
|Docs: how: for common use cases X,Y,Z mini-tutorials showing worked examples on how to do X,Y,Z|3| Has a video and description in README|
|Docs: why: docs tell a story, motivate the whole thing, deliver a punchline that makes you want to rush out and use the thing|3| Introductory video shows the motivation
|Docs: short video, animated, hosted on your repo. That convinces people why they want to work on your code.|3| Video presented in README
|Use of version control tools|3| GitHub is used as VCS during the entire cycle|
|Use of style checkers |3|Pylint module used to keep a check on this|
|Use of code formatters. |3|Pylint module used to keep a check on this|
|Use of syntax checkers. |3|Pylint module used to keep a check on this|
|Use of code coverage |2|coverage 74%. needs to be better|
|Other automated analysis tools|0|Exist but no status|
|Test cases exist|3| in GH|
|Test cases are routinely executed|0|no active CICD|
|The files CONTRIBUTING.md lists coding standards and lots of tips on how to extend the system without screwing things up|3|in GH|
|Issues are discussed before they are closed|even if you discuss in slack, need a sumamry statement here|
|Chat channel: exists|0|Unsure if they have it|
|Test cases: a large proportion of the issues related to handling failing cases.|0| Can't find it on the GH|
|Evidence that the whole team is using the same tools: everyone can get to all tools and files|3| https://github.com/kingan1/application-tracking-system/graphs/contributors|
|Evidence that the whole team is using the same tools (e.g. config files in the repo, updated by lots of different people)|0|No such eveidence|
|Evidence that the whole team is using the same tools (e.g. tutor can ask anyone to share screen, they demonstrate the system running on their computer)|0| No report|
|Evidence that the members of the team are working across multiple places in the code base|3| In github people have committed to different files across folders|
|Short release cycles |0| Dont see any active CICD pipeline


|Notes|Score|evidence|
|-----|-----|---------|
| Question 1.1: Does your website and documentation provide a clear, high-level overview of your software?|  3|  Check README.md on homepage of repo. [Here](https://github.com/kingan1/application-tracking-system/blob/main/readme.md).
| Question 1.2: Does your website and documentation clearly describe the type of user who should use your software? |  3|  Check README.md on homepage of repo. [Here](https://github.com/kingan1/application-tracking-system/blob/main/readme.md).
| Question 1.3: Do you publish case studies to show how your software has been used by yourself and others? |  0| Dont see a case study|
| Question 2.1: Is the name of your project/software unique? |  3| Yes. Did not see the name being used anywhere|
| Question 2.2: Is your project/software name free from trademark violations? |  3|  Could not find anything with the exact name, with the same purpose|
| Question 3.1: Is your software available as a package that can be deployed without building it? |  3|  Yes, they have a startup.sh script. [Here](https://github.com/kingan1/application-tracking-system/blob/main/startup.sh)
| Question 3.2: Is your software available for free? |  3|  Available on public repository for anyone to view and use|
| Question 3.3: Is your source code publicly available to download, either as a downloadable bundle or via access to a source code repository? |  3|  Available on public repository for anyone to view and use|
| Question 3.4: Is your software hosted in an established, third-party repository like GitHub (https://github.com), BitBucket (https://bitbucket.org),LaunchPad (https://launchpad.net) orSourceForge (https://sourceforge.net)?  |  3|  Yes Their [repo link](https://github.com/kingan1/application-tracking-system)
| Question 4.1: Is your documentation clearly available on your website or within your software? |  3|  Yes. [Here](https://github.com/kingan1/application-tracking-system/tree/main/docs)
| Question 4.2: Does your documentation include a "quick start" guide, that provides a short overview of how to use your software with some basic examples of use? |  3|  Yes. InTheir README.md. [Here](https://github.com/kingan1/application-tracking-system/blob/main/readme.md)
| Question 4.3: If you provide more extensive documentation, does this provide clear, step-by-step instructions on how to deploy and use your software? | 3 | Yes. InTheir README.md file [here](https://github.com/SmayanaReddy/auto_anki/blob/main/README.md) |
| Question 4.4: Do you provide a comprehensive guide to all your software's commands, functions and options? | 3 | Yes, in they README.md [Here](https://github.com/kingan1/application-tracking-system/blob/main/readme.md) |
| Question 4.5: Do you provide troubleshooting information that describes the symptoms and step-by-step solutions for problems and error messages? | 0 | No info on this |
| Question 4.6: If your software can be used as a library, package or service by other software, do you provide comprehensive API documentation? | 2 |  |
| Question 4.7: Do you store your documentation under revision control with your source code? | 3 | Yes |
| Question 4.8: Do you publish your release history e.g. release data, version numbers, key features of each release etc. on your web site or in your documentation? | 0 | No |
| Q5 - How you support your software | not applicable  |  |
| Question 5.1: Does your software describe how a user can get help with using your software? | 0 | Not mentioned in the documentation|
| Question 5.2: Does your website and documentation describe what support, if any, you provide to users and developers? | 0 | no |
| Question 5.3: Does your project have an e-mail address or forum that is solely for supporting users? | 0 | No |
| Question 5.4: Are e-mails to your support e-mail address received by more than one person? | 0 | Not applicable |
| Question 5.5: Does your project have a ticketing system to manage bug reports and feature requests? | 0 | No it is not there |
| Question 5.6: Is your project's ticketing system publicly visible to your users, so they can view bug reports and feature requests? | 0 | Not present |
| Question 6.1: Is your software's architecture and design modular? | 1 | Single file contains all code [here] |
| Question 6.2: Does your software use an accepted coding standard or convention? | 3 |Their code adheres to python PEP standards, using pylint |
| Q7 - Open standards and your software |  |  |
| Question 7.1: Does your software allow data to be imported and exported using open data formats? e.g. GIF, SVG, HTML, XML, tar, zip, CSV, JSON, NetCDF, or domain specific ones | 0 |Data export functionality not available|
| Question 7.2: Does your software allow communications using open communications protocols? e.g. HTTP, FTP, XMPP, SOAP over HTTP, or domain-specific ones | 3 |Their code communicates with google over HTTPS |
| Q8 - Your software's portability |  |  |
| Question 8.1: Is your software cross-platform compatible? *e.g. does it run under two or more of Windows, Unix/Linux and Mac OS X, or can be used from within two or more of Internet Explorer, Chrome, Firefox and Safari? | 3 |Yes since python env can be set for multiple envs |
| Q9 - Your software and accessibility |  |  |
| Question 9.1: Does your software adhere to appropriate accessibility conventions or standards? | 0 | The software does not adhede to conventions/standards |
| Question 9.2: Does your documentation adhere to appropriate accessibility conventions or standards? | 0 | Didn't follow it |
| Q10 - How you manage your source code |  |  |
| Question 10.1: Is your source code stored in a repository under revision control? | 3 |Their software is stored in the github repository. |
| Question 10.2: Is each source code release a snapshot of the repository? | 0 | https://github.com/kingan1/application-tracking-system/releases/tag/v1.2 |
| Question 10.3: Are releases tagged in the repository? | 3 | Tagged as V1.2 |
| Question 10.4: Is there a branch of the repository that is always stable? (i.e. tests always pass, code always builds successfully) | 2 | The main branch is used for stability. But there doesnt seem to be an active CICD pipeline |
| Question 10.5: Do you back-up your repository? |3  |Backed up in zenodo. https://doi.org/10.5281/zenodo.5750920  |
| Q11 - Building and installing your software|  |  |
| Question 11.1: Do you provide publicly-available instructions for building your software from the source code? |3  |The required steps are documented in README along with screenshots and a GIF |
| Question 11.2: Can you build, or package, your software using an automated tool? e.g. Make (https://www.gnu.org/software/make/), ANT (http://ant.apache.org/), Maven (https://maven.apache.org/), CMake (https://cmake.org/), Python setuptools (https://pypi.python.org/pypi/setuptools), or R package tools (https://cran.r-project.org/doc/manuals/r-devel/R-exts.html) | 3 | The project is providing a bash script that brings up the project env |
| Question 11.3: Do you provide publicly-available instructions for deploying your software? | 3 |Documentation provides the required steps  |
| Question 11.4: Does your documentation list all third-party dependencies? | 0 |No|
| Question 11.5: Does your documentation list the version number for all third-party dependencies? | 0 |No  |
| Question 11.6: Does your software list the web address, and licences for all third-party dependencies and say whether the dependencies are mandatory or optional? | 0 |No |
| Question 11.7: Can you download dependencies using a dependency management tool or package manager? *e.g. Ivy (http://ant.apache.org/ivy/), Maven (https://maven.apache.org/), Python pip (https://pypi.python.org/pypi/pip) or setuptools (https://pypi.python.org/pypi/setuptools), PHP Composer (https://getcomposer.org/), Ruby gems (https://rubygems.org), or R PackRat (https://rstudio.github.io/packrat/) |3  |Yes using pip  |
| Question 11.8: Do you have tests that can be run after your software has been built or deployed to show whether the build or deployment has been successful? | 0 | No post deployment or post build steps available |
| Question 12.1: Do you have an automated test suite for your software? |3  | Unit tets available   |
| Question 12.2: Do you have a framework to periodically (e.g. nightly) run your tests on the latest version of the source code? | 0 |No status|
| Question 12.3: Do you use continuous integration, automatically running tests whenever changes are made to your source code? | 2 |The project has it but there is no status |
| Question 12.4: Are your test results publicly visible? | 3 |Publicly available at https://app.codecov.io/gh/kingan1/application-tracking-system |
| Question 12.5: Are all manually-run tests documented? | 1 | No such documentation is available|
| Q13 - How you engage with your community |  |  |
| Question 13.1: Does your project have resources (e.g. blog, Twitter, RSS feed, Facebook page, wiki, mailing list) that are regularly updated with information about your software? * e.g. release announcements, publications, workshops, conference presentations  | 0 | Not present |
| Question 13.2: Does your website state how many projects and users are associated with your project? | 0 | Not present |
| Question 13.3: Do you provide success stories on your website? | 0 | Not present |
| Question 13.4: Do you list your important partners and collaborators on your website? | 3 | Available in README page
| Question 13.5: Do you list your project's publications on your website or link to a resource where these are available? | 0 | Not present |
| Question 13.6: Do you list third-party publications that refer to your software on your website or link to a resource where these are available? | 0 | Not present |
| Question 13.7: Can users subscribe to notifications to changes to your source code repository? | 0 | No |
| Question 13.8: If your software is developed as an open source project (and, not just a project developing open source software), do you have a governance model? | 3 | The licensing talks about the [governance model](https://github.com/kingan1/application-tracking-system/blob/main/LICENSE) |
| Q14 - How you manage contributions |  |  |
| Question 14.1: Do you accept contributions (e.g. bug fixes, enhancements, documentation updates, tutorials) from people who are not part of your project? | 3 | Contributors can contribute |
| Question 14.2: Do you have a contributions policy? | 3 | The policy is provided in the [CONTRIBUTING.md](https://github.com/kingan1/application-tracking-system/blob/main/Contributing.md) file. |
| Question 14.3: Is your contributions' policy publicly available? | 3 | Yes in github . [How to contribute](https://github.com/kingan1/application-tracking-system/blob/main/Contributing.md) |
| Question 14.4: Do contributors keep the copyright/IP of their contributions? | 0 | No |
| Q15 - Your software's copyright and licensing  |  |  |
| Question 15.1: Does your website and documentation clearly state the copyright owners of your software and documentation? | 3 | https://github.com/kingan1/application-tracking-system/blob/main/LICENSE |
| Question 15.2: Does each of your source code files include a copyright statement? | 0 | No |
| Question 15.3: Does your website and documentation clearly state the licence of your software? | 3 |  License details here : https://github.com/kingan1/application-tracking-system/blob/main/LICENSE |
| Question 15.4: Is your software released under an open source licence? | 3 |  It is licensed under the MIT License. https://github.com/kingan1/application-tracking-system/blob/main/LICENSE |
| Question 15.5: Is your software released under an OSI-approved open-source licence? | 3 | Yes, MIT is OSI approved. |
| Question 15.6: Does each of your source code files include a licence header? | 0 | No |
| Question 15.7: Do you have a recommended citation for your software? | 0 | No |
| Q16 - Your plans for the future |  |  |
| Question 16.1: Does your website or documentation include a project roadmap (a list of project and development milestones for the next 3, 6 and 12 months)? | 0 | No |
| Question 16.2: Does your website or documentation describe how your project is funded, and the period over which funding is guaranteed? | 0 | Not Applicable |
| Question 16.3: Do you make timely announcements of the deprecation of components, APIs, etc.? | 0 | No |