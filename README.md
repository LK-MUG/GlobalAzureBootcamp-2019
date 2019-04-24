# Global Azure Bootcamp 2019 - Letterkenny, Ireland

## Host: Letterkenny DotNet Azure User Group (www.lk-mug.org)
![gablogo][gablogo]

All around the world user groups and communities want to learn about Azure and Cloud Computing!

On **April 27, 2019**, all communities will come together once again in the sixth great [Global Azure Bootcamp](https://global.azurebootcamp.net/) event! 

In this repository you will find included all materials used during the demos so you can try them at home.


## Scenario 2019
Life has been going very well at *Contoso* it's been a while since they start their journey on Azure. Things have been so well that today *Contoso* has many developers across the many different locations and using different platforms.  They want to build an new application that could be secure and accessible from everywhere to manage their images. They would also like to have the application to do be easy to maintain and follow the best practices.

In an effort to improve their efficiency and the quality of their application they decided to agree on the following:

* Use cross-platform tools as much as possible. 
* Continuous Integration and Continuous Deployment solution (CI/CD)
* A way to reproduce the environment quickly in any new environment
* They would like to be the application "portable"
* Artificial Intellegent is an excellent way to bonify their application and distinguish themselves from the competition.
* Get rid of their old process

The team has been assigned a couple of days to find tools & put new processes in place to check all the action items of the list above. Excited, the team will actively start documenting themselves and working on this tomorrow.

## Overview of the day

### [Lab 0 - What you need to install (must do >>before<< the bootcamp!)](./Lab0/README.md) 


Time        | Duration | Tittle                                      | Description  
:----:      | :------: | :-------                                    | :----------- 
09h00-9h30  | 30 mins  | [Arrival/ Coffee](./Locations/README.md)    | Grab a seat, get your coffee, install your laptop...
09h30-10h15 | 45 mins  | Session - Discovering Azure                 | Intro, agenda
10h15-11h00 | 60 mins  | [Lab 1 - CI/CD ](./Lab1/README.md)          | Create an .Net Core App, put it in GitHub/ or Azure DevOps Repo. Create an Azure DevOps CI/CD, and deploy a webapp.
11h00-11h15 | 15 mins  | Coffee Break                                | Coffee break and Networking 
11h15-12h00 | 45 mins  | [Lab 2 - ARM template](./Lab2/README.md)    | Create an ARM template , also add a storage to the mix, modify the CICD to deploy.
12h00-12h45 | 45 mins  | [Lab 3 - Container 1](./Lab3/README.md)     | Package the Application in a Docker container. Test it locally and deploy it manually to Azure Container Services.
12h45-1h30 | 45 mins  | Lunch Break                                 |  Lunch and Networking 
1h30-2h15 | 45 mins   | Session - ARM Best Practices                |  Damian Flynn [MVP, Azure]
2h15-15h00 | 45 mins  | [Lab 5 - AI](./Lab5/README.md)              | Add an Azure Cognitive Services Vision to the application to validate an image
15h00-15h45 | 45 mins  | [Lab 6 - Serverless](./Lab6/README.md)      | Create an Azure Functions (blob trigger) to process all images in a blob storage and use the Vision API for filtering
15h45-16h00 | 15 mins  | Coffee Break                                | Coffee break and Networking 
16h00-16h45 | 45 mins  | [Lab 7 - Security](./Lab7/README.md)        | Moving all the keys and sensible information to a KeyVault
16h45-17h30 | 30 mins  | Ending                                      | Questions/ Networking/ Giveaway

#### Cancelled - Due to Time Sensitivity, but you can individually go through  from the link below
12h45-12h30 | 45 mins  | [Lab 4 - Containers 2](./Lab4/README.md)    | Create a new CI/CD pipeline to automate the container creation and deployment 
## Technology Stack required for the Global Azure Bootcamp 2019

All Platforms (Windows, MacOS, Linux)


* [Visual Studio Code](https://code.visualstudio.com/?WT.mc_id=globalazure-github-frbouche&wt.mc_id=vscom_downloads)
* [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?WT.mc_id=globalazure-github-frbouche&view=azure-cli-latest)
* [Git](https://git-scm.com/downloads)
* [Docker](https://www.docker.com/get-started)

## What you will need before the bootcamp?

Before the bootcamp, we encourage you to make sure you have all the requirement software so you can concentrate on learning and not running installations.  Make sure you get all the source code and install all the required software.  See **[Lab 0)](./Lab0/README.md)**.

### Azure Subscription
If you don't own an Azure subscription already, you can create your free account today. It comes with 200$ credit, so you can experience almost everything without spending a dime. 

Make sure to have your account up and ready before the bootcamp.

[Create your free Azure account today](https://azure.microsoft.com/en-us/free/)

[gablogo]: ./medias/GlobalAzureBootcamp2019.png "Global Azure Bootcamp 2019"
