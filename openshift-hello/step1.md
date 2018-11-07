## Logging in to the Cluster

To login to the OpenShift cluster from the _Terminal_ run:

``oc login -u developer -p developer``{{execute}}

This will log you in using the credentials:

* **Username:** ``developer``
* **Password:** ``developer``

Use the same credentials to log into the web console. 

## Creating your own Project

To create a new project called ``helloProject`` run the command:

``oc new-project helloProject``{{execute}}

You could instead create the project from the web console. If you do this,
to change to the project from the command line run the command:

``oc project helloProject``{{execute}}

