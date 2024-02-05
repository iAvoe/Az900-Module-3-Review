# Az900-Module-3-Review

## Core Solutions

### Internet of Things (IoT)
- Ability for devices to garner, then relay information for data analysis

### Azure IoT solutions
- *Azure IoT Central* - A fully managed global IoT SaaS solution
- *Azure IoT Hub*     - A managed, cloud hosted message hub service
- *Azure Sphere*      - A secured, high-level application platform

### Azure Big-data analytics solutions
- *Azure Synapse Analytics* - A cloud-based Enterprise Data Warehouse
- *Azure HDInsight*         - A fully-managed, open-source analytics service 
- *Azure Databricks*        - Apache Spark based analytics service

### Azure AI & Machine Learning solutions
- *Azure Machine Learning* - Platform to develop, train, deploy models
- *Cognitive Services*     - Enable apps to see, hear, speak, understand
- *Azure Bot Service*      - develop intelligent, customer servicing bots

### Azure Serverless Computing solutions
- *Azure Functions*  - Event based code on cloud (not on device)
- *Azure Logic Apps* - Automate & orchestrate tasks, business processes

-----

### Azure Development solutions
- *Azure DevOps*
  - development collaboration tools including:
  - Pipelines
  - Kanban boards
  - Auto-cloud-based load testing
- *GitHub (a development host)*
  - Version control
  - Source code management
  - Bug/task management
- *GitHub Actions for Azure*
  - Automate in GitHub to build, test, & deploy
- *Azure DevTest Labs*
  - Quickly create environments in Azure while minimizing waste & controlling cost

-----

## Azure Management Tools
- *Azure Portal*
- *Azure PowerShell*
- *Azure Mobile App*
- *Azure Command Line / Azure Batch*
- *Azure REST API*
- *Azure Cloud Shell*
- ***Azure Advisor***
  - Analyzes deployed resources & makes recommendations on:
  - Reliability, Security, Performance, Cost, and Operational Excellence
- ***Azure Monitor***
  - Maxmizes the availability and performance of apps-&-services by collecting, analysing & acting on telemetry
  - Application insights
  - Log analytics
  - Smart alerts
  - Automation actions
  - Customized dashboards
- ***Azure Service Health***
  - Evaluate the impact of service issues with support, provides a personalized view of:
  - Planned maintenance
  - The regions being used
  - Health of Azure services
  - Communication regarding outage
- ***Azure Resource Manager (ARM) templates***
  - JSON configuration files to repeatably create & deploy Azure infrastructure without commands
  - Declarative syntax
  - Repeatable results
  - Orchestration
  - Modular files
  - Built-in validation
  - Exportable code

-----

<br>

## Data management

### Moving Data
- *Azure Migrate* - A unified data-migration platform
- *Azure Data Box*
  - Store up & protect 80TB of disaster recoverable data
  - Protected in rugged case during transit

### File management
- *AzCopy* - Copy blobs or files from your storage account (one-directional sync)
- *Azure Storage Explorer* - A GUI similar to Windows Explorer
- *Azure File Sync* - Sync Azure & on premises files bidirectionally with
  - Cloud tiering: - keeps frequently accessed files local to free up space
  - Rapid reprovisioning: - recover failed local server

### CI/CD
- Continuous integration
- Continuous delivery/Continuous deployment

-----

<br>

## Quiz

#### _________ is a repeatable set of governance tools that helps development teams quickly build and create new environments while adhering to organizational compliance to speed up development and deployment.
- Azure Blueprints

#### __________ rapidly provisions and runs new environments with the knowledge that they are in line with the organization's compliance requirements.
- Azure Blueprints

#### What two components could you use to implement an "infrastructure as code" deployment?
- Azure Blueprints
- ARM Templates

#### How many parameters does an Azure Blueprint Artifact need to be valid?
- 0

#### Which of the following is an attribute of Azure Resource Manager Templates?
- Repeatable results

#### What are sections of a Resource Manager Template
- `$schema, contentVersion, parameters, variables, functions, resources, outputs

#### What is ARM QuickStart Templates? Where are templates deployed?
- Resource Manager templates provided by the Azure community.
- Deployed in Resource Groups

#### What language are ARM templates written in?
- JSON

#### What is JSON
- A collection of key-value pairs

#### These items allow easier organization of resources.
- Tags

#### What Azure feature can help stay organized and track usage based on metadata associated with resources?
- Tags

#### __________ is a managed service hosted in the cloud that acts as a central message hub for bi-directional communication between IoT applications and the devices it manages.
- Azure IoT Hub

#### When using Azure IoT Hub service, what does 'command and control' apply to?
- Cloud-to-device communication

#### Which is not one of the recommendation categories for Azure Advisor?
- Capacity

#### Which of the following Azure services has pre-trained models available for you to send data to for predictions?
- Azure Cognitive Services

#### As part of Azure DevOps, what service would you use for adopting CI/CD for a development team?
- Azure Pipelines

#### __________ is a fully managed global IoT SaaS solution that makes it easy to connect, monitor, and manage IoT assets at scale
- Azure IoT Central

#### __________ is a secured, high-level application platform w/ built-in communication and security features for internet-connected devices.
- Azure Sphere

#### Which of the following is not an Azure Management tool?
- Azure Linux Desktop

#### __________ alerts you when service issues occur in an Azure environment, such as a regional Azure outage that affects all Azure customers.
- Azure Service Health

#### What can you use to launch the Azure Cloud Shell?
- Azure portal (click the cloud shell button to launch)

#### Which Azure serverless computing technology provides the ability to execute workflows to automate business scenarios by using triggers without writing any code?
- Azure Logic Apps

#### What service helps you manage your Azure, on-premises, and multi-cloud environments?
- Azure Arc

#### You use __________ to organize resources in an Azure subscription.
- Resource groups