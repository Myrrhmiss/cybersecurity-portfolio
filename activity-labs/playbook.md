# Activity: Use a playbook to respond to a phishing incident

## Ticket ID

A-2703

## Alert Message

SERVER-MAIL Phishing attempt possible download of malware

## Severity

Medium

## Details

The user may have opened a malicious email and opened attachments or clicked links.

## Ticket status

Escalated

## Ticket comments

An alert detected that an employee downloaded and opened a malicious file from a phishing email. There is an inconsistency between the sender’s email address “76tguy6hh6tgftrt7tg.su’” the name used in the email body “Clyde West,” and the sender’s name, “Def Communications.” There were grammatical errors in the email body and subject line. The email’s body also had a password-protected attachment, “bfsvc.exe,” which was downloaded and opened by the employee on the affected machine. After investigating the file hash, its malicious file has confirmed. The alert severity is reported as medium. Therefore, I escalate this ticket to a level-two SOC analyst to take further action.

## Additional information

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
