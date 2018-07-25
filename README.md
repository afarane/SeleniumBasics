# Maven

There are three built-in build lifecycles :
1. default : The default lifecycle handles your project deployment
2. clean : the clean lifecycle handles project cleaning
3. site : while the site lifecycle handles the creation of your project's site documentation.

--------------

Lifecycle Phases :
- validate - validate the project is correct and all necessary information is available
- compile - compile the source code of the project
- test - test the compiled source code using a suitable unit testing framework. These tests should not require the code be packaged or deployed
- package - take the compiled code and package it in its distributable format, such as a JAR.
- verify - run any checks on results of integration tests to ensure quality criteria are met
- install - install the package into the local repository, for use as a dependency in other projects locally
- deploy - done in the build environment, copies the final package to the remote repository for sharing with other developers and projects.
