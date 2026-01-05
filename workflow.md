1. Open OWASP ZAP on Kali : Search for zap on the application in kali
   - Applications → Web Application Analysis → OWASP ZAP

         zap
     <img width="268" height="230" alt="load owasp zap" src="https://github.com/user-attachments/assets/dd8c8916-c079-458c-ba8e-f452c6f74fa1" />

2. Load the Vulnerable Website
   - Open OWASP ZAP
     
     <img width="704" height="387" alt="start zap" src="https://github.com/user-attachments/assets/668c9d53-d9fc-4727-934c-4da2267f3011" />

   - Open the vulnerable website
     <img width="834" height="407" alt="launch dvwa(vulnerable app)" src="https://github.com/user-attachments/assets/2cb420c8-bfa3-4747-8678-aa3f5413cc9e" />

   - Click Automated Scan
   - Paste the target URL (Note:DVWA website was used "http://172.17.0.2/dvwa/")

          http://172.17.0.2/dvwa/index.php)
     
     <img width="672" height="461" alt="vulnerablilites" src="https://github.com/user-attachments/assets/8a2127ea-6046-4896-a3b0-dbd171d0fe94" />

   - Click attack
   
ZAP will:
- Spider the site
- Actively scan for vulnerabilities
- Generate alerts automatically

3. Understanding ZAP Alert Colors

   <img width="601" height="188" alt="zap alerts" src="https://github.com/user-attachments/assets/b0c9540e-e94c-4197-a6b2-88a69635d778" />

## Lessons Learned
- Automated scanners quickly reveal common web flaws
- Not all alerts are exploitable (false positives exist)
- Manual verification is still required
- Security headers significantly reduce attack surface
