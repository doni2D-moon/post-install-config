<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Steps 1-2 Creating Agents and Assignments
- Step 3 Creating SLAs
- Step 4 Creating Help Topics
- Step 5 Creating Users

<h2>Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/cee32ae9-f219-407d-a14e-b69bccf6392e)

<p>
<strong>Step 1:</strong> In this step, we will be adding agents along with their departments and access. In the "Admin Panel," go to "Agents" and then "Add New Agent." 1) Under "Account," fill out information for an agent and give a password under "Authentication" --> "Set Password" 2) In "Access," select a department for the agent and then select how much access the agent will be given next to the department name.
</p>
<br />

![image](https://github.com/user-attachments/assets/3d9d90ff-bdb3-4776-bfb6-694cd7b4cc56)

<p>
<strong>Step 2:</strong> For the same agent, go to "Teams" to assign an agent a team and then click "Add." After completing the information for the agent, click "Create" (in orange). After adding more agents, a list of those agents will be shown in the Agents List showing their name, username, status, and department.
</p>
<br />

![image](https://github.com/user-attachments/assets/e4ff7be1-d203-4d25-804e-5a0c1401dcc5)

<p>
<strong>Step 3:</strong> In this step, we will create SLAs (3 of them from Sev-A to Sev-C). After going to "Manage" under the Admin Panel, click "SLA" to add Service Level Agreements. Clicking on the "Add New SLA Plan" will bring up a window to put in information for an SLA. Under "Add New SLA Plan," 1) Give a name (ex. Sev-A), then 2) give a number of hours for the "Grace Period" (ex. 1 hour). After that, 3) set the timeframe in "Schedule" choosing between 24/5. 24/7, and Monday-Friday at specific times (business hours). Once completed, a list of SLAs will appear in the Service Level Agreements list with the status and grace period.
</p>
<br />

![image](https://github.com/user-attachments/assets/978139eb-1ee7-476b-b569-5650187cebc9)

<p>
<strong>Step 4:</strong> In this step, we will create help topics for users to click on the kind of issue they have. In the same place where SLA is, click on "Help Topics" to create a list of help topics. After clicking "Add New Help Topic," 1) give the name of the "Topic" (ex. Business Critical Outage) and then 2) choose one of the list as the "Parent Topic" (ex. Report a Problem or General Inquiry). After saving, a list of help topics created, we will find them listed under "Help Topics."
</p>
<br />

![image](https://github.com/user-attachments/assets/5849786c-2d13-42bc-baa5-32a88d2e7664)

<p>
<strong>Step 5:</strong> In this step, we will create users reporting problems. Clicking the "Agent Panel" will reveal a page where agents can see tickets and users. Under "Users," add a new user, input information for that user, and then click "Add User." After adding more users, the users' names and statuses will show under "User Directory." Setting up the roles and departments, agents, users, SLAs, and help topics will help when completing tickets.
</p>
<br />

