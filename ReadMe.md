# Project-Gradle Basics

This project contains a couple of gradle tasks that can be run to perform specific operations.
The tasks are seen in the build.gradle file.

## Running each task
All the tasks in the build.gradle file can be run using the following command in the project root directory
* gradle task_name  e.g  gradle sayHello

###Gradle Dependency Commands

* gradle dependencyInsight --dependency commons-logging
* gradle dependencies --configuration runtimeOnly
* gradle dependencies --configuration runtime