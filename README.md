# What are we working on?
An imaginary company: Freshbite cloud kitchen (online based food delivery company)
Key Assets: Custome payment data(crown jewel), delivery app, suppliers contracts
Customer touchpoints- website, mobile app, customer support
## What can go wrong?
1.Spoofing - Fake delivery drivers logs into system.
2.Tampering - Attackers modify orders or delivery address.
3.Info disclosure- Customer data leak.
4.Elevation of privilege - Attacker gains admin access.

Risks ( prioritized)
1.Customer data breach- high monetary+ trust loss
2.DoS attacks on website - stops revenue flow
3.Insider tampering with payroll or suppliers contracts 
### What are we gong to do about it?
REDUCE
.Strong authentication for customers and drivers.
.Encrypt all sensitive data.
.Web Application Firewall(WAF)+ DDoS protection.
ELIMINATE
.Remove unnecessary admin account.
TRANSFER
.Use trusted third-party payment processor.
.Cyber insurance for data breaches.
ACCEPT
.Minor orders- handled via customer service
#### Did we do the enough job?
.Continuous monitoring of logs.
.Threat modeling update Quarterly or after major system changes.
.Routine inspections and controls.
.Treat security system as an ongoing process.

Source
Braitmen et al.2020: The Threat Modeling Manifesto
Shostack 2022: The World's Shortest Threat Modeling Course
Karvinen 2024: Information Security Course
OWASP 2021: Threat Modeling Cheat Sheet

