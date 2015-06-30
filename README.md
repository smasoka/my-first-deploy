# Your first Jenkins job 

This is a training and demonstration repo for writing -deploy jobs for our build and deploy system at http://ci.sagrid.ac.za:8080

In general we want to make access to the SAGrid build system as open as possible, but manage the rights of anyone who wants to contribute. Since we want to automate as much as possible the delivery of new applications in this distributed environment, we need to have a stepping-stone project which can be personally managed by new users. This is the purpose of this repo. 

# Purpose  of this repo

This repository is to demonstrate, with high verbosity, how we expect new applications to be built, tested and deployed. This repository is thus an expression of good practice. As it is tested - like all other `-deploy` repos - with every commit, it is also an expression of the functional state of this good practice. 

# How to use this repo

Every jenkins job is connected to specific repo. Let's say you have a new application which you want to port - `myapp`. In order to get started, we expect you to fork this repo to your own github account (@user/myapp-deploy) and send us pull request to a repo in this organisation with your app name (@SouthAfricaDigitalScience/myapp-deploy). This will allow us to collaboratively provide suggestions to your new project. Do not edit this repo directly.

