# Redynox Cyber Security Internship Report

**Intern:** Bithin Krishna Radhakrishnan
**LinkedIn:** linkedin.com/in/bkr95
**Report date:** October 12, 2026

## Files

`Redynox_Internship_Report.pdf`


## What the current report covers

The report follows the Redynox template: Introduction, Task Overview (Task 1 and Task 2, each with objective, tools and methods, steps taken, challenges and solutions, and results), Conclusion, and Closing Remarks.

| Task | Topic | Evidence used |
|------|-------|---------------|
| 1 | Network security basics: threat research, Wi-Fi (WPA2-PSK) and Windows Defender Firewall settings, Wireshark traffic capture | Wi-Fi settings, firewall screenshots, Wireshark capture |
| 2 | Web application security using WebGoat, OWASP ZAP, and Burp Suite: SQL injection, reflected XSS, and CSRF | WebGoat and ZAP/Burp screenshots |

## Items to confirm before submitting

- **CSRF result:** Your notes say the Referer change to `attacker.com` returned the flag. The ZAP screenshot shows it was rejected (flag `null`). The flag 36040 came from a request sent from a separate host through Burp. The report follows the screenshots. If you have a screenshot showing success with the Referer change, send it and the report can be updated.
- **XSS evidence:** The `XSS-Test` payload from your notes only appears in a Microsoft editor response, not WebGoat. The report uses the WebGoat credit-card-field screenshot. If your test was in the comment field, capture it.
- **SQL injection page 3:** The `UPDATE ... Tobi` step from your notes has no screenshot, so it is not in the report.
- **Task 1 IP address:** The unencrypted request to `185.200.125.154` (`/connecttest.txt`) has not been checked. Look up its owner before submitting.
- **Challenges and reflections:** The challenges are written from the screenshots. Add any difficulties you actually had. The Conclusion and Closing Remarks are drafts to be reworded in your own voice.
- **Table of contents:** In Word, right-click it and choose "Update Field."
- **Task 3:** Needs LinkedIn screenshots (follow Redynox, share an internship post, mention Redynox in a cyber security post).
