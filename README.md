# DotNetRepo With this project we are testing MSbuild plugin of Jenkins.
Once code commti done for this repository then jenkins will trigger MSBuild pipeline and which builds .net project.
Detailed PDF present inside this project

Hello everyone, we are back with one more DevOps topic. Jenkins is a very popular CI/CD tool in the DevOps world. Today we will talk about how to build a visual studio project in Jenkins. As it is open source, you may face some issues when you try to build the visual studio project in Jenkins first time. If you are also facing that issue, you are at the right place. I will explain step by step procedure to build a visual studio project in Jenkins.

Before Proceeding, please make sure you have fulfilled the below pre-requites to complete this topic:

Jenkins server is already installed on Linux/Windows VM and up and running.
Configure a windows agent under Jenkins Nodes
Install MS Build software on the Windows machine.
Once the above three prerequisites are in place, we are good to move ahead with our topic. Let’s just dig in. Below is the main list of tasks that we need to complete to build a visual studio project in Jenkins.

Install MS Build Plugin in Jenkins
Configure MS Build Plugin
Create a Free Style Project
Restrict the job to Windows Agent
Add Git Repository
Add Build Steps
Archive the Artifacts.
Build the project.
