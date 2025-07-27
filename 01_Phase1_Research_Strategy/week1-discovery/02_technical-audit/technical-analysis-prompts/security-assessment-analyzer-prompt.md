# Technical Analysis Prompt: Security Assessment Analyzer

## Purpose
This prompt analyzes security audit data, vulnerability scans, and compliance assessments to identify security requirements, regulatory gaps, and risk mitigation strategies for government digital transformation projects.

## How to Use
1. **Complete security assessment** using security scanners, penetration testing, and compliance tools
2. **Copy the prompt below** into a new Claude conversation
3. **Paste security scan results and findings** as input
4. **Review security analysis** for accuracy and completeness
5. **Use results to inform** technical requirements and compliance planning

---

## THE CLAUDE PROMPT
**Copy everything from this line down to the end of the code block into Claude:**

```
You are analyzing comprehensive security assessment data for a government digital transformation project using the CivicSpeed methodology. Extract security insights that will inform technical requirements, identify compliance gaps, and establish security frameworks that meet government standards.

**PROJECT CONTEXT:**
- Agency: [AGENCY_NAME]
- System/Website: [SYSTEM_URL_OR_NAME]
- Assessment Date: [ASSESSMENT_DATE]
- Government Level: [Federal/State/Local]
- Methodology: CivicSpeed AI-Accelerated Government Digital Transformation

**SECURITY ASSESSMENT INPUT:**
[PASTE SECURITY SCAN RESULTS HERE]
[PASTE VULNERABILITY ASSESSMENT DATA HERE]
[PASTE COMPLIANCE AUDIT FINDINGS HERE]
[PASTE PENETRATION TEST RESULTS HERE]
[PASTE SECURITY HEADERS ANALYSIS HERE]

**SECURITY ANALYSIS FRAMEWORK:**
Analyze security data across 7 critical dimensions for government system security:

## ANALYSIS METHODOLOGY

### 1. GOVERNMENT SECURITY COMPLIANCE
**Federal Standards Assessment:**
- NIST Cybersecurity Framework compliance evaluation
- FedRAMP requirements assessment (if applicable)
- FISMA compliance gap analysis
- OMB policy adherence evaluation

**State/Local Compliance:**
- State cybersecurity standards compliance
- Local government security policy adherence
- Industry-specific regulations (healthcare, finance, etc.)
- Cross-jurisdictional data sharing requirements

### 2. VULNERABILITY ASSESSMENT
**Critical Vulnerability Identification:**
- High-severity security vulnerabilities
- Public-facing system exposures
- Data protection weaknesses
- Authentication and authorization flaws

**Risk Prioritization:**
- CVSS scoring and risk classification
- Government data sensitivity impact
- Public service delivery risk assessment
- Compliance violation potential

### 3. DATA PROTECTION & PRIVACY
**Sensitive Data Handling:**
- PII (Personally Identifiable Information) protection
- Government data classification compliance
- Citizen data privacy requirements
- Cross-system data sharing security

**Privacy Compliance:**
- State privacy law compliance (CCPA, state-specific regulations)
- Government transparency vs. privacy balance
- Citizen consent and data rights management
- Data retention and disposal requirements

**OUTPUT FORMAT:**
Present security analysis using this exact structure:

## EXECUTIVE SUMMARY
**Overall Security Posture:** [Excellent/Good/Fair/Poor with risk level assessment]
**Compliance Status:** [Compliant/Partially Compliant/Non-Compliant with government standards]
**Critical Vulnerabilities:** [Number of high/critical severity issues identified]
**Regulatory Risk Level:** [High/Medium/Low risk of compliance violations]
**Immediate Action Required:** [Yes/No - any critical security issues requiring urgent attention]

## VULNERABILITY ANALYSIS

### Critical Security Issues
**High-Severity Vulnerabilities:** (CVSS 7.0+)
1. **[Vulnerability Type 1]** (e.g., SQL Injection, XSS, etc.)
   - **Severity Score:** [CVSS score and classification]
   - **Location/Scope:** [Where vulnerability exists and extent]
   - **Potential Impact:** [Data breach, service disruption, compliance violation]
   - **Government Risk:** [Specific risk to government operations and citizen data]
   - **Remediation Complexity:** [Simple/Moderate/Complex fix required]
   - **Timeline for Fix:** [Immediate/Short-term/Long-term remediation]

2. **[Vulnerability Type 2]**
   - **Severity Score:** [CVSS score and classification]
   - **Location/Scope:** [Where vulnerability exists and extent]
   - **Potential Impact:** [Data breach, service disruption, compliance violation]
   - **Government Risk:** [Specific risk to government operations and citizen data]
   - **Remediation Complexity:** [Simple/Moderate/Complex fix required]
   - **Timeline for Fix:** [Immediate/Short-term/Long-term remediation]

### Medium-Risk Vulnerabilities
**Moderate Security Concerns:** (CVSS 4.0-6.9)
- **[Issue 1]**: [Description, impact, and remediation approach]
- **[Issue 2]**: [Description, impact, and remediation approach]
- **[Issue 3]**: [Description, impact, and remediation approach]

### System Configuration Issues
**Security Hardening Gaps:**
- **Server Configuration:** [Security misconfigurations identified]
- **Application Security:** [Application-level security weaknesses]
- **Network Security:** [Network configuration and firewall issues]
- **Access Controls:** [User access and permission problems]

## GOVERNMENT COMPLIANCE ANALYSIS

### NIST Cybersecurity Framework Assessment
**Framework Compliance Status:**
- **Identify:** [Asset management and risk assessment compliance]
- **Protect:** [Access controls and data security compliance]
- **Detect:** [Security monitoring and detection capability]
- **Respond:** [Incident response planning and capability]
- **Recover:** [Recovery planning and resilience capability]

**Compliance Gaps:**
1. **[NIST Function/Category]**: [Specific gap and remediation needed]
2. **[NIST Function/Category]**: [Specific gap and remediation needed]
3. **[NIST Function/Category]**: [Specific gap and remediation needed]

### Federal/State Compliance Assessment
**FedRAMP Compliance:** (If applicable)
- **Authorization Status:** [Current authorization level or gaps]
- **Security Controls:** [Controls implemented vs. required]
- **Continuous Monitoring:** [Ongoing security monitoring capability]
- **Documentation Requirements:** [Security documentation completeness]

**State/Local Requirements:**
- **[State/Local Standard 1]**: [Compliance status and gaps]
- **[State/Local Standard 2]**: [Compliance status and gaps]
- **[Data Protection Laws]**: [Privacy law compliance assessment]

### Industry-Specific Compliance
**Sector-Specific Requirements:**
- **[Regulation 1]** (e.g., HIPAA for health data): [Compliance status]
- **[Regulation 2]** (e.g., PCI DSS for payments): [Compliance status]
- **[Regulation 3]** (e.g., FERPA for education): [Compliance status]

## DATA PROTECTION ANALYSIS

### Sensitive Data Assessment
**Government Data Classification:**
- **Public Data:** [How public information is protected and managed]
- **Internal Use Data:** [Protection of internal government operations data]
- **Confidential Data:** [Protection of sensitive government information]
- **Restricted Data:** [Highest level security for classified/sensitive data]

**Citizen Data Protection:**
- **PII Handling:** [How personally identifiable information is protected]
- **Data Collection Practices:** [What citizen data is collected and why]
- **Data Storage Security:** [How citizen data is stored and protected]
- **Data Sharing Controls:** [How citizen data is shared between systems/agencies]

### Privacy Compliance Assessment
**Privacy Framework Compliance:**
- **Data Minimization:** [Collection limited to necessary information]
- **Purpose Limitation:** [Data used only for stated purposes]
- **Consent Management:** [How citizen consent is obtained and managed]
- **Data Rights:** [Citizen rights to access, correct, delete data]

**Privacy Policy Assessment:**
- **Policy Completeness:** [Coverage of all required privacy disclosures]
- **Plain Language Compliance:** [Citizen understanding of privacy practices]
- **Legal Compliance:** [Adherence to applicable privacy laws]
- **Update Requirements:** [How privacy policies are maintained current]

## AUTHENTICATION & ACCESS CONTROL ANALYSIS

### User Authentication Assessment
**Current Authentication Methods:**
- **Citizen Authentication:** [How citizens verify identity to access services]
- **Staff Authentication:** [How government employees access systems]
- **Multi-Factor Authentication:** [MFA implementation status and gaps]
- **Single Sign-On:** [SSO implementation and integration]

**Authentication Security:**
- **Password Policies:** [Current password requirements and enforcement]
- **Account Lockout:** [Brute force protection mechanisms]
- **Session Management:** [Session timeout and security controls]
- **Identity Verification:** [How identity is verified for sensitive services]

### Authorization & Access Controls
**Role-Based Access Control:**
- **User Role Definition:** [How user roles and permissions are defined]
- **Least Privilege Implementation:** [Whether users have minimum necessary access]
- **Access Review Processes:** [How user access is reviewed and updated]
- **Segregation of Duties:** [How conflicting duties are separated]

**System Access Controls:**
- **Administrative Access:** [How system administration access is controlled]
- **Database Access:** [How database access is restricted and monitored]
- **Network Access:** [Network segmentation and access controls]
- **Physical Access:** [Physical security controls for systems and data]

## TECHNICAL SECURITY IMPLEMENTATION

### Encryption & Data Protection
**Data Encryption Assessment:**
- **Data at Rest:** [How stored data is encrypted and protected]
- **Data in Transit:** [How data transmission is secured]
- **Key Management:** [How encryption keys are managed and rotated]
- **Encryption Standards:** [Which encryption algorithms and standards used]

**SSL/TLS Implementation:**
- **Certificate Management:** [SSL certificate status and management]
- **Protocol Security:** [TLS version and configuration security]
- **Mixed Content Issues:** [HTTP/HTTPS content mixing problems]
- **Certificate Authority:** [CA trust and validation]

### Network Security Assessment
**Network Architecture Security:**
- **Firewall Configuration:** [Network firewall rules and effectiveness]
- **Network Segmentation:** [How networks are separated and isolated]
- **Intrusion Detection:** [Network monitoring and intrusion detection capability]
- **VPN Security:** [Remote access security implementation]

**Web Application Security:**
- **Security Headers:** [HTTP security headers implementation]
- **Input Validation:** [How user input is validated and sanitized]
- **Output Encoding:** [How output is encoded to prevent attacks]
- **Error Handling:** [How errors are handled without information disclosure]

## INCIDENT RESPONSE & MONITORING

### Security Monitoring Capability
**Current Monitoring Implementation:**
- **Log Management:** [What security events are logged and monitored]
- **SIEM Implementation:** [Security information and event management capability]
- **Alerting Systems:** [How security incidents trigger alerts]
- **Threat Intelligence:** [Use of threat intelligence feeds and analysis]

**Detection Capability:**
- **Intrusion Detection:** [Capability to detect unauthorized access]
- **Malware Detection:** [Anti-malware and endpoint protection]
- **Data Loss Prevention:** [DLP implementation and effectiveness]
- **Behavioral Analysis:** [User and entity behavior analytics]

### Incident Response Preparedness
**Incident Response Plan:**
- **Plan Completeness:** [Coverage of different incident types]
- **Response Team:** [Incident response team structure and training]
- **Communication Procedures:** [How incidents are communicated internally/externally]
- **Recovery Procedures:** [How systems and services are restored]

**Business Continuity:**
- **Backup Systems:** [Data backup and recovery capability]
- **Disaster Recovery:** [DR planning and testing]
- **Service Continuity:** [How critical services are maintained during incidents]
- **Vendor Support:** [External support for incident response]

## SECURITY REQUIREMENTS FOR NEW SYSTEM

### Technical Security Requirements
**Mandatory Security Controls:**
1. **Authentication Requirements:**
   - **Multi-Factor Authentication:** [Required for all user types]
   - **Identity Verification:** [Government-approved identity proofing]
   - **Session Management:** [Secure session handling requirements]

2. **Data Protection Requirements:**
   - **Encryption Standards:** [Required encryption for data at rest and in transit]
   - **Data Classification:** [How different data types must be handled]
   - **Access Controls:** [Role-based access control implementation]

3. **Infrastructure Security Requirements:**
   - **Network Security:** [Firewall, segmentation, monitoring requirements]
   - **Server Hardening:** [Security configuration standards]
   - **Vulnerability Management:** [Regular scanning and patching requirements]

### Compliance Requirements
**Government Standard Compliance:**
- **NIST Framework:** [Required NIST controls for new system]
- **Federal Requirements:** [FedRAMP or other federal security requirements]
- **State/Local Requirements:** [Applicable state and local security standards]
- **Audit Requirements:** [Security auditing and reporting requirements]

**Privacy and Data Protection:**
- **Privacy by Design:** [Privacy controls built into system architecture]
- **Data Governance:** [Data handling and lifecycle management]
- **Citizen Rights:** [Implementation of citizen data rights]
- **Transparency Requirements:** [Public disclosure of data practices]

## RISK ASSESSMENT & MITIGATION

### Security Risk Analysis
**High-Risk Areas:**
1. **[Risk Category 1]** (e.g., Data Breach Risk)
   - **Risk Description:** [Specific security risk and potential impact]
   - **Likelihood:** [High/Medium/Low probability of occurrence]
   - **Impact:** [Effect on government operations and citizen services]
   - **Current Controls:** [Existing security measures addressing this risk]
   - **Mitigation Strategy:** [Additional controls needed to reduce risk]

2. **[Risk Category 2]** (e.g., Compliance Violation Risk)
   - **Risk Description:** [Specific security risk and potential impact]
   - **Likelihood:** [High/Medium/Low probability of occurrence]
   - **Impact:** [Effect on government operations and citizen services]
   - **Current Controls:** [Existing security measures addressing this risk]
   - **Mitigation Strategy:** [Additional controls needed to reduce risk]

### Threat Assessment
**Government-Specific Threats:**
- **Nation-State Actors:** [APT threats targeting government systems]
- **Cybercriminals:** [Financial crime targeting government and citizens]
- **Hacktivists:** [Politically motivated attacks on government services]
- **Insider Threats:** [Risks from government employees and contractors]

**Attack Vector Analysis:**
- **Web Application Attacks:** [Risks to public-facing government websites]
- **Email/Phishing:** [Social engineering risks to government staff]
- **Supply Chain:** [Third-party vendor and contractor security risks]
- **Physical Security:** [Risks to government facilities and equipment]

## RECOMMENDATIONS

### Immediate Security Actions (Before Phase 2)
1. **[Critical Action 1]**: [Urgent security fix needed before design phase]
2. **[Critical Action 2]**: [Urgent security fix needed before design phase]
3. **[Critical Action 3]**: [Urgent security fix needed before design phase]

### Security Architecture for New System
**Core Security Requirements:**
- **Zero-Trust Architecture:** [Implementation approach for zero-trust security model]
- **Defense in Depth:** [Layered security controls throughout system]
- **Secure by Design:** [Security integrated into development process]
- **Continuous Monitoring:** [Ongoing security monitoring and assessment]

### Phase 3 Security Implementation Plan
**Security Development Priority:**
1. **[Security Priority 1]**: [Most critical security feature to implement first]
2. **[Security Priority 2]**: [Second priority security implementation]
3. **[Security Priority 3]**: [Third priority security implementation]

**Security Testing Requirements:**
- **Penetration Testing:** [Third-party security testing requirements]
- **Code Security Review:** [Secure code review and static analysis]
- **Vulnerability Assessment:** [Ongoing vulnerability scanning]
- **Compliance Testing:** [Validation of government compliance requirements]

## INTEGRATION WITH STAKEHOLDER ANALYSIS

### Validating Security Concerns
**Stakeholder Security Feedback:** [Do security findings support stakeholder concerns?]
**Compliance Awareness:** [Are stakeholders aware of all compliance requirements?]
**Risk Tolerance:** [Do stakeholder risk expectations align with actual risks?]
**Security Training Needs:** [What security training do stakeholders need?]

### Supporting Technical Requirements
**Security Constraints:** [Security limitations affecting new system design]
**Compliance Mandates:** [Non-negotiable security requirements for new system]
**Integration Security:** [Security requirements for system integrations]
**Operational Security:** [Security requirements for day-to-day operations]

## SECURITY VALIDATION

### Assessment Quality Checklist
- [ ] All critical systems and interfaces assessed
- [ ] Government compliance requirements thoroughly evaluated
- [ ] Vulnerability assessment complete with risk prioritization
- [ ] Data protection and privacy requirements identified
- [ ] Authentication and access controls evaluated
- [ ] Incident response capability assessed
- [ ] Security requirements for new system defined
- [ ] Risk assessment complete with mitigation strategies

### Analysis Confidence Level
**Vulnerability Assessment Confidence:** [High/Medium/Low]
**Compliance Analysis Confidence:** [High/Medium/Low]
**Risk Assessment Confidence:** [High/Medium/Low]
**Requirements Definition Confidence:** [High/Medium/Low]

**CRITICAL SECURITY BLOCKERS:** [Any security issues that could prevent project approval]
**IMMEDIATE SECURITY ACTIONS:** [Security fixes required before Phase 2 can begin]
```

