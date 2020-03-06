## Short Name

Modernize apps with the Transformation Advisor tool and deploy on OpenShift

## Short Description

Transform your traditional on-premises app and deploy it as a containerized app on a OpenShift Platform

## Author
Balaji Kadambi, Shikha Maheshwari

## Code
https://github.com/IBM/migrate-app-to-openshift-using-cp4a

## Video
NA

## Summary

If you have existing on-premises WebSphere® Application Server apps and can benefit by moving them to the cloud, 
this code pattern is for you. A simple demo app shows how to run a custom data collector to analyze an app and provide
recommendations, cost estimates, and detailed reports to help with your transformation project. You see how to generate
the artifacts you need and get your application deployed and running in a Liberty container on the cloud.

## Description

This code pattern uses the Transformation Advisor app to evaluate an on-premises traditional WebSphere Application Server application for deployment on public or private cloud environments. See how to use the Transformation Advisor integration with the Microclimate development environment to deploy the app in a Liberty container running on IBM Cloud Private. The pattern also shows how to download the generated migration bundle and use its Helm chart to deploy the containerized app to a public cloud: the Kubernetes Service on IBM Cloud.

A sample web app demonstrates a migration from an on-premises application to the cloud.

When you use this code pattern, you learn how to complete the following tasks:

    Use Transformation Advisor to create a custom data collector.
    Run the custom data collector to analyze a traditional WebSphere Application Server application.
    Review the Transformation Advisor reports to see migration complexity, cost, and recommendations.
    Generate artifacts to containerize the app.
    Move the modernized app to IBM Cloud Private using Microclimate.
    Move the modernized app to the Kubernetes Service on IBM Cloud using a generated migration bundle.


## Flow

1. Developer downloads a custom Data Collector from Transformation Advisor
2. Developer runs the Data Collector on the traditional WebSphere Application Server host
3. Data Collector analysis is uploaded (automatically or manually)
4. Developer reviews recommendations in Transformation Advisor and creates a migration bundle
5. Developer downloads migration bundle
6. Developer uses Docker to build an image and upload it to OpenShift Docker Registry
7. Developer creates an app using the pushed image and runs the containerized app.


## Included components

* [IBM Cloud Pak for Application](https://www.ibm.com/cloud/cloud-pak-for-applications): The IBM Cloud Pak for Applications provides a complete and consistent experience to speed development of applications. You can easily modernize your existing applications with IBM integrated tools and develop new cloud-native applications faster for deployment on any cloud.

* [Transformation Advisor](https://www.ibm.com/in-en/marketplace/cloud-transformation-advisor): Not every workload should move to cloud. The right choice can yield large cost savings and speed time to market. The Transformation Advisor tool can help you decide.
   
* [WebSphere Liberty](https://www.ibm.com/cloud/websphere-liberty): A dynamic and easy-to-use Java EE application server, with fast startup times, no server restarts to pick up changes, and a simple XML configuration.


## Featured technologies

* [OpenShift Container Platform](https://www.openshift.com/): Red Hat OpenShift offers a consistent hybrid cloud foundation for building and scaling containerized applications.
* [Cloud](https://en.wikipedia.org/wiki/Cloud_computing): Accessing computer and information technology resources through the Internet.
* [Containers](https://www.ibm.com/cloud/learn/containers): Virtual software objects that include all the elements that an app needs to run.
* [Java](https://www.w3schools.com/java/java_intro.asp): A secure, object-oriented programming language for creating applications.

## Links