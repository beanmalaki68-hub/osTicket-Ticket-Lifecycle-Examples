<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />



https://github.com/user-attachments/assets/5617d74b-dbe1-4190-930c-cbceb0d31156



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows (Windows 11 Pro)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

# Step 1 - Remoting into the Virtual Machine and creating a ticket as Karen

First, I used remote desktop to log into my virtual machine. Then I create a ticket as Karen for us to work.

<h2>Video Walkthrough</h2>


https://www.youtube.com/watch?v=_rqSR4kBVyY&list=PLZr1iJyCzL_0&index=1


# Step 2 - Login as John to view the Ticket, and then editing Johns permissions

I then logged in as John and viewed the ticket. Since John only had view access I logged onto the admin account and gave him more access.

<h2>Video Walkthrough</h2>

https://youtu.be/I3lB3knZY9w


# Step 3 - 

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

