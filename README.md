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

- Windows (Windows 11 Pro)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img width="1023" height="886" alt="image" src="https://github.com/user-attachments/assets/97dae5be-c8d5-4a8c-9d0f-f6934ac28afa" />


</p>
<p>
First an end user would create a ticket using the ticket support system. It is always important to keep in mind that end users may not fill out the ticket %100 correctly and it is always important to gather as much information from the user as you can. 
</p>
<br />

<p>
<img width="1203" height="1027" alt="image" src="https://github.com/user-attachments/assets/28dd8bf9-efe4-4aba-bcbb-659fd7e5d90b" />

</p>
<p>
I logged in as a user to see if the ticket was submitted. I also wanted to highlight that John in this case has "Read Only" access which limited what he can do to tickets that are submitted. 
</p>
<br />

<p>
<img width="1221" height="921" alt="image" src="https://github.com/user-attachments/assets/0aaa5050-fb2b-43b0-81ef-66badf18088a" />

</p>
<p>
I then gave John higher privileges allowing him to change things Priority Level, SLA Plan, & and Help Topic. After the ticket is triaged either that IT professional will work the ticket to completion or escalate it to an IT professional who is higher up.
</p>
<br />

</p>
<img width="1209" height="728" alt="image" src="https://github.com/user-attachments/assets/2ef7e4f9-d32d-49ab-8528-446314f44de2" />

</p>
<p>After John assigned the ticket to the SysAdmins, he was no longer able to access it due to the way the permissions were configured. Jane, who is part of the SysAdmins department, then took ownership of the ticket and worked it through to completion. Before resolving the ticket, Jane confirmed with the end user that everything was operating normally. Once the issue was verified as resolved, she marked the ticket as resolved.</p>

# Summary

This lab focused on the **ticket lifecycle in osTicket**, from creating a ticket as an end user to assigning, managing, escalating, and resolving tickets as a help desk professional. The lab included creating multiple support tickets, reviewing ticket properties such as priority, department, Service Level Agreement (SLA), and assignment, and working tickets through completion. It also demonstrated how department permissions affect ticket access and how an administrator can provide an agent with access to escalated tickets. Finally, the lab covered real-world ticket intake methods, the importance of documenting all support work, and how email communication can be used to keep users updated throughout the ticket lifecycle.
