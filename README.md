Satorix Rails Demo
===================

A Ruby on Rails demo application for the Satorix Cloud

Next Steps
----------

### To explore and modify this app
* Download a local copy of the demo app
  * `git clone https://github.com/satorix/satorix-rails-demo.git`
* Change directory into the local repository
  * `cd satorix-rails-demo`
* Rename Github origin
  * `git remote rename origin old-origin`
* Associate this repository with appname in your Satorix Gitlab
  * `git remote add origin https://gitlab.clientid.satorix.cloud/satorix/appname.git`
* You'll now be set up to run the app locally, or deploy to your Satorix Hosting Cluster

How to use this app
-------------------

* Enable a Postgres database in the Resources tab for this project in your Satorix Dashboard
* Merge this project into the staging or production branches in your Satorix Gitlab to deploy to the corresponding environment
* During the deploy to your Satorix Hosting Cluster all the dependencies required to run this application will be installed
* This application runs as a single web process in your cluster by default
* The Books page can be used to test database access

Required App Variables
----------------------

#### The Satorix Dashboard allows input of settings that are utilized by your application. Here is a list of the required settings for this application to run:
* `SECRET_KEY_BASE`
  * Rails secret key can be generated with `rake secret`
