# DevOps on Azure Workshop

## A 2 day workshop covering how to perform DevOps related tasks in Azure. Consists of a combination of lectures and hands on labs demonstrating core concepts.

## Learning Objectives
* Perform Work Item Management in Visual Studio Team Services 
* Perform continuous Integration/Deployment Between Environments 
* Understand the different Code Repositories 
* Understand how to plan and perform Load Testing 
* Understand how to plan and perform Monitoring

## Pre-Requisites
* Azure Subscription 
* Visual Studio Team Services account
* Visual Studio 2015+
* Azure SDK
* PowerShell

# Presentations

### [Introduction to DevOps](./Presentations/01_Introduction_to_DevOps.pptx)
Understand why and how modern DevOps practices fit within the Microsoft Azure platform

### [Infrastructure as Code](./Presentations/02_Infrastructure_as_Code.pptx)
Understand how managing the provisioning of infrastructure is enhanced with Infrastructure as Code (IaC) concepts

### [Configuration Management](./Presentations/03_Configuration_Management.pptx)
Understand how to configure and manage the "inside" of environments

### [Security for Modern Application](./Presentations/04_Security_for_Modern_Applications.pptx)
Understand common security patterns for modern application development

### [Continuous Integration](./Presentations/05_Continuous_Integration.pptx)
Understand the array of options for enabling a Continuous Integration environment on Microsoft Azure

### [Automated Testing](./Presentations/06_Automated_Testing.pptx)
Understand how to implement a thorough testing plan for cloud applications

### [Release Management](./Presentations/07_Release_Management.pptx)
Understand the process of regular releases into a cloud first environment

### [Continuous Deployment](./Presentations/08_Continuous_Deployment.pptx)
Implement common use cases for continuous deployment on Microsoft Azure

### [Modern Application Monitoring](./Presentations/09_Modern_Application_Monitoring.pptx)
Integrate Microsoft Azure tools for managing telemetry within an application

### [Open Source on Azure](./Presentations/10_Open_Source_on_Microsoft_Azure.pptx)
Utilize open source technologies in conjunction with Microsoft Azure services

### [DevOps Landscape](./Presentations/11_DevOps_Landscape.pptx)
Understand a variety of contemporary concerns and techniques pertaining to DevOps

# Hands on Labs

### [Configuration Management: Infrastructure Lab](./Labs/Configuration%20Management)
Deploy Azure resources using an ARM template. Includes the the following:
* Deploy VM1 - config using DSC  + Web Deploy
* Deploy VM2- config using Chef + Web Deploy
* Deploy VM3 - config using Puppet + Web Deploy

### [Desired State Configuration using Chef Server Lab](./Labs/DSC%20Using%20Chef%20Server)
During this lab, you will continue working with the 3 Azure Virtual Machines you deployed in the Azure Resource Manager lab. The goal of this lab is configuring a trial hosted Chef Server account, and using this technology to bootstrap any of the already deployed Windows Server Virtual Machines as web server running Internet Information Server

### [Automated Testing + Continuous Integration Lab](./Labs/Continous%20Integration)
Setup an automated build in VSTS.
Setup automated test cases using VSTS

### [Continuous Deployment Lab](./Labs/Continuous%20Deployment)
Implement a continuous deployment release pipeline by using visual studio team service

### [Modern Application Monitoring Lab](./Labs/Monitoring)
Configure monitoring for IaaS/PaaS workloads with ARM

### [Open Source on Microsoft Azure Lab](./Labs/Open%20Source/)
Implement CI and CD using open source technologies such as Docker and Jenkins

# Suggested Itinerary

|Day|Time           |Session Title                                     |Activity |Mins  |
|:--|---------------|--------------------------------------------------|-----    |:-----|
| 1 |08:00am - 09:00|Introduction to DevOps                            |Lecture  |  60  |
| 1 |09:00am - 10:00|Infrastructure as Code                            |Lecture  |  60  |
| 1 |10:00am - 10:15|Break                                             |Break    |  15  |
| 1 |10:15am - 11:00|Configuration Management                          |Lecture  |  45  |
| 1 |11:00am - 12:00|Configuration Management: Infrastructure Lab      |Lab      |  60  |
| 1 |11:00am - 12:00|Desired State Configuration using Chef Server Lab |Lab      |  30  |
| 1 |12:00pm - 01:00|Lunch                                             |Lunch    |  60  |
| 1 |01:00pm - 02:00|Security for Modern Application                   |Lecture  |  60  |
| 1 |02:00pm - 03:00|Continuous Integration                            |Lecture  |  60  |
| 1 |03:00pm - 03:15|Break                                             |Break    |  15  |
| 1 |03:15pm - 04:15|Automated Testing                                 |Lecture  |  60  |
| 1 |04:15pm - 05:15|Automated Testing: + CI Lab                       |Lab      |  60  |
| 1 |05:15pm - 05:30|Open Panel                                        |Panel    |  15  |
| 2 |08:00am - 09:00|Release Management                                |Lecture  |  60  |
| 2 |09:00am - 010:0|Continuous Deployment                             |Lecture  |  60  |
| 2 |10:00am - 10:15|Break                                             |Break    |  15  |
| 2 |10:15am - 11:15|Continuous Deployment Lab                         |Lab      |  60  |
| 2 |11:15am - 12:15|Modern Application Monitoring                     |Lecture  |  60  |
| 2 |12:15pm - 01:15|Lunch                                             |Lunch    |  60  |
| 2 |01:15pm - 02:15|Modern Application Monitoring Lab                 |Lab      |  60  |
| 2 |02:15pm - 03:15|Open Source on Microsoft Azure                    |Lecture  |  60  |
| 2 |03:15pm - 03:30|Break                                             |Break    |  15  |
| 2 |03:30pm - 04:30|Open Source on Microsoft Azure Lab                |Lab      |  60  |
| 2 |04:30pm - 05:15|DevOps Landscape                                  |Lecture  |  45  |
| 2 |05:15pm - 05:30|Open Panel                                        |Panel    |  15  |