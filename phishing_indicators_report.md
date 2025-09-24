# Phishing Indicators Report

| Indicator Type         | Example Found                             | Why It's Suspicious                                      |
|------------------------|-------------------------------------------|----------------------------------------------------------|
| Spoofed Email Address  | security@hdfcbank-alerts.com              | Not an official HDFC domain                              |
| Header Discrepancy     | SPF fail, foreign IP                      | Sender not authorized, likely spoofed                    |
| Suspicious Link        | http://hdfc-verification.ru/login         | `.ru` domain, not associated with HDFC                   |
| Threatening Language   | “Verify immediately to avoid suspension”  | Creates urgency, typical of phishing                     |
| Generic Greeting       | No name or account reference              | Legitimate banks personalize emails                      |
| Grammar/Style Issues   | Generic phrasing, no branding             | Lacks professionalism and authenticity                   |

Summary: This email is a textbook phishing attempt using spoofed identity, urgency, and a malicious link.
