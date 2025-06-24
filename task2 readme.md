Phishing Email Analysis – Task 2
Objective:
To identify phishing characteristics in a suspicious email sample.
Sample Email:

Subject:Urgent! Your Account Has Been Suspended  
From:support@amaz0n-verification.com  
To:user@example.com  

Body:
>Dear Customer,  
> Your Amazon account has been suspended due to suspicious activity.  
> Please verify your account immediately by clicking the link below:  
> [Verify Now](http://amaz0n-security-check.com/login)  
> Failure to do so will result in permanent suspension of your account.  
> Sincerely,  
> Amazon Security Team  

Attachment: Amazon_Security_Form.exe
Phishing Indicators:
1.Spoofed Email Address: 
support@amaz0n-verification.com is not an official Amazon domain.

2.Suspicious Link:  
   - Hovering shows it leads to: `http://amaz0n-security-check.com/login`
   - Misspelling ("amaz0n" instead of "amazon")

3.Urgent Language:  
   - "Your account has been suspended", "Verify immediately", "permanent suspension"

4.Dangerous Attachment: 
   - `.exe` file can install malware

5.Grammar/Spelling Errors:  
   - Slightly robotic and unnatural language

Conclusion:
This email uses multiple phishing tactics including a spoofed domain, urgency, fake links, and a malware attachment. 
It is a "clear phishing attempt and should be reported or deleted immediately. 
Files Included:
- `README.md` – This report
- `email_sample.txt` – Raw phishing email
- (Optional)Screenshot of header analysis or link hover
