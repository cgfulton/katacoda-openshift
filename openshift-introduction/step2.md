This section will focus on build 

# Create build config

``oc new-build --name=hello --dockerfile=$'FROM centos:7\nRUN yum install -y nc\nEXPOSE 8080\nENTRYPOINT ["/bin/sh", "-c", "while true ; do nc -l -p 8080 -c \'echo -e \\"HTTP/1.1 200 OK\\n\\n$(date)\\"\'; done"]'``{{execute}}

# Check build logs

``oc logs -f bc/hello``{{execute}}




