# PASTA worksheet

I. Define business and security objectives

Make 2-3 notes of specific business requirements that will be analyzed.

●	Users can create member profiles internally or by connecting external accounts.

●	The app must process financial transactions.

●	The app should be in compliance with PCI-DSS.

II. Define the technical scope

List of technologies used by the application:

●	Application programming interface (API)

●	Public key infrastructure (PKI)

●	SHA-256

●	SQL

APIs facilitate the exchange of data between customers, partners, and employees, so they should be prioritized. They handle a lot of sensitive data while they connect various users and systems together. However, details such as which APIs are being used should be considered before prioritizing one technology over another. So, they can be more prone to security vulnerabilities because there’s a larger attack surface.

III. Decompose application

![Pasta Image 1](../images/pasta-evidence1.png)

IV. Threat analysis

List 2 types of threats in the PASTA worksheet that are risks to the information being handled by the application.

●	Injection

●	Session hijacking

V. Vulnerability analysis

List 2 vulnerabilities in the PASTA worksheet that could be exploited.

●	Lack of prepared statements

●	Broken API token

VI. Attack modeling

![Pasta Image 2](../images/pasta-evidence2.png)

VII. Risk analysis and impact

List 4 security controls that can reduce risk.
SHA-256, incident response procedures, password policy, principle of least privilege



