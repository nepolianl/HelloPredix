# Getting Started with Predix

Predix, known as Predix Platform is an industrial IoT software platform from GE Digital. It provides secure edge-to-cloud OT/IT data connectivity, processing, analytics, and services to support industrial applications from GE Digital as well as those developed by customers or partners.

# How Predix Works

Predix helps you develop, deploy, and operate industrial apps at the edge and in the cloud. Securely connect machines, data, and analytics to improve operational efficiency.

Everything you need to build IIoT applications

## Manifest Configuration & Deploy
```
applications:
  - name: hello-predix # Step 1: Change your application name
    buildpack: predix_openresty_buildpack
    #path: dist
    memory: 64M
    stack: cflinuxfs2
```

**Deploy**:

From the project's home directory, push the application: `cf push` <p>
View the environment variables for your application: `cf env <application_name>`

## Further help

To get more help on Predix Platform [Predix.io](https://www.predix.io/).
