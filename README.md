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

- Add/Configure Roles/Departments/Teams
- Add/Configure Agents(Workers)/Users(Customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/lGIT4d3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/hDkKWZR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this step we add the roles, departments, and teams. We then configure them to the needs of the company. All three play a part in making each user and their permissions/access unique for their specific job description.
</p>
<br />

<p>
<img src="https://i.imgur.com/w1qXVXL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/kqzeO5h.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/ZmkiENZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here we add the Agents(Workers) and Users(Customers) and configure them to our needs. In the images above, the process for creating the agents are shown, as well as assigning them to their specific role, department, and team. I made the user "Jane Doe," and assigned her to the System Admin department, and the Level II Support role.
</p>
<br />

Here is the after photo of the users I created. These are simply made for the lab, but in a real setting would have more specifics to them, and there would be a lot more of them.
<img src="https://i.imgur.com/85KODTb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>
<img src="https://i.imgur.com/GPnGlHT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/ZILF4Yl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Above is the process for configuring the SLA (Service Level Agreement). The SLA controls the severity/priority of a ticket, and is useful in determining which ticket a HelpDesk Professional should tend to first. There are three severity levels I created for this lab: Sev-A, Sev-B, and Sev-C. Sev-A is the highest severity, and must be tended to within an hour of creation, 24/7. This means that despite the time of day, the HelpDesk Professional assigned to it has one hour to make a comment or acknowledge its creation. Sev-B is similar, however instead of one hour to respond, you have four. Sev-C is the lowest severity one, and gives the HelpDesk User 8 hours to respond, only pertaining to business hours. For instance, If a Sev-C ticket is made at friday at 4pm, assuming a 9-5, Mon-Fri workweek, that ticket can be tended to as late as the following Monday at 4pm.
</p>
<br />
Help topics are the most common issues that a User/Agent may have in a business environment, and are made to make the problem-solving process quicker for the HelpDesk Professional by allowing whoever created the ticket to choose from a list of issues that are most likely to occur. Below are some of the most common help topics:
<img src="https://i.imgur.com/0ZnwjZh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
