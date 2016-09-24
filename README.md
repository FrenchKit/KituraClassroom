# Kitura Classroom

## Setup
There's a number of samples and tutorials that you can either build yourself, or download from GitHub. Below are a couple of those projects in case you want to clone then ahead of time:
```
git clone https://github.com/IBM-Swift/Kitura-Sample
git clone http://github.com/rfdickerson/SuperTodoList
```
### Optional  
If you want to try deploying to the IBM Bluemix Cloud, this is made easier using the IBM Cloud Tools for Swift:
http://cloudtools.bluemix.net/

## Instructions
**Tutorial 1: My First Project**  
This is a simple "Hello World" Application
* Step 1: Build and deploy "myFirstProject"  
http://www.kitura.io/en/starter/gettingstarted.html
* Step 2: Create an XCode project for "myFirstProject"  
`swift package generate-xcodeproj`
* Step 3: Open the project in XCode and make some changes
* Step 4: Change the build scheme to your executable  
Xcode defaults to the module of the same name, which won't run.
* Step 5: Run your modified "myFirstProject"

**Tutorial 2: Kitura Sample**  
This is a more complicated example that includes logging and templating.
* Step 1: Clone the Kitura Sample project:  
`git clone https://github.com/IBM-Swift/Kitura-Sample`
* Step 2: Follow the instructions in the README.md

**Tutorial 3: Super ToDo List**  
This is a tutorial that implements a ["ToDo List Backend"](http://www.todobackend.com)
* Step 1: Clone the Super ToDo List repository:  
`git clone http://github.com/rfdickerson/SuperTodoList`
* Step 2: Build your own version of the ToDo list using the project and [the tutorial](todolist-tutorial.pdf)
