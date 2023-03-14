<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<h3>Intake - Creating a Ticket</h3>

- Click [link](http://localhost/osTicket/).
- Select Open a New Ticket
  - Email Address: Karen@osticket.com
  - Name: Karen Karen
  - Help Topic Dropdown Menu: Business Critical Outage
    - Issue Summary: Bank System is down
    - Details: Customers are reporting they are getting a 404 error when browsing to online banking
  - Create Ticket
<p>
<img src="https://i.imgur.com/jxNLg7q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/P80fPxq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


<p>
<h3>Assignment and Communication</h3>

- Sign into osTicket as an Agent
  - Use user jane.doe's credentials created in the previous tutorial. 
  - Select the ticket we created in Step 1.
  
  
<p>
<img src="https://i.imgur.com/U8LEFxV.png" height="80%" width="80%" /> 
</p>


 - Priority: Emergency. 
      - The mobile online banking app is high priority because it prevents users from using. 
 - Assigned to: Jane Doe
 - SLA Plan: SEV-A 
      - Business Impacting, critical incident
 - Department: System Administrators 
      - Sys Admins responsible for mobile banking infrastructure
 - Response text box: Currently cooperating with the System Admin Team to get the problem solved.
    - Select Post Reply


<p>
<img src="https://i.imgur.com/Fts0LMN.png" height="80%" width="80%" />
<img src="https://i.imgur.com/BFbtNfF.png" height="80%" width="80%" />
</p>

<h3>Resolving the Issue</h3>

- Jane and the system admin team coordinate to solve the issue. 


<h3> Resolution</h3>
     
- Once the issue is resolved, head back to the ticket and update the server.
  - Response text box:  issue has been resolved  Ticket closed.
  - Ticket Status: Resolved
- Select Post Reply
- Observe the ticket presenting "closed".

<p align="center">
<img src="https://i.imgur.com/6tpDbBo.png" height="80%" width="80%" /> <img src="https://i.imgur.com/Fts0LMN.png" height="80%" width="80%" />
</p>

Done.
