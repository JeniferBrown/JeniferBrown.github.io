
Sage Users Guide

# Introduction

The Sage product will save you time and money by proving reports that will detail the effort needed to upgrade and modernize your application to run in the Cloud.

Using the Sage product, you will simply onboard your application, set up roles, upload your source code and answer a few questions about your application and you will soon have 5 detailed reports giving you the information you need to make informed decisions on cost and effort to modernize your application to run in the Cloud.  The Sage product uses multiple industry proven application scanning tools, like CAST Highlight and SonarQube, to compile data that will provide you with the most up to date and accurate information available regarding your applications code quality and Cloud readiness.

The purpose of this guide is to help get you up and running with Sage today.  This users guide will provide you with step by step instructions to set up your account, onboard your application, handle your configurations and analyze your Sage provided reports. And of course, if you have any issues don't hesitate to contact our support team at *some support info here*.

# Sage Cloud App Modernization

This is a space for Sage Cloud App Modernization - best practices information

**_Roger to provide diagram and words here_**

# Getting Started

Let's get started using Sage!

## System Requirements

- Browser requirements??
- Some installation completed for backend??
- Soure code and artifacts available to machine running UI 

## Security Consideratons

*SSP support for your organizations security requirements*

## First Time Login

### Create Account

Register for your account and create a password in KeyCloak.
*Sample images of KeyCloak account screen with details of use*

Administrators will log in and perform all role assignments for registered users.
*Sample images of Administrators steps to assign roles*

Play the video to see a calculator add 2+2 *This is just an example video*
<video width="320" height="240" controls>
  <source src="../Image/calculator.mp4" type="video/mp4"></source>
</video>


### Security and Password Management

Passwords for Sage must follow the below criteria:

- Have a minimum length of 8 characters
- Must contain at least one alphabetic character
- Must contain at least one upper case character
- Must contain at least one lower case character
- Muust contain at least one numeric character
- Must be changed every 180 days
- Must not be the same password as the previous six passwords

# Managing Your Applications

## Onboarding Your Application

In order to process your application through the Sage product, you will need to onboard your application. Please watch the following video for an overview of the onboarding process.

*onboarding video here*

Now, you can follow these easy steps to complete your application onboarding:

1. Select the Onboarding Icon

*Screenshot here*

2. Enter your application name and its acroynm

*Screenshot here*

3. Enter all fields for Ownership Contacts and other points of contact 

*Screenshot here*

4. Select the Upload Source Code Icon

*Screenshot here*

5. Upload your zipped up source code 

*Screenshot here*

:warning: Zipped up source code files cannot exceed 500MB.  If your application source code is larger than 500MB, it will need to be split apart and zipped up into logical blocks that are smaller than 500MB and then you will need to follow the entire onboarding process for each zip file.

6. Select the Upload Artifacts Icon if you have any artifacts to include

*Screenshot here*

7. Upload any application artifacts or documents

*Screenshot here*

### Issues with your Application Onboarding?

Please refer to our Sage Operations Manual for troubleshooting tips.
*Link to Operations Manual*


## Survey Management 

In order to provide you with the most accurate Cloud readiness anaylysis, you need to complete a short survey with questions regarding your application and its dependencies and interfaces.  Please be sure to provide the most accurate information as possible as incorrect answers can affect your output.

Please watch the following video for a quick overview of completing the survey.

*Video Here*

Now, follow these steps to complete your survey:

1. Select the Survey Icon

*Screenshot here*

2. Answer all the survey questions

*Screenshot here*

:::important
Survey answers need to be as accurate as possible.  Seek out the assistance of your application software experts if you don't know the answers as incorrect survey values can affect your output.
:::

3. Select OK

*Screenshot here*

### Survey Question Details



|Survey Question| Possible Answers |Question Details or Examples|
|---------------|----------------|----------------|
|What is the system type|1. Legacy System<br>2. Cloud System|1. Non-Cloud Based System<br>2. Cloud Based System  |
|What is the architechture of the system?|Web System (3-Tier)<br>1. Thick Client System<br>2. Mainframe System|  |
|What is the data impact level of this system?|IL-2<br>IL-4<br>IL-5<br>IL-6<br>IL-7|PUBLIC<br>CUI or Non-CUI<br>Higer Sensitivity CUI<br>SECRET<br>TOP SECRET|
|What type of primary interface is associated with this system?|1. HTTPS Based<br>2. Non-HTTPS Based<br>3. Rest<br>4. UDP, TCP, etc|
|How many primary interfaces are associated with this system?|0-20|Number of primary interfaces |
|What type of secondary interface is associated with this system?|1. HTTPS Based<br>2. Non-HTTPS Based<br>3. Rest<br>4. UDP, TCP, etc|
|How many secondary interfaces are associated with this system?|0-20|Number of secondary interfaces |
|What is the primary database type for this system?|1. Niche<br>2. Available Paas<br>3. No Database| |
|How many primary databases are associated with this system?|0-20| |
|What primary database components are usedfor this system?|1. DB Links<br>2. Stored Procs<br>3. Both<br>4. None| |
|What is the secondary database type for this system?|1. Niche<br>2. Available Paas<br>3. No Database| |
|How many secondary databases are associated with this system?|0-20| |
|What secondary database components are usedfor this system?|1. DB Links<br>2. Stored Procs<br>3. Both<br>4. None| |
|Does this system use CAC for authentication?|Yes<br>No| |
|What user token does the system use?|1. SAML<br>2. JWT<br>3. Other|1. Security Assertions Markup Language<br>2. JSON Web Token<br>3. Anything else|
|Does the system use Shared Filesystems or Shared Caching?|Yes<br>No| |
|Does this system use messaging based products?|Yes<br>No|MQSeries, Apache Kafka, MuleSoft Anypoint Platform, RabbitMQ, and Apache ActiveMQ or others|
|Does this system have a need for real-time data syncronization?|Yes<br>No| |
|Does this system have use of Propietary Tools/ETL/BI/COTS products?|Yes<br>No| |


## Migration Metric and Data

### Application Assessment

### Application Technical Debt

### Application Cloud Readiness 

### Application Cost Estimate 

### CAST Highlight Dashboard 

### SonarQube Dashboard

### Metabase Dashboard 



## Migration Estimate

In order to create your migration estimates, you will need to run the Migration Estimation tool on against your uploaded code results and completed survey.  Please watch the following viedo for a quick overview of running migration estimates.

*Video Here*

Peform the following steps to create your migration estimates.

1. Select the Migration Estimate Icon

*Screenshot here*

2. Select run

*Screenshot here*

3. Once the migration estimate is complete the report will be available....??
 
*Screenshot here*