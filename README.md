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

## Configure Roles
- Log in using the 'user_admin' account created during the prerequisites and installation.
- Navigate to Admin Panel -> Agents -> Roles -> Add New Role.
- Create a new role, e.g., 'Supreme Admin', and grant all permissions under Tickets, Tasks, and Knowledgebase tabs.

## Configure Departments
- Access Admin Panel -> Agents -> Departments -> Add New Department.
- Create departments for organizing tickets, e.g., 'System Administrators'.

## Configure Teams
- Go to Admin Panel -> Agents -> Teams -> Add New Team.
- Create teams to organize agents across departments, e.g., 'Level II Support'.

## Configure Agents
- Access Admin Panel -> Agents -> Add New.
- Create agents responsible for resolving tickets, specifying their roles, departments, and teams.

## Configure Users
- Navigate to Agent Panel -> Users -> Add New.
- Create users who will submit tickets into the system.

## Allow Anyone to Create Tickets
- In Admin Panel, under Settings, ensure Registration Required is unchecked to allow ticket submission without logging in.

## Configure SLA Plans
- Access Admin Panel -> Manage -> SLA -> Add New SLA Plan.
- Create SLA plans specifying response times and schedules for different ticket severities.

## Configure Help Topics
- Go to Admin Panel -> Manage -> Help Topics -> Add New Help Topic.
- Create topics to categorize tickets based on their nature or severity.

## Conclusion
By following these steps, you have completed the post-installation configuration of osTicket. For further details on ticket lifecycles, refer to the osTicket - Ticket Lifecycle: Intake Through Resolution Lab.
