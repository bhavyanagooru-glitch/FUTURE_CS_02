# FUTURE_CS_02
Phishing Email Detection and Awareness System – Future Interns Task 2
Future Interns – Cyber Security Internship | Task 2

Project Name: Phishing Email Detection & Awareness System
Intern: Bhavya Nagooru
Domain: Cyber Security
Project Type: Email Security Analysis and Awareness

1. Project Overview

This project focuses on identifying and analyzing phishing emails using sample email data. It demonstrates how attackers use fake notifications, suspicious links, malicious attachments, and sender impersonation to trick users.

The project includes email header analysis, link and attachment inspection, phishing indicator identification, risk classification, and employee awareness guidelines.

2. Project Objectives

- Collect and study phishing email samples.
- Analyze email headers and authentication results.
- Identify suspicious sender domains and email links.
- Inspect suspicious attachments.
- Identify common phishing indicators.
- Classify emails as Safe, Suspicious, or Phishing.
- Create security awareness and prevention guidelines.

3. Tools and Resources Used

- Google Admin Toolbox – Message Header Analyzer
- MXToolbox – Email Header Analyzer
- Web browser
- Notepad
- GitHub
- Public educational phishing email samples

4. Email Samples Analyzed

Sample 1 – Fake Fax Notification

- Type: Fake Fax Notification
- Sender: attack@attacker.example.com
- Subject: Monday, March 7 2022
- Suspicious link text: Print & Preview Here
- Observation: Unexpected fax notification and suspicious preview link.
- Risk Classification: HIGH – PHISHING

Sample 2 – Fake Voicemail Notification

- Type: Fake Voicemail Notification
- Sender: noreply@target.example.com
- Subject: Voice Message Notification
- SPF: FAIL
- DKIM: NONE
- DMARC: FAIL
- Observation: Unexpected HTML attachment and suspicious sign-in page shown in the sample evidence.
- Risk Classification: HIGH – PHISHING

Note: The domains and IP addresses in these training samples are anonymized/example values.

5. Common Phishing Indicators

- Unknown or suspicious sender address.
- Unexpected email notifications.
- Suspicious links and redirects.
- HTML attachments pretending to be audio or documents.
- SPF and DMARC authentication failures.
- Requests to enter passwords or personal information.
- Inconsistent branding and unusual email content.

6. Risk Classification

Category| Meaning
Safe| No significant suspicious indicators found
Suspicious| One or more warning signs need verification
Phishing| Strong indicators of fraudulent activity

Both analyzed samples were classified as High Risk – Phishing for educational purposes.

7. Prevention and Awareness Guidelines

Do's

- Verify the sender's email address.
- Check links before opening them.
- Verify unexpected notifications through official channels.
- Report suspicious emails to the IT/Security team.
- Use Multi-Factor Authentication (MFA).
- Keep systems and security software updated.

Don'ts

- Do not click unknown links.
- Do not open unexpected attachments.
- Do not share passwords or OTPs.
- Do not trust emails only because they contain company logos.
- Do not enter credentials on suspicious websites.

8. Project Methodology

1. Collected educational phishing email samples.
2. Reviewed email content and sender details.
3. Examined available email header information.
4. Checked suspicious links and attachments as text/evidence.
5. Identified phishing indicators.
6. Classified the risk level.
7. Prepared analysis documentation and awareness guidelines.

9. Project Deliverables

- Sample phishing email files.
- Email header analysis documents.
- Link and attachment analysis documents.
- Fake Fax and Voicemail screenshots.
- Phishing Email Analysis Report (PDF).
- Employee Phishing Awareness guidelines.

10. Safety and Scope

This project was performed for educational purposes using public training samples.

No real users were targeted. No credentials were collected, no live phishing links were opened, and no suspicious attachment was executed.

11. References

- Public educational samples: https://github.com/autinerd/phishing-mail-examples
- Google Admin Toolbox: https://toolbox.googleapps.com/apps/messageheader/
- MXToolbox: https://mxtoolbox.com/EmailHeaders.aspx

The public sample repository is used as an educational reference and is not owned by the project author. Sample identifiers may be anonymized.

12. Conclusion

This project helped demonstrate how phishing emails can be identified through sender verification, header analysis, link inspection, and suspicious attachment detection.

It also highlights the importance of employee awareness and safe email-handling practices in protecting organizations against phishing attacks.

Project completed as part of the Future Interns Cyber Security Internship – Task 2.
