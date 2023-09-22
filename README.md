<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

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

**Intake**
<p>
  We'll start by creating example support tickets as End Users. Go to the following URL inside the Edge browser to access the osTicket system Support Center: http://localhost/osTicket/. Click on Open a New Ticket. 
</p>

![image](https://github.com/marbienjimeno/ticket-lifecycle/assets/29347863/cc9150cd-d0ab-4c9b-b31a-dbcd3d166c7c)

<p>
  We will create a ticket as the user Karen Kove. For Email Address, enter "karen@osticket.com". For Full Name, enter "Karen Kove". For Help Topic, select Business Critical Outage. For Issue Summary, we'll enter "Entire mobile online banking is down". For the additional ticket details, enter "Customers are reporting they are getting a 404 error when browsing online banking". Click Create Ticket. 
</p>

![image](https://github.com/marbienjimeno/ticket-lifecycle/assets/29347863/9ed2a629-d529-4b58-a6ef-53e755ccfb96)

![image](https://github.com/marbienjimeno/ticket-lifecycle/assets/29347863/456cb6e5-a8c0-4be1-8817-22adc2931064)

**Assignment and Communication**

<p>
  Now we will log into osTicket as an Agent to start processing one of tickets. We will log in as Jane Doe. For Username, enter "jane.doe". For Password, enter "Password1".
</p>

![image](https://github.com/marbienjimeno/ticket-lifecycle/assets/29347863/805c5c90-e182-4739-9e25-d139d4e5d906)

<p>
  We should see the open tickets created by Users. Click on "Entire mobile online banking is down" to start assigning the ticket.
</p>

![image](https://github.com/marbienjimeno/ticket-lifecycle/assets/29347863/a5a0ba4b-d236-4eb9-afab-73a3ed613e3c)

<p>
  For Priority, we'll change it to Emergency. For the reason for the change, enter "Business impacting event".
</p>

![image](https://github.com/marbienjimeno/ticket-lifecycle/assets/29347863/103af501-3237-4727-bcb5-bf5910bed2df)

<p>
  For Department, transfer it to System Administrators. For Assigned To, Select Jane Doe as the Assignee. For SLA Plan, select SEV-A. 
</p>

![image](https://github.com/marbienjimeno/ticket-lifecycle/assets/29347863/8fe89a79-2484-4d90-9fb2-1abdeda478f1)

**Working the Issue**
<p>
  We are able to see the history of our changes through the Ticket Thread.
</p>

![image](https://github.com/marbienjimeno/ticket-lifecycle/assets/29347863/b3b72d7f-1606-4f0a-bd67-9076e91c1dd3)

<p>
  For our Reply, enter "Coordinating with Sys Admin to bring mobile banking back online". Click Post Reply.
</p>

![image](https://github.com/marbienjimeno/ticket-lifecycle/assets/29347863/20906616-a0c1-43eb-a2b9-9c390293cf9b)

**Resolution**
<p>
  After assigning the ticket and working the issue, we'll start resolving the ticket. Click on "Entire mobile online banking is down".
</p>

![image](https://github.com/marbienjimeno/ticket-lifecycle/assets/29347863/e37a8b64-8b76-4ca1-9a79-1fd14d9c641e)

<p>
  For a Reply, enter "Jerry from System Engineering found and corrected a failed load balancer. Mobile banking should be back up". For Ticket Status, change it to Resolved. Click Post Reply. 
</p>

![image](https://github.com/marbienjimeno/ticket-lifecycle/assets/29347863/f9fe4617-1022-4678-b98e-e85dbaac5ac8)

**Conclusion**
<p>
  In this lab, we followed and demonstrated the lifecycle of a helpdesk support ticket from intake to resolution using the osTicket ticketing system.
</p>
