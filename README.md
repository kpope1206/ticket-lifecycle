# ticket-lifecycle<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

In this lab, we will be creating tickets as end users
Observing all the ticket properties and responding to them as help desk professionals


* Change the SysAdmins Department to a Top Level Department
* DELETE the Maintenance Department (not archive)
________________




As an end-user, create the following ticket
entire mobile/online banking system is down


As a Help Desk Agent (john), observe the ticket’s properties
        Priority
        Department
        SLA
        Assigned To


Set Properties to the ticket
* Sev-A (1 hour, 24/7)
* Online Banking Department


Attempt to observe the ticket again as “john”. Can you view or change?


Work the ticket to completion as jane


________________




As an end-user, we will create the following ticket
accounting department needs adobe upgrade, broken


As a Help Desk Agent we will, observe the ticket’s properties
        Priority
        Department
        SLA
        Assigned To


Set Properties to the ticket
* Sev-B (4 hours, 24/7)
* Support


Work the ticket to completion as john


________________




As an end-user, create the following ticket
CFO’s laptop will no longer turn on


As a Help Desk Agent (john), observe the ticket’s properties
        Priority
        Department
        SLA
        Assigned To


Set Properties to the ticket
* Sev-B (4 hours, 24/7)
* Support


Work the ticket to completion as john
________________




Set Properties to all the tickets; do SEV-A (SysAdmins last), observe ticket becomes inaccessible
Switch to admin panel and assign yourself View-access to Sys Admins
Switch to agent panel and observe the escalated ticket
Observe that you can no longer make changes to it


Solve all of the tickets
Explain in most ticketing systems (probably this one too) there is an email capability so every time you update the ticket, the user gets a copy and they can respond


Explain ticket intake IRL:
Sometimes tickets get created via phone, chat app, email, web form, or maybe even you run into someone in your hall or they roll up on you at your desk.
A lot of the time people will randomize you and try to get you to fix stuff on the spot. It’s fine to fix things on the spot, but generally speaking, you want to create tickets for EVERYTHING you do. (metrics are important)


Finishing up and additional practice
Obviously there is much more to this product that covered here
Encourage the use and exploration of the email feature
Do this lab a few more times, enough times where you’re able to implement it with this simple checklist. This will build your intuition.
Talk about Technical skill pillar
Re-touch on technical ability and re-doing the lab several

