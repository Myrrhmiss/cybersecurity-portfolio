# Activity Exemplar: Apply OS hardening techniques

## Section 1: Identify the network protocol involved in the incident

The protocol presented in this activity is the Hypertext transfer protocol (HTTP). The issue was related to accessing the web server for yummyrecipesforme.com; Requests to web servers for web pages involve http traffic. In the activity we ran tcpdump and accessed the yummyrecipesforme.com website the corresponding tcpdump log file showed the usage of the http protocol and the malicious file was noted to being transported to the users’ computers using the HTTP protocol at the application layer.

## Section 2: Document the incident

Customers contacted the helpdesk stating that when they visited the website, they were directed to download and run a file that contained access to new recipes, and since then their computers have been operating slow. The owner of the website tried logging into the server but noticed they were locked out of their account.

The analyst used a sandbox enter the website without impacting the company network. Then ran tcpdump to capture the network traffic packets produced by interacting with the website. Later, the analyst was prompted to download a file stating it would provide access to free recipes. The analyst accepted the download, ran it, and was redirected to a fake website (greatrecipesforme.com). 

The analyst inspected the tcpdump log noticing the browser requested the IP address for the yummyrecipesforme.com website. The connection with the website was established using the HTTP protocol. Then, the analyst recalled downloading and executing the file. The logs presented a great change in network traffic as the browser requested a new IP address for the greatrecipesforme.com URL. Lasly, the network traffic was then rerouted to the new IP address for the greatrecipesforme.com website. 

The senior cybersecurity professional analyzed the source code for the websites and the downloaded file. The analyst discovered that an attacker had manipulated the website to add code that prompted the users to download a malicious file disguised as a browser update. It was deduced that since the team had been locked out of their administrator account, the team believes the attacker used a brute force attack to access the account and change the admin password. The execution of the malicious file compromised the end users’ computers. 


##Section 3: Recommend one or more remediations for brute force attacks

The team plans to implemented a security method to disallow previous passwords from being used. The attacker’s ability to use a default password to log in s part of the vulnerabilities, it’s important that we prevent any old passwords such as default passwords from being used to reset the password. It’s imperative to require frequent password updates, so in case any unauthorized person becomes aware of the password, and implement two-factor authentication (2FA). 2FA requires authentication via a password and confirming a one-time passcode (OTP) sent to either their email or phone. When the user confirms their identity through their login credentials and the OTP, they will access to the system. Any malicious actor that attempts a brute force attack will require additional authentication and the access will be restricted. 



