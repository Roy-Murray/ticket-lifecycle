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

<h3>5.) Work the Ticket to Completion</h3>

- Log in as **Help Desk Agent (jane)**.
- Take ownership of the ticket, work the issue, and resolve it.
- Mark the ticket as **Closed** once the issue is resolved.

![image](https://github.com/user-attachments/assets/a645ecd7-d0ca-4d4b-b5cb-730eb18c3dba)

<h3>6.) Create another Ticket as an End User</h3>

- **Scenario 2:** Create a ticket as an end-user with the following details:
  - **Subject:** "Accounting department needs Adobe upgrade, broken"
  - **Details:** Describe the issue briefly (e.g., "The Adobe software used by the accounting department is broken and needs an upgrade.")

![image](https://github.com/user-attachments/assets/71db2cdb-3ec1-48a7-b6a7-c361b5cbfc59)


<h3>7.) Observe Ticket Properties as Help Desk Agent</h3>

- Log in as **Help Desk Agent (john)**.
- Observe the ticket’s properties:
  - **Priority:** Default value.
  - **Department:** Default department.
  - **SLA:** Default SLA.
  - **Assigned To:** Not yet assigned.
 
  ![image](https://github.com/user-attachments/assets/f7ae5ead-f54e-4135-be93-8ea2defdfc14)

  <h3>8.) Set Ticket Properties</h3>

- Update the ticket with the following properties:
  - **SLA:** Sev-b (4 hours, 24/7).
  - **Department:** Support.
 
   ![image](https://github.com/user-attachments/assets/448fcec0-4f81-4c50-a639-249e1c4dd29a)
  
<h3>9.) Work the Ticket to Completion</h3>

- Log in as **Help Desk Agent (john)**.
- Take ownership of the ticket, work the issue, and resolve it.
- Mark the ticket as **Closed** once the issue is resolved.

![image](https://github.com/user-attachments/assets/aae08732-0427-479f-96b0-cd02d6deb296)

![image](https://github.com/user-attachments/assets/aed32b64-fdae-4ac4-88a9-d5199857547f)

![image](https://github.com/user-attachments/assets/dccf4dd6-041f-4364-95b5-8d39d939e124)


<h3>10.) Create a Final Ticket as an End-User</h3>

- **Scenario 3:** Create a ticket as an end-user with the following details:
  - **Subject:** "CFO’s laptop will no longer turn on"
  - **Details:** Describe the issue briefly (e.g., "The CFO's laptop is not powering on, and it needs urgent attention.")
 


![image](https://github.com/user-attachments/assets/7a5deb05-6df2-4147-98e7-c7c4d746391f)

<h3>11.) Observe Ticket Properties as Help Desk Agent</h3>

 - Log in as **Help Desk Agent (john)**.
- Observe the ticket’s properties:
  - **Priority:** Default value.
  - **Department:** Default department.
  - **SLA:** Default SLA.
  - **Assigned To:** Not yet assigned.


![image](https://github.com/user-attachments/assets/1d1da998-b995-4de2-96f1-24761d6f5305)

<h3>12.) Set Ticket Properties as Help Desk Agent</h3>

- update ticket with these properties:
 - **SLA:** Sev-B (4 hours, 24/7).
  - **Department:** Support.
  - **Priority Level:** Emergency
  - **Assign to:** John 

  
