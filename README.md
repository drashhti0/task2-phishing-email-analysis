# Task 2: Phishing Email Analysis

## Introduction
Phishing is a cyber attack technique where attackers impersonate trusted organizations to trick users into revealing sensitive information such as login credentials, banking details, or personal data. In this task, a suspicious email pretending to be from PayPal was analyzed to identify common phishing characteristics.

## Email Sample
From: "PayPal Support" <security@paypal-update.com>  
To: user@example.com  
Subject: Urgent: Verify Your Account Immediately  

Body:  
Dear Customer,  
We have detected suspicious activity in your PayPal account. To restore access, please verify your account immediately using the link below:  
https://paypal.com.verify-account-security-update.com/login  

Failure to verify within 24 hours will result in account suspension.  

Thank you,  
PayPal Security Team  

## Analysis

### Sender Email Address
The sender email address is security@paypal-update.com. This is not an official PayPal domain. Legitimate PayPal emails come from domains like @paypal.com. This indicates email spoofing.

### Subject Line
The subject contains words like "Urgent" and "Immediately" which are used to create panic and pressure the user into acting quickly. This is a common social engineering tactic.

### Greeting
The email uses a generic greeting "Dear Customer" instead of addressing the user by name. Legitimate companies usually personalize emails, so this is a red flag.

### Email Content
The email claims there is suspicious activity in the account and threatens suspension within 24 hours. This creates fear and urgency, encouraging the user to click the link without thinking.

### Link Analysis
The link provided is:
https://paypal.com.verify-account-security-update.com/login  

Although it appears to contain "paypal.com", the actual domain is "verify-account-security-update.com", which is malicious. This is a common phishing trick.

### URL Mismatch
The presence of "paypal.com" in the URL is misleading. The real domain is different, indicating URL spoofing. Users should always check the main domain carefully.

### Grammar and Style
The email appears mostly correct but lacks personalization and uses a templated tone. Phishing emails often follow this pattern.

## Phishing Indicators Identified
- Fake sender domain (paypal-update.com)  
- Use of urgent and threatening language  
- Generic greeting (Dear Customer)  
- Suspicious and misleading URL  
- Fear tactics (account suspension warning)  
- URL spoofing  

## Conclusion
This email is a phishing attempt designed to trick users into entering their credentials on a fake website. It uses multiple social engineering techniques to appear legitimate and create urgency.

## Awareness and Prevention
Users should always verify the sender's email address, avoid clicking on suspicious links, and manually visit official websites. It is also recommended to enable two-factor authentication for additional security.

## Project Contents
- Phishing email sample  
- Analysis document (PDF)  
- README.md  

## Outcome
This task helped in understanding how phishing attacks work, how to identify them, and how to prevent falling victim to such attacks.
