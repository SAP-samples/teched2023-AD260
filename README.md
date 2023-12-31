[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/teched2023-AD260)](https://api.reuse.software/info/github.com/SAP-samples/teched2023-AD260)

# AD260 - Building SAP Fiori apps with ABAP Cloud on SAP BTP ABAP environment

## Description

This repository contains the material for the SAP TechEd 2023 Hands-On Workshop called [AD260 - Building SAP Fiori apps with ABAP Cloud on SAP BTP ABAP environment](https://go2.events.sap.com/TechEd2023/agb/go/agendabuilder.sessions/?l=326&sid=116864&schid=520415&locale=en_US).  

> 📺 Live session: 📅 Thursday, Nov 2 | 🕐 11:15 AM – 1:00 PM IST
> 
> 📺 Live session: 📅 Friday, Nov 3 | 🕐 10:15 AM – 12:00 PM IST

The ABAP RESTful application programming model (RAP) is at the heart of the ABAP Cloud development model for building transactional, cloud-ready apps and services on SAP BTP, ABAP environment and SAP S/4HANA, in the cloud and on premises. Learn how to use RAP features, such as late numbering, side effects, and business events, to build your own SAP Fiori apps. This session focuses on the development capabilities available in the ABAP development tools. 

## Overview

In this Hands-On Workshop , participants will learn how to use the core features of the ABAP RESTful application programming model (RAP) to build modern, cloud-ready, transactional SAP Fiori applications and services.

This section provides a brief introduction to RAP and to the current business scenario.

<details>
  <summary>Click to expand!</summary>

### Business Scenario

> In this hands-on session we will guide you through the development of the OData service of a SAP Fiori elements based _Travel Processing App_ with RAP, using the _managed_ business object (BO) runtime implementation with semantic key and late numbering. We will give you more details on the scenario in the different exercises.
>   
> The OData service you are going to implement is based on the _ABAP Flight Reference Scenario_. To set the business context, the scenario is the following: The department responsible for managing worldwide Travels for multiple Agencies is requesting you to build a new Fiori app with draft capabilities for processing (i.e. creating, updating and deleting) Travels. 
  
<details>
  <summary>Click to expand!</summary>
   
The resulting _Travel_ app is a SAP Fiori elements-based List Report app with search, filter, and draft capabilities for processing travel bookings. A navigation to an Object Page for displaying the details of each _travel_ entry in the list report is offered. The application will look like this: 

that will look like this:

**List Report**:
<img src="exercises/images/ad260_travelapp01.png" alt="RAP110 Travel App - List Report" width="100%">
  
**Object Page**: 
<img src="exercises/images/ad260_travelapp02.png" alt="RAP110 Travel App - Object Page" width="100%">

Below is the simplified _Flight_ data model underlying the app.

<img src="exercises/images/ad260_datamodel.png" alt="RAP110 Data Model" width="80%">

</details>

### About the ABAP RESTful Application Programming Model (RAP)
   
> **ABAP Cloud** is the development model for building cloud-ready business apps, services and extensions on SAP BTP and all SAP S/4HANA editions, i.e. public or private cloud, and even on-premise.
>
> The **ABAP RESTful Application Programming Model (RAP)** is the centerpiece of _ABAP Cloud development model_ for building transactional, cloud-ready SAP Fiori apps and Web APIs. RAP offers a set of concepts, tools, languages, and powerful frameworks provided on the ABAP platform. It supports the efficient development of innovative and cloud-ready enterprise applications, as well as the extension of SAP standard applications in an upgrade-stable way in the cloud and on-premise.

<details>
<summary>Click to expand!</summary>

RAP is an enabler for improving the user experience and innovating business processes in ABAP-based SAP solutions by leveraging SAP Fiori, SAP HANA, and the cloud. 
It is a long-term strategic solution for ABAP development on SAP’s flagship product SAP S/4HANA, in the cloud and on-premise (as of release 1909), as well as on the SAP BTP ABAP Environment.

The illustration below shows the high-level end-to-end development stack when working with RAP.  

<img src="exercises/images/rap_bigpicture.png" alt="RAP Big Picture" width="80%">

</details>

</details>

## Requirements

The requirements to follow the exercises in this repository are (Only for on-site session):
1. On your Windows Desktop you will find an "eclipse" shortcut. Double-click to launch the Eclipse installation.
2. Open ABAP perspective if not already opened. Check [here](https://github.com/SAP-samples/teched2023-AD260/blob/main/exercises/images/abap%20perspective.png) for steps.
3. ⏬ Download the 🔑 [service key](https://sap-my.sharepoint.com/:t:/p/shubham_waghmare/EbYWKjgIaFxCs-exT3fh1tMBOm6FvIm39xrC8b0KzCQDOQ?e=NMu7hc) locally that will be used in [Exercise 0: Getting Started](https://github.com/SAP-samples/teched2023-AD260/tree/main/exercises/ex00#create-an-abap-cloud-project-in-adt) to logon to the dedicated SAP BTP, ABAP environment system for the hands-on exercises.
4. Logon to the system by following the [Exercise 0: Getting Started](https://github.com/SAP-samples/teched2023-AD260/tree/main/exercises/ex00#create-an-abap-cloud-project-in-adt) 
5. Your custom user is AD260-###@education.cloud.sap where ### should be replaced by your seat number. Password will be shared during the session.

## Exercises

🛠 Access the exercises [here](https://github.com/SAP-samples/abap-platform-rap-workshops/blob/main/rap1xx/rap110/README.md#-exercises).

## Presentation

Access the Session presentation: [AD260@SAP_TechEd_2023.pdf](/exercises/images/AD260@SAP_TechEd_2023.pdf)

## Related ressources
 - 📍 [Overview of the ABAP Cloud Sessions at SAP TechEd 2023](https://blogs.sap.com/2023/10/02/abap-cloud-at-sap-teched-in-2023/)
 - 📃 [State-of-the-Art ABAP Development with the ABAP RESTful Application Programming Model (RAP) | SAP Community](https://community.sap.com/topics/abap/rap)
 - 📄 [ABAP Cloud – SAP S/4HANA extensibility – May 2023 update | SAP Blogs](https://blogs.sap.com/2023/05/26/abap-cloud-sap-s-4hana-extensibility-may-2023-update/)
 - 🛠 [Develop and Run a Fiori Application with SAP Business Application Studio | SAP Tutorials](https://developers.sap.com/tutorials/abap-environment-deploy-cf-production.html)

## Contributing
Please read the [CONTRIBUTING.md](./CONTRIBUTING.md) to understand the contribution guidelines.

## Code of Conduct
Please read the [SAP Open Source Code of Conduct](https://github.com/SAP-samples/.github/blob/main/CODE_OF_CONDUCT.md).

## How to obtain support

Support for the content in this repository is available during the actual time of the on-site session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## License
Copyright (c) 2023 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
