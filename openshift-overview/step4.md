## Labels

All object in OpenShift have labels, label is key value like `app=hello`

Labels are used widely in OpenShift infrastructure.

 ``oc get pod --show-labels``

Output:
```
NAME               READY     STATUS      RESTARTS   AGE       LABELS
po/hello-1-build   0/1       Completed   0          54m       openshift.io/build.name=hello-1
po/hello-1-nk58l   1/1       Running     0          53m       app=hello,deployment=hello-1,deploymentconfig=hello
```


