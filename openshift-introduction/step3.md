

# Create application 

``oc new-app hello``{{execute}}

# Expose application 

``oc expose service hello``{{execute}}

# Access from external world

``curl -s http://hello-myproject.[[HOST_SUBDOMAIN]]-80-[[KATACODA_HOST]].environments.katacoda.com/``{{execute}}