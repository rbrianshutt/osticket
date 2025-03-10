<h1>osTicket</h1>

![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/osticket-logo1.png)


<h2>Description</h2>
A hands-on lab designed for IT professionals to practice help desk ticketing workflows using osTicket. This lab covers ticket creation, property assignment, SLA management, department structuring, and access control.
<br />

<h2>Techonologies Used</h2>

- <b>Microsoft Azure</b> 
- <b>Remote Desktop</b>
- <b>OsTicket</b>

<h2>Operating Systems</h2>

- <b>Windows 10 </b> 

<h2>Dependencies</h2>

- <b>PHP Manager for IIS (PHPManagerForIIS_V1.5.0.msi)</b> 
- <b>Rewrite Module (rewrite_amd64_en-US.msi)</b>
- <b>PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip)</b> 
- <b>VC_redist.x86.exe</b>
- <b>MySQL 5.5.62 (mysql-5.5.62-win32.msi)</b> 
- <b>HeidiSQL</b>

<h2>Program walk-through:</h2>

- [osTicket Configuration and Set up for Virtual Environment](https://github.com/rbrianshutt/osticket_configuration) 

<h3>Login Pages</h3>

Admin/Analyst Login Page: http://localhost/osTicket/scp/login.php  <br/>

![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/3%20osTicket%20login.PNG)
<br />
<br />
End Users osTicket URL: http://localhost/osTicket <br/>

![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/3.1.support%20center.PNG)
<br />

<h2>Assign a new ticket</h2>

Click Open a New Ticket (seen above) <br/>
As an end-user, create the following ticket: "entire mobile/online banking system is down" <br/>
 
![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/13.1%20create%20ticket.PNG)
![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/13.2ticket%20created.PNG)
<br />
<br />
Sign in as john  <br/>

![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/13.3john%20login.PNG)
<br/>
<br/>
View the current tickets <br/>

![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/13.4%20tickets.PNG)
<br/>
<br/>
As a Help Desk Agent (john), observe the ticket’s properties <br/>

- <b>Priority</b> 
- <b>Department</b>
- <b>SLA</b>
- <b>Assigned To</b>

![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/13.5observe%20ticket%20properties.PNG)
<br />
<br />
Set Properties to the ticket<br/>
- <b>Click Default SLA Plan(pictured above)</b> 
- <b>Select Severity A (1 hour, 24/7)</b>
- <b>Online Banking Department</b>

Click Update <br/>

![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/13.6update%20sla.PNG)
<br />
<br />
Update Help Topic  <br/>
"Customers not able to access online banking" <br/>
Click Update <br/>

![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/13.7update%20help%20topic.PNG)
<br />
<br />
"View the log of documentation" <br/>

![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/13.8view%20log%20of%20documentation.PNG)
<br />
<br />
Assign to the team Online Banking <br/>
Click Assign<br/>

![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/13.9assign%20to%20a%20team.PNG)
<br />

<h2>Assign a new ticket</h2>

As an end-user, create the following ticket: "accounting department needs adobe upgrade, broken" <br/>

![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/14.1create%20ticket.PNG)
<br />
<br />
As a Help Desk Agent (john), observe the ticket’s properties <br/>

- <b>Priority</b> 
- <b>Department</b>
- <b>SLA</b>
- <b>Assigned To</b>

![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/14.2view%20ticket%20as%20john.PNG)
<br />
<br />
Set Properties to the ticket <br/>

- <b>Severity C (4 hours, 24/7)</b> 
- <b>Support</b>

Click Update <br/>

![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/14.3update%20sla.PNG)
<br />
<br />
Update the ticket  <br/>
"Customer will restart.  Will follow up with customer"  <br/>
Click Update <br/>

![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/14.4update%20ticket.PNG)
<br />
<br />
Update ticket again  <br/>
"Restart fixed issue.  Closing out ticket" <br/>
Click Update <br/>

![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/14.5update%20ticket%20again.PNG)
<br/>
<br/>
To resolve ticket, hover over current status (Open) <br/>
Click Resolved <br/>

![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/14.6resolve%20ticket.PNG)

<br />
<br />
Set status to Resolved  <br/>
Click Close  <br/>

![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/14.7close%20ticket.PNG)
<br />

<h2>Assign a new ticket</h2>

As an end-user, create the following ticket: "CFO’s laptop will no longer turn on" <br/>

![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/15.1create%20ticket.PNG)
![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/15.2view%20ticket.PNG)
<br />
<br />
As a Help Desk Agent (john), observe the ticket’s properties <br/>

- <b>Priority</b> 
- <b>Department</b>
- <b>SLA</b>
- <b>Assigned To</b>

![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/15.3view%20ticket%20properties.PNG)
<br />
<br />
Set Properties to the ticket  <br/>

- <b>Severity B (4 hours, 24/7)</b> 
- <b>Support</b>

![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/15.4sla.PNG)
<br />
<br />
Update Priority Level to Emergency  <br/>

![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/15.5priority.PNG)
<br />
<br />
Update the ticket  <br/>
"Laptop not charging due to broken charger. Replaced broken charger with new charger.  Charging succesfully." <br/>

![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/15.7update%20ticket.PNG)
<br />
<br />
To resolve ticket, hover over current status (Open) <br/>
Click Resolved <br/>

![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/15.8resolve%20ticket.PNG)
<br />
<br />
Set status to Resolved <br/>
"Charger was broken and battery ran out of power. New charger resolved issue." <br/>
Click Close <br/>

![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/15.9close%20ticket.PNG)
<br />
<br />
See there are no more tickets remaining <br/>

![](https://github.com/rbrianshutt/osticket/blob/main/osTicket/15.10%20no%20tickets.PNG)
<br />
<br />




