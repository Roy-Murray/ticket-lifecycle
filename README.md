<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

  - Microsoft Azure
  - Remote Desktop
  - IIS

 <h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<h3>Create Tickets as end user</h3>
- create a ticket with a scenario

- **Scenario 1:** Create a ticket as an end-user with the following details:
  - **Subject:** "Entire mobile/online banking system is down"
  - **Details:** Describe the issue briefly (e.g., "The entire online banking system is down, preventing users from accessing their accounts.")

![image](https://github.com/user-attachments/assets/955a0507-5db0-480a-9b87-46378e510010)

<h3>2.) Observe Ticket Properties as Help Desk Agent</h3>

- Log in as **Help Desk Agent (john)**.
- Observe the ticket’s properties:
  - **Priority:** Default value.
  - **Department:** Default department.
  - **SLA:** Default SLA.
  - **Assigned To:** Not yet assigned.
 
  ![image](https://github.com/user-attachments/assets/3a13ce1d-dff0-42d4-9cec-f30fb1697f1b)

  
<h3>3.) Set Ticket Properties</h3>

- Update the ticket with the following properties:
  - **SLA:** Sev-A (1 hour, 24/7).
  - **Assigned To:** Online Banking Department. (Jane)
 
  ![image](https://github.com/user-attachments/assets/304f29ff-79ba-49f0-bb6d-1ef414888c15)

  <h3>4.) Verify Ticket Permissions</h3>

- Log back in as **Help Desk Agent (john)**.
- Attempt to view or modify the ticket. Verify whether the changes are accessible or editable.



  
