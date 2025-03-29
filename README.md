# osTicket-Ticket-Lifecycle-Examples
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h2>Discription </h2>

This tutorial demonstrates the creation of three mock tickets ond resolve them (work to completion) as a Help Desk Analyst in the free help desk ticketing system osTicket.<br />
 
<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Azure Virtual Machine
- osTicket v1.15.8


<h2> Ticket Creation and Completion Steps</h2>

1. Login to osTicket-vm
 <p> 
</p>

osTicket-vm public ip address -> remote desktop -> enter Username/Password
 <p> 
</p>

![image](https://github.com/user-attachments/assets/7cfc5936-8abf-407e-b10b-f896f5d0c434)
 <p> 
</p>

![image](https://github.com/user-attachments/assets/6c574e4c-84d4-4f5a-8211-14696f62d759)
 <p> 
</p>

2. Open admin/analyst login page http://localhost/osTicket/scp/login.php -> Open end user login page http://localhost/osTicket
 <p> 
</p>

![image](https://github.com/user-attachments/assets/e17a9f8a-8ebf-4151-a611-098dd8c60b20)
![image](https://github.com/user-attachments/assets/ec2a1084-85f6-4226-a00e-88166994a0b2)

TICKET #1

3. Create a Ticket (as End User created in Previous lab)
 <p> 
</p>

End User login page -> Open a New ticket -> Enter End User email address -> Enter End User Name -> Enter phone numder -> Select Help topic -> Enter Issuse Summary (Main focus of the ticket) -> Enter discription of the ticket -> Create Rticket
 <p> 
</p>

![image](https://github.com/user-attachments/assets/ec2a1084-85f6-4226-a00e-88166994a0b2)
![image](https://github.com/user-attachments/assets/9ce1e805-c2be-46c5-baa5-f01a9518b998)

4. Observe Ticket (as Agent "John" created in Previous lab)
 <p> 
</p>

login to Admin/Analyst webpage -> Enter Agent Username/Password -> Click on the ticket -> Observe the "Priority, department, Assigned To, SLA Plan"
 <p> 
</p>

![image](https://github.com/user-attachments/assets/e17a9f8a-8ebf-4151-a611-098dd8c60b20)
![image](https://github.com/user-attachments/assets/c07977a9-d739-402c-a981-5067a5256f52)

5. Set Priorities (Change or Add)
 <p> 
</p>

Set SLA to highest level (created in Previous lab) -> Change Help topic to "Report a Problem: Business Critical Outage" -> Assign to a team (created in Previous lab)
 <p> 
</p>

![image](https://github.com/user-attachments/assets/4cddbe58-250e-49a4-9f15-d667ac6b7d45)
![image](https://github.com/user-attachments/assets/6617aedc-4d2b-4ffe-a678-a038baf9238c)
![image](https://github.com/user-attachments/assets/6b2a6149-5a86-491e-a000-38744220eb65)
![image](https://github.com/user-attachments/assets/1b72da89-f608-42bf-a0f8-16a2beb0d12a)

6. Log out of Admin/Analyst webpage as current Agent -> Login as the other Agent 
 <p> 
</p>

7. Work the ticket to completion (as the orther Agent who just logged into Analyst webpage)
 <p> 
</p>

Click the ticket -> Reassign to yourself/claim the ticket (due to this agent being a member of the Online banking team) -> Type in your observation of the suspected problem and potential solution then Post -> Type that you solved the problem with stated solution then Post-> Under Status click "Open" -> select Resolved -> Close
 <p> 
</p>

TICKET #2

8. Create a Ticket (as End User created in Previous lab)
 <p> 
</p>

End User login page -> Open a New ticket -> Enter End User email address -> Enter End User Name -> Enter phone numder -> Select Help topic -> Enter Issuse Summary (Main focus of the ticket) -> Enter discription of the ticket -. Create Rticket
 <p> 
</p>

9. Observe Ticket (as agent created in Previous lab)
 <p> 
</p>

login to Admin/Analyst webpage -> Enter Agent Username/Password -> Click on the ticket -> Observe the "Priority, department, Assigned To, SLA Plan"
 <p> 
</p>

10. Set Priorities (Change or Add)
   Set SLA to lowest level (created in Previous lab) -> Change to Department *Support* (created in Previous lab) -> Assign to Agent (agent currently observing ticket)

11. Work the ticket to completion (as the current agent)
 <p> 
</p>

Click the ticket -> Type in your observation of the suspected problem and potential solution then Post -> Type that you solved the problem with stated solution then Post-> Under Status click "Open" -> select Resolved -> Type a summary of finished ticket -> Close
 <p> 
</p>

TICKET #3

12. Create a Ticket (as End User created in Previous lab)
 <p> 
</p>

End User login page -> Open a New ticket -> Enter End User email address -> Enter End User Name -> Enter phone numder -> Select Help topic -> Enter Issuse Summary (Main focus of the ticket) -> Enter discription of the ticket -. Create Rticket
 <p> 
</p>

13. Observe Ticket (as agent created in Previous lab)
 <p> 
</p>

login to Admin/Analyst webpage -> Enter Agent Username/Password -> Click on the ticket -> Observe the "Priority, department, Assigned To, SLA Plan"
 <p> 
</p>

15. Set Priorities (Change or Add)
 <p> 
</p>

Set priority to Emergency -> set SLA to mid level (created in Previous lab) -> Assign to Agent (agent currently observing ticket)
 <p> 
</p>

16. Work the ticket to completion (as the current agent)
 <p> 
</p>

Click the ticket -> Type in your observation of the suspected problem and potential solution then Post -> Type that you solved the problem with stated solution then Post-> Under Status click "Open" -> select Resolved -> Type a summary of finished ticket -> Close
 <p> 
</p>

Crongratulations on Successfully creating three differnt tickets and also working/resolving each ticket. Now you can practice these steps as many times you want to familurize 
