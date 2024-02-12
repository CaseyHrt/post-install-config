<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket Post-Installation Setup Guide

## Introduction
This guide outlines the steps required to configure osTicket, an open-source help desk ticketing system, after installation. It builds upon the prerequisites and installation steps covered in the previous lab.

## Environment and Tools
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- osTicket
- Internet Information Services (IIS)
- Operating System: Windows 10 (21H2)

## Objectives of Post-Installation Configuration
1. Get acquainted with the osTicket UI.
2. Set up roles, departments, teams, and users.
3. Configure Service Level Agreement (SLA) plans and help topics.

## osTicket UI Overview
The osTicket UI consists of two panels: the Agent Panel and Admin Panel. The current panel being viewed is indicated in the top right corner.

![image](https://github.com/CaseyHrt/post-install-config/assets/146404028/61b8b2fb-e0fe-49be-89fd-f02d3e6000ad)

## Configure Roles
- __Log in using the 'user_admin' account:__ This account should have been created during the prerequisites and installation steps.
- __Navigate to Admin Panel -> Agents -> Roles -> Add New Role:__ Here, users can create custom roles with specific permissions tailored to the needs of different agents.

![image](https://github.com/CaseyHrt/post-install-config/assets/146404028/2010d056-d3f2-40cf-9685-20b150011ed6)

![image](https://github.com/CaseyHrt/post-install-config/assets/146404028/b61eadaa-395d-497a-820d-f1c93d9f0b47)

![image](https://github.com/CaseyHrt/post-install-config/assets/146404028/823c5f75-2c24-47e2-80b2-93a40538bdd7)

![image](https://github.com/CaseyHrt/post-install-config/assets/146404028/97e7c221-3389-44ad-80b4-a601eba91d37)

![image](https://github.com/CaseyHrt/post-install-config/assets/146404028/5ec39542-e75a-4dcf-a845-60dac47d81d8)

![image](https://github.com/CaseyHrt/post-install-config/assets/146404028/bf8c9357-2aec-4dd2-bfa8-ff02fdd4fd1b)

## Configure Departments
- __Access Admin Panel -> Agents -> Departments -> Add New Department:__ Departments help organize tickets and assign them to appropriate agents based on their specialization or responsibilities.
  
![image](https://github.com/CaseyHrt/post-install-config/assets/146404028/ff77006d-8792-4374-8882-c6559df79dd2)

![image](https://github.com/CaseyHrt/post-install-config/assets/146404028/2e5fceae-3815-4ce8-81f3-58b362f4066e)

## Configure Teams
- __Go to Admin Panel -> Agents -> Teams -> Add New Team:__ Teams allow for the grouping of agents from different departments to handle specific issues or tasks effectively.
  
![image](https://github.com/CaseyHrt/post-install-config/assets/146404028/9c65b19b-a7ce-4a84-a444-7195774c2e1b)

![image](https://github.com/CaseyHrt/post-install-config/assets/146404028/a91b718f-6da2-4cf9-bf8f-83de4b3ae5f9)

## Configure Agents
- __Access Admin Panel -> Agents -> Add New:__ Agents are individuals responsible for managing tickets within osTicket. This step involves creating agent accounts and specifying their roles, departments, and teams.

![image](https://github.com/CaseyHrt/post-install-config/assets/146404028/db43e214-b87c-401d-a3c6-3403debbb47c)

![image](https://github.com/CaseyHrt/post-install-config/assets/146404028/6a551dc3-164b-443a-b274-6922ff292533)

![image](https://github.com/CaseyHrt/post-install-config/assets/146404028/70c838bc-da4c-4f13-9e37-d551422d8402)

![image](https://github.com/CaseyHrt/post-install-config/assets/146404028/42dcddf1-6d7f-4921-9bf1-7eaafaeba602)

![image](https://github.com/CaseyHrt/post-install-config/assets/146404028/bc0f3203-1fc1-4400-b7d0-be42ff5ff003)



## Configure Users
- __Navigate to Agent Panel -> Users -> Add New:__ Users are individuals who submit tickets into the osTicket system. This step involves creating user accounts for ticket submission purposes.

![image](https://github.com/CaseyHrt/post-install-config/assets/146404028/9585ef73-b00d-4677-bf8d-43bd8b85e9d0)

![image](https://github.com/CaseyHrt/post-install-config/assets/146404028/32f3c941-70b2-42df-8621-98e04c8f2d9c)

![image](https://github.com/CaseyHrt/post-install-config/assets/146404028/9e5274ab-0b8c-401a-a424-4f6fb0a210ad)



## Allow Anyone to Create Tickets
- __In Admin Panel, under Settings, ensure Registration Required is unchecked:__ By allowing anyone to create tickets without logging in, users can submit issues or requests easily.

![image](https://github.com/CaseyHrt/post-install-config/assets/146404028/0299150c-c7a4-4a9e-9b7d-754d81e9f233)


## Configure SLA Plans
- __Access Admin Panel -> Manage -> SLA -> Add New SLA Plan:__ SLA plans define response times for different ticket severities, ensuring timely resolution of issues.

![image](https://github.com/CaseyHrt/post-install-config/assets/146404028/78f011c0-57bd-4352-bd31-8a11086f410a)

![image](https://github.com/CaseyHrt/post-install-config/assets/146404028/cbb1904f-dada-4798-bbe7-6ef1e084e06d)

## Configure Help Topics
- __Go to Admin Panel -> Manage -> Help Topics -> Add New Help Topic:__ Help topics categorize tickets based on their nature or severity, allowing for efficient routing and prioritization.

![image](https://github.com/CaseyHrt/post-install-config/assets/146404028/94d7901b-7d20-44af-94e3-2c06e235579b)

![image](https://github.com/CaseyHrt/post-install-config/assets/146404028/8715c251-d1b2-40b0-ba3b-e3b3324c1ee2)

## Conclusion
By following these steps, users can complete the post-installation configuration of osTicket, making it ready for efficient ticket management. Further details on ticket lifecycles can be explored in subsequent labs.