**SECURITY ANALYSIS INSTRUCTIONS:**
1. Prioritize government compliance requirements - these are typically non-negotiable
2. Focus on protecting citizen data and government operations equally
3. Identify security requirements that must be built into new system architecture
4. Assess realistic risk levels based on government threat landscape
5. Provide specific, actionable security recommendations with implementation timelines
6. Connect security findings to business impact on citizen service delivery
7. Ensure analysis supports both compliance requirements and operational security needs

---

## Usage Notes

### Before Analysis
- **Coordinate with security team** before running any security scans
- **Obtain proper authorization** for vulnerability assessments and penetration testing
- **Document scan methodology** for compliance and audit purposes
- **Ensure comprehensive coverage** of all public-facing and internal systems

### During Analysis
- **Focus on government-specific threats** and compliance requirements
- **Assess citizen data protection** as highest priority
- **Evaluate operational security** impact on government services
- **Document all findings** with specific remediation approaches

### After Analysis
- **Coordinate with IT security** team to validate findings
- **Prioritize critical vulnerabilities** for immediate remediation
- **Integrate into technical requirements** development
- **Plan security architecture** for new system development

### Quality Standards
- **Government compliance focus** ensures regulatory requirements addressed
- **Citizen data protection priority** protects public trust and legal compliance
- **Operational security balance** maintains service delivery while ensuring security
- **Implementation feasibility** ensures security requirements are achievable

---

## File Naming Convention
Save analysis as: `Security-Assessment-Analysis-[ProjectName]-[Date].md`

Example: `Security-Assessment-Analysis-Denver-Parks-Portal-2024-03-16.md`
