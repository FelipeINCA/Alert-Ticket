# Alert Ticket
<body>
  <a>Ticket ID
Alert Message
Severity
Details
Ticket status
A-2703
SERVER-MAIL Phishing attempt possible download of malware
Medium
The user may have opened a malicious email and opened attachments or clicked links.
 Escalated



Ticket comments 
According to a deep analysis, this alert has to be escalated because the mail contains a malicious attachment file with a famous malware. This alert could turn into a serious threat if it isn’t escalated correctly. The content of the e-mail has grammar errors which means there is a possible phishing threat. With these findings, I chose to escalate this ticket to a level-two SOC analyst to take further action. 


Additional information
Known malicious file hash: 54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b

Email:
From: Def Communications <76tguyhh6tgftrt7tg.su>  <114.114.114.114>
Sent: Wednesday, July 20, 2022 09:30:14 AM
To: <hr@inergy.com> <176.157.125.93>
Subject: Re: Infrastructure Egnieer role

Dear HR at Ingergy,

I am writing for to express my interest in the engineer role posted from the website.

There is attached my resume and cover letter. For privacy, the file is password protected. Use the password paradise10789 to open. 

Thank you,

Clyde West
Attachment: filename="bfsvc.exe"

INCIDENT FINAL REPORT
Executive summary
The organization experienced a security incident on December 28, 2022, at 7:20 p.m., PT, during which an individual was able to gain unauthorized access to customer personal identifiable information (PII) and financial information. Approximately 50,000 customer records were affected. The financial impact of the incident is estimated to be $100,000 in direct costs and potential loss of revenue. The incident is now closed and a thorough investigation has been conducted.
Timeline
At approximately 3:13 p.m., PT, on December 22, 2022, an employee received an email from an external email address. The email sender claimed that they had successfully stolen customer data. In exchange for not releasing the data to public forums, the sender requested a $25,000 cryptocurrency payment. The employee assumed the email was spam and deleted it.
On December 28, 2022, the same employee received another email from the same sender. This email included a sample of the stolen customer data and an increased payment demand of $50,000. 
On the same day, the employee notified the security team, who began their investigation into the incident. Between December 28 and December 31, 2022, the security team concentrated on determining how the data was stolen and the extent of the theft.
Investigation
The security team received the alert and traveled on-site to begin the investigation. 
The root cause of the incident was identified as a vulnerability in the e-commerce web application. This vulnerability allowed the attacker to perform a forced browsing attack and access customer transaction data by modifying the order number included in the URL string of a purchase confirmation page. This vulnerability allowed the attacker to access customer purchase confirmation pages, exposing customer data, which the attacker then collected and exfiltrated.
After confirming the web application vulnerability, the security team analyzed the web application access logs. The logs indicated that the attacker accessed the information of thousands of purchase confirmation pages.
Response and remediation
The organization collaborated with the public relations department to disclose the data breach to its customers. Additionally, the organization offered free identity protection services to customers affected by the incident. 
After the security team reviewed the associated web server logs, the cause of the attack was very clear. There was a single log source showing an exceptionally high volume of sequentially listed customer orders.
Recommendations
To prevent future recurrences, we are taking the following actions:
Perform routine vulnerability scans and penetration testing.
Implement the following access control mechanisms:
Implement allowlisting to allow access to a specified set of URLs and automatically block all requests outside of this URL range.
Ensure that only authenticated users are authorized access to content.



</a>
</body>
