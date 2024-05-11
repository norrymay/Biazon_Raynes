
### **Ethical Hacking Technical Report**  
**Client: PhilHealth**  
**Date: May 10, 2024**  
**Prepared by: Biazon, Norry May R. and Raynes, Cristel S.**  

  **Executive Summary:** This report presents the technical findings of the ethical hacking assessment conducted for PhilHealth. The assessment aimed to identify vulnerabilities within the organization's network infrastructure, applications, and systems. Through various testing methodologies, including penetration testing and vulnerability scanning, critical and high-risk issues were discovered. This report provides detailed descriptions of these findings, along with actionable recommendations for remediation. 

**Vulnerability Summary:**

**1. Data Security:**
-  Critical: Data Encryption and Data Access Controls of PhilHealth, encrypted member data. Weaknesses in access controls may have allowed unauthorized access to member data.

**2. Web Applications**
-  Critical: SQL Injection vulnerability on the Online platform of PhilHealth like member portals could be exploited to access or manipulate the sensitive data stored in their database.

-  High: Cross-Site Scripting (XSS) vulnerability in PhilHealth web application, allowing attackers to execute malicious scripts in users' browsers that can potentially compromised their accounts or steal their sensitive information.

**3. Network Infrastructure:**
-  Critical: PhilHealth’s lacking of cyber protection software like antivirus. Network infrastructure may have servers or systems running vulnerable software. Such as web applications or internal portals. These vulnerabilities may allow the attackers to gain unauthorized access to sensitive data on PhilHealth’s server.

-  High: Lacking of firewall configurations could lead to the exposing PhilHealth internal service, like employee portals or database servers to unauthorized access from external sources.

**4. Outdated and Unpatched Operating Systems:**
-  Critical: Outdated and unpatched operating systems on critical servers PhilHealth or internal systems might be running outdated operating system potential for malicious exploits and malware attacks.

-  High:  Weak password policies on domain user accounts could make it easier to attackers to brute force credentials and gain unauthorized access to their system. 

**5. Wireless Networks**
-  Critical: Using weak encryption standards such as WEP could allow attackers to intercept and decrypt sensitive data transmitted over these networks by PhilHealth, which uses wireless networks in its infrastructure.

**6.	Data Protection:**
-	Critical: PhilHealth is collecting and storing a large amount of sensitive personal and medical data about its members. Unauthorized access, data breaches and privacy infringements could result from insufficient data protection measures in the form of poor encryption or improper access controls.
  
**7.	Physical Security Weaknesses:**
-	Critical: The physical premises of PhilHealth, including data centers, offices and storage facilities, may be vulnerable to risks such as inadequate access controls, lack of surveillance or the risk of unauthorized entry. Physical security breaches may result in theft, sabotage or unauthorized access to sensitive equipment and information.
  
**8.	Social Engineering:** 
-	High: Several employees have been victims of Phishing attacks, where hackers are trying to get them to reveal confidential information such as login details that could compromise the security of an organization.

**Recommendation:**

**1.	Network Infrastructure:**
-	Immediately implement comprehensive antivirus, antimalware, and endpoint protection software for all PhilHealth systems. 
-	To reduce the risk of exposure to outside threats, firewall configurations should be regularly reviewed and updated to restrict access to internal services from authorized sources, ports and IP address only.
  
**2.	Web Applications:**
-	Conduct a thorough code review and implement input validation to prevent SQL Injection and XSS attacks to PhilHealth’s online platforms to identify and remediate SQL injection vulnerabilities and SQL injection attacks.
-	To reduce XSS vulnerabilities in PhilHealth's web applications, correct input validation and output encoding needs to be implemented. To reduce the impact of XSS attacks, use the Content Security Policy HTTP headers.
  
**3.	Data Security:**
-	Strengthen the data encryption to protect both member data in transit and at rest and enhance the access control to ensure that only authorized access personnel can access the sensitive data and in order to detect and respond to unauthorized access attempts, access logs are regularly audited.
  
**4.	Operating Systems:** 
-	Develop a patch management process to regularly update and secure operating systems on critical servers and internal systems against known vulnerabilities. Prioritize security updates to mitigate the risk of exploitation by malicious attacks.
-	Enforce strong password policies regular password changes, account lockout and consider implementing multi-factor authentication for domain user accounts.
  
**5.	Wireless Networks:** 
-	Upgrade wireless network encryption to WPA2 or WPA3 to ensure confidentiality and integrity of wireless communications. To reduce the risk of unauthorized access, introduce strong authentication mechanisms and regularly rotate passwords for wireless networks.

**6.	Data Protection:**
-	Conduct a review of data access controls and implement strong encryption for all sensitive member data, stored on servers and traveling over networks. To minimize the potential for unauthorized access and misuse of data.

**7.	Physical Security Weaknesses:**
-	Enhance the physical access control with measures such as biometric authentication and surveillance cameras. And also conduct a regular security audit and physical assessment to identify and address vulnerabilities.

**8.	Social Engineering:** 
-	Conduct regular security awareness training for employees to educate them about the risks of phishing attacks and how to identify and report suspicious emails. And also implements email filtering and anti phishing measures before it reaches the employees inbox.


**Conclusion:** The findings of the ethical hacking assessment highlight several critical vulnerabilities and security weaknesses within PhilHealth’s infrastructure and applications. These vulnerabilities exposed to significant risk, includes unauthorized access, data breaches, privacy infringements and potential disruption of critical services. By implementing the recommended remediation measures, PhilHealth can significantly enhance its security posture and mitigate the risk of cyber threats and data breaches. Emphasizing the implementation of robust cyber security measures. These recommendations include the implementing of antivirus, software protection updating and reviewing the firewall configurations, strengthening data encryption and access controls and also conducting a security awareness training for employees. It can significantly enhance and mitigate the impact of the potential security threats and attacks.

**Signature:**  Norry May R. Biazon/Cristel S. Raynes
