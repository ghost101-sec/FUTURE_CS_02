# FUTURE_CS_02: Phishing Email Detection & Awareness System

**Internship:** Future Interns, Cyber Security Track
**Task:** 2, Phishing Email Detection & Awareness System
**Author: EDWIN BAIJU

## Overview
This project analyzes phishing emails, classifies them as Safe, Suspicious or Phishing, explains common phishing techniques in simple business language, and provides prevention guidelines for users.

## What's Inside
- `Phishing_Detection_and_Awareness_Report.pdf`: the full report
- `safe_email_headers.png`: screenshot of SPF, DKIM and DMARC authentication results

## Summary of Findings
| Verdict | Emails |
|---|---|
| Phishing | 3 |
| Suspicious | 2 |
| Safe | 2 |

## Method
1. Created 6 simulated emails covering common phishing styles, plus 1 real email checked using its authentication results
2. Checked sender address, lookalike domains, urgency, mismatched links, attachments and requests for sensitive data
3. Verified SPF, DKIM and DMARC results using Gmail's "Show original"
4. Classified each email and documented the reasons

## Key Phishing Indicators
- Spoofed sender or lookalike domain
- Urgent or threatening language
- Mismatched or shortened links
- Unexpected attachments
- Requests for passwords, OTPs or bank details

## Tools Used
Gmail header analysis (SPF, DKIM, DMARC), browser tools, Google Docs

## Note
Emails 1-6 are simulated for educational purposes. All links are defanged ([.] and hxxp) and no malicious links or attachments were opened. Personal details have been removed from screenshots.

## Key Learning
Decisions should combine several signs (sender, links, language and authentication results), because an unfamiliar domain alone does not always mean phishing.
