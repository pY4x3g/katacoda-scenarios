We download the image with the `pull` command as follows

`docker pull py4x3g/jenkins-auto-setup:latest`{{execute}}

You can now start the image and expose port 8080 from the container to the localhost (here the test environment) with the following command

`docker run -p 8080:8080 py4x3g/jenkins-auto-setup:latest`{{execute}}

The jenkins should now be reachable.
You can load the Jenkins' dashboard via the following URL https://[[HOST_SUBDOMAIN]]-8080-[[KATACODA_HOST]].environments.katacoda.com/ or by clicking the dashboard tab on the right.
Sometimes the jenkins needs some time to start up, but you can follow the progress in the terminal and wait for the log 'Jenkins is fully up and running'.

In the next step we will configure our first jenkins job.