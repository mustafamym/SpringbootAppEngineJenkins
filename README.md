# how run project

# login with google cloud 

gcloud auth login

# Create the GCP Project

# set project 

$gcloud projects list will list the projects running on my account. I want to change the current project to any other project from the list using a cli com

gcloud config set project metal-shift-255901


# run local


#Deploy to App Engine

## run

mvn appengine:run

## deploy

mvn appengine:deploy