# Workshop Material
-  Virtual Box
    - [Image Location](https://drive.google.com/open?id=0By6_zxxSRb11R0hBSkVJeU9kMEU)
    - Password : r3dh4t1!
-   Installer (pre-installed in VM Image)
    -   [JBoss Developer Studio](https://drive.google.com/open?id=0BwYg9EJiu13fLXR0eHNVSGlVbFE
)
    -   [CDK](https://drive.google.com/open?id=0BwYg9EJiu13fUGh0U2FLMGE0TGs
)
-   Lab Instruction
    -   [Lab 01](https://drive.google.com/open?id=0BwYg9EJiu13fbmNjOGtMTERQcWc)
    -   [Lab 02](https://drive.google.com/open?id=0BwYg9EJiu13fNGRMMV82eU9jbXc)
    -   [Lab 03](https://drive.google.com/open?id=0BwYg9EJiu13fTkRLS0Fvb2UtV2s)
    -   [Lab 04](https://drive.google.com/open?id=0BwYg9EJiu13fbVczUFZIUmRsYnM)

# Preparation
1. Go to terminal and run the below command
```sh
$ oc cluster up
``` 

2. Once Openshift is up and running, log in as system admin with the below command, and initiate download for FIS image and mysql ephemeral 
```sh
$ oc login -u system:admin 
$ oc create -f https://raw.githubusercontent.com/jboss-fuse/application-templates/master/fis-image-streams.json -n openshift
$ oc create -f https://raw.githubusercontent.com/openshift/origin/master/examples/db-templates/mysql-ephemeral-template.json -n openshitf
```
