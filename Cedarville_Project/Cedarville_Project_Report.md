# Cedarville Family Health – Cybersecurity & GRC Assessment Report

Commentary:

This is a capstone project I did as part of my GRC and Data Privacy badge. I wanted to share the report to showcase what I have learned.

Also attached is the final presentation for the project:

[Cedarville_GRC_Presentation.pptx](https://github.com/user-attachments/files/27755283/Cedarville_GRC_Presentation.pptx)



## 1. Executive Summary

This report provides a comprehensive Governance, Risk, and Compliance (GRC) assessment of Cedarville Family Health. The objective is to evaluate the organization’s cybersecurity posture, identify risks, and assess compliance with the HIPAA Security Rule.

The assessment identified critical gaps in encryption, risk management, and backup security practices. While the organization demonstrates strong intent through policies and training, the absence of effective technical and operational controls creates significant exposure to data breaches, regulatory penalties, and reputational damage.

---

## 2. Background and Context

Cedarville Family Health is a small healthcare clinic serving its community for over 40 years. Originally operating fully on paper-based processes, the clinic has partially transitioned to electronic records without implementing modern cybersecurity safeguards.

The clinic operates using a single computer system, manual patient data entry, and portable storage for backups. Although policies exist, their implementation is inconsistent and lacks technical reinforcement.

> **Commentary:** This reflects a common scenario in small organizations where operational efficiency is prioritized over cybersecurity, leading to high-risk environments.

---

## 3. Cybersecurity Risk Analysis

Key vulnerabilities include:
- Lack of encryption  
- Insecure backup handling  
- Unrestricted access to patient records  

These weaknesses expose sensitive patient information to unauthorized access and compromise the confidentiality, integrity, and availability (CIA) of data.

> **Commentary:** Encryption absence is the most critical issue as it directly violates HIPAA safeguards.

---

## 4. HIPAA Compliance Evaluation

The clinic is not compliant with several HIPAA Security Rule requirements, particularly in:
- Technical safeguards  
- Risk management processes  

However, it demonstrates compliance in:
- Workforce training  
- Policy establishment  

> **Commentary:** There is a clear gap between policy definition and technical implementation.

---

## 5. Governance and Risk Management

Governance structures such as training and policies are in place, but the clinic lacks:
- Formal risk analysis procedures  
- Continuous assessment mechanisms  

> **Commentary:** Risk management is effectively absent, making other controls less effective.

---

## 6. Risk Treatment Strategy

### Immediate priorities:
- Phishing attacks  
- Unauthorized access  
- Insecure backups  

### Medium-term priorities:
- Password management improvements  
- Network security enhancements  

---

## 7. Backup Strategy

A secure backup strategy is recommended based on the **3-2-1 rule**:
- 3 copies of data  
- 2 different storage types  
- 1 offsite backup  

Using **daily differential backups**, stored both locally and in the cloud.

> **Commentary:** This eliminates single points of failure and aligns with industry standards.

---

## 8. Encryption Strategy

Recommended encryption methods:

- **Full-disk encryption** → for systems  
- **Asymmetric encryption** → for communications  
- **Symmetric encryption** → for backups  

These measures ensure compliance and protect sensitive patient data.

> **Commentary:** Correct selection of encryption types demonstrates improved understanding of data protection principles.

---

## 9. Conclusion

Cedarville Family Health is currently not fully compliant with HIPAA but has strong potential to improve through implementation of recommended controls.

Immediate focus should be placed on:
- Encryption  
- Secure backup practices  
- Formal risk management  
