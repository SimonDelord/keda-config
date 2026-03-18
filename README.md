# keda-config
how to scale a group of Pods based on time


# setup is simple
Go onto the operator hub (software catalog) and select - Custom Metrics Autoscaler.
Wait for it to install in the openshift-keda namespace.

Then deploy the nginx deployment.yaml file.
Then create the scaledObject time-based-scaler-packops.

This is taken from https://medium.com/@farshadnick/how-to-scale-based-on-specified-time-in-kubernetes-keda-cron-658dd4d00604 and 
https://www.redhat.com/en/blog/custom-metrics-autoscaler-on-openshift


