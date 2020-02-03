# Individual Project #1: Continuous Delivery of Flask Application on GCP

##The following project includes:

-Creation of a Google App Engine application using GCP Cloud Shell environment

-Configuration of Cloud Build to deploy changes

-Trigger establishment.

-Source code to Github

Created a Git repository called 'Project1' and created a virtual environment in cloud shell.
  
The git repository includes the following files:

-requirement. txt: This file includes the necessary libraries for the project (Flask, Pandas, google.cloud.language, etc.)

-main.py: This is the file that contains several functions with routes that execute specific commands. These routes will be executed in the local host port web browser. These routes include a default route, a route that prints json data information using python pandas, a name route that executes different results based on user input, an html route that practices html commands, and a greeting route that practices advanced html commands.

-main_test.py: This file includes specific test cases.

-Makefile: This is, esentially, a list of "rules". This is efficient when running or updating certain files.

-App.yaml: Used to run the latest version of Python.

-Cloud.yaml Used to configure cloudbuild and deploy changes.