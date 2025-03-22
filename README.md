# osTicket-Ticket-Lifecycle-Examples
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - osTicket Ticket Lifecycle Examples</h1>
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
   osTicket-vm public ip address -> remote desktop -> enter Username/Password

2. Open admin/analyst login page http://localhost/osTicket/scp/login.php -> Open end user login page http://localhost/osTicket

TICKET #1

3. Create a Ticket (as End User created in Previous lab)
   End User login page -> Open a New ticket -> Enter End User email address -> Enter End User Name -> Enter phone numder -> Select Help topic -> Enter Issuse Summary (Main focus of the ticket) -> Enter discription of the ticket -. Create Rticket

4. Observe Ticket (as agent created in Previous lab)
   login to Admin/Analyst webpage -> Enter Agent Username/Password -> Click on the ticket -> Observe the "Priority, department, Assigned To, SLA Plan"

5. Set Priorities (Change or Add)
   Set SLA to highest level (created in Previous lab) -> Change Help topic to "Report a Problem: Business Critical Outage" -> Assign to a team (created in Previous lab)

6. Log out of Admin/Analyst webpage as current agent -> Login as the other Agent 

7. Work the ticket to completion (as the orther agent who just logged into Analyst webpage)
   Click the ticket -> Reassign to yourself/claim the ticket (due to this agent being a member of the Online banking team) -> Type in your observation of the suspected problem and potential solution then Post -> Type that you solved the problem with stated solution then Post-> Under Status click "Open" -> select Resolved -> Close

TICKET #2

8. Create a Ticket (as End User created in Previous lab)
   End User login page -> Open a New ticket -> Enter End User email address -> Enter End User Name -> Enter phone numder -> Select Help topic -> Enter Issuse Summary (Main focus of the ticket) -> Enter discription of the ticket -. Create Rticket

9. Observe Ticket (as agent created in Previous lab)
   login to Admin/Analyst webpage -> Enter Agent Username/Password -> Click on the ticket -> Observe the "Priority, department, Assigned To, SLA Plan"

10. Set Priorities (Change or Add)
   Set SLA to lowest level (created in Previous lab) -> Change to Department *Support* (created in Previous lab) -> Assign to Agent (agent currently observing ticket)

11. Work the ticket to completion (as the current agent)
   Click the ticket -> Type in your observation of the suspected problem and potential solution then Post -> Type that you solved the problem with stated solution then Post-> Under Status click "Open" -> select Resolved -> Type a summary of finished ticket -> Close

TICKET #3

3. Create a Ticket (as End User created in Previous lab)
   End User login page -> Open a New ticket -> Enter End User email address -> Enter End User Name -> Enter phone numder -> Select Help topic -> Enter Issuse Summary (Main focus of the ticket) -> Enter discription of the ticket -. Create Rticket

4. Observe Ticket (as agent created in Previous lab)
   login to Admin/Analyst webpage -> Enter Agent Username/Password -> Click on the ticket -> Observe the "Priority, department, Assigned To, SLA Plan"

5. Set Priorities (Change or Add)
   Set priority to Emergency -> set SLA to mid level (created in Previous lab) -> Assign to Agent (agent currently observing ticket)

7. Work the ticket to completion (as the current agent)
   Click the ticket -> Type in your observation of the suspected problem and potential solution then Post -> Type that you solved the problem with stated solution then Post-> Under Status click "Open" -> select Resolved -> Type a summary of finished ticket -> Close


Crongratulations on Successfully creating three differnt tickets and also working/resolving each ticket. Now you can practice these steps as many times you want to familurize 
