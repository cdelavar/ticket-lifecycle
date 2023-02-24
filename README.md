<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.For this lab, I'm using a virtual machine I created in Azure.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://youtu.be/ruBs9OKgPmA)

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

<p>
<img src="https://imgur.com/7y7uXs8.png" height="80%" width="80%" alt="Support Center"/>
</p>
<p>
<b>End users can open tickets with the Suport Center home page. Navigate to http://localhost/osTicket/ and click on Open a New Ticket.</b>
</p>
<br />

<p>
<img src="https://imgur.com/i5G9fHb.png" height="80%" width="80%" alt="Create New Ticket  "/>
</p>
<p>
<b>Let's create some tickets as end users, for us to solve as the help desk professional. A user will fill out the new ticket form and include their name, email address, choose a help topic from the drop down menu, and write a summary of the problem. They could also attach any images that could help the agent solve the problem.</b>
</p>
<br />

<p>
<img src="https://imgur.com/RGTfDDG.png" height="80%" width="80%" alt="Filled out ticket"/>
</p>
<p>
<b>When the form is filled out, click Create Ticket, then create a couple more.</b>
</p>
<br />

<p>
<img src="https://imgur.com/FKZAOts.png" height="80%" width="80%" alt="Filled out ticket two"/>
</p>
<p>

<p>
<img src="https://imgur.com/KFBnKV2.png" height="80%" width="80%" alt="Agent Panel Open Tickets"/>
</p>
<p>
<b>Login to osTicket as a helpdesk agent to see the user created tickets. In this case, the tickets have been configured to automatically appear in the open ticket inbox of any agent in the Support Department. The tickets are not assigned to any agents when they are created. A helpdesk agent, or queue manager, will have to go through each ticket and assign them to agents and update their priorities. </b>
</p>
<br />

<p>
<img src="https://imgur.com/sJkS6GR.png" height="80%" width="80%" alt="Update Priority"/>
</p>
<p>
<b>Let's open the ticket with the issue "Entire Mobile Banking Is Down". The Priority level for the ticket is set to Normal by default. Click on Priority and change the Priority Level to "Emergency". The issue for this ticket is critical and will negatively impact the business if left unfixed for too long.</b>
</p>
<br />

<p>
<img src="https://imgur.com/nr6IH9U.png" height="80%" width="80%" alt="Assign Agent"/>
</p>
<p>
<b>Click on Assigned To and assign an Agent to the ticket.</b>
</p>
<br />

<p>
<img src="https://imgur.com/IliaFV8.png" height="80%" width="80%" alt="Update SLA"/>
</p>
<p>
<b>The SLA Plan is currently set to Default SLA, which is non-critical. Update the SLA Plan to SEV-A for this emergency issue ticket.</b>
</p>
<br />

<p>
<img src="https://imgur.com/a62XhIh.png" height="80%" width="80%" alt="Update Department"/>
</p>
<p>
<b>The Department assigned to this ticket might not be equipped to handle this issue. This sounds like a system issue that needs to be handled by the system administrators. Click on the Department and change from Support to System Administrators.</b>
</p>
<br />

<p>
<img src="https://imgur.com/4h1dcX9.png" height="80%" width="80%" alt="Ticket Updates Log"/>
</p>
<p>
<b>Whenever a change is made to the ticket, a log entry will be created in the ticket with details about each update.</b>
</p>
<br />

<p>
<img src="https://imgur.com/uR1lqpG.png" height="80%" width="80%" alt="Close Ticket"/>
</p>
<p>
<b>When an issue has been resolved, a ticket can be closed by updating the ticket status to "Resolved" and clicking Post Reply. </b>
</p>
<br />

<p>
<img src="https://imgur.com/UXVns1z.png" height="80%" width="80%" alt="Closed Ticket Tab"/>
</p>
<p>
<b>Once the ticket status has been updated, it will be removed from the open ticket queue and will now only be viewable in the Closed ticket tab.</b>
</p>
<br />

<p>
<img src="https://imgur.com/Osg7jVq.png" height="80%" width="80%" alt="Update Ticket Two"/>
</p>
<p>
<b>Let's open the "Entire Accounting Dept Adobe Reader Not Working" ticket and change the Priority Level. This doesn't seem to be an emergency, but if everyone in the accounting department can't use their Adobe Reader and they need it to do their job, this would be a high priority to troubleshoot. We'll change the Priority Level to High. Let's also change the SLA to SEV-B which would require a 24/7 response within 4 hours. Lastly, assign the ticket to a helpdesk agent.</b> 
</p>
<br />

<p>
<img src="https://imgur.com/xdFF2F3.png" height="80%" width="80%" alt="Close Ticket Two"/>
</p>
<p>
<b>The high priority ticket is assigned to helpdesk agent Wigburg Boulder, so let's log into his account and close out the ticket. We'll add a note about the actions that were taken to solve the issue in the Internal Note box. The Ticket Status should be changed to Resolved.</b>
</p>
<br />


