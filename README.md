# Individual Project #1: Continuous Delivery of Flask Application on GCP

  # The following project includes:

           -Creation of a Google App Engine application using GCP Cloud Shell environment

           -Configuration of Cloud Build to deploy changes

           -Creation of a Trigger.

           -Source code to Github

Created a Git repository called 'Project1' and created a virtual environment in cloud shell.
  
The git repository includes the following files:

          -requirement. txt: This file includes the necessary libraries for the project (Flask, Pandas, google.cloud.language, etc.)

          -main.py: This file contains several functions with respective routes. The routes will be executed on the local host port web browser. The routes include: default route, pandas route (prints json data information using Python pandas), a name/value route that executes different results based on user input, an html route, and a greeting route that displays a gif image on the webpage.

          -main_test.py: This file includes specific test cases.

          -Makefile: This is, esentially, a list of "rules". This is efficient when running or updating certain files.

          -App.yaml: Used to run the latest version of Python.

          -Cloud.yaml Used to configure cloudbuild and deploy changes.
