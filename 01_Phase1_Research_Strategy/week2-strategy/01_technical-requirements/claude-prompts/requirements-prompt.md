# Claude Prompt: Technical Requirements Generator

## Purpose
This prompt transforms stakeholder synthesis insights into comprehensive technical requirements for government digital transformation projects. Generates detailed, implementable specifications that guide Phase 2 design and Phase 3 development while ensuring government compliance.

## How to Use
1. **Complete stakeholder synthesis first** using the Cross-Stakeholder Synthesizer
2. **Copy the prompt below** into a new Claude conversation
3. **Paste the synthesis document** as input
4. **Review technical requirements** for completeness and accuracy
5. **Validate with technical stakeholders** before proceeding to IA design
6. **Use output to guide** information architecture and user journey development

---

## THE CLAUDE PROMPT
**Copy everything from this line down to the end of the code block into Claude:**

```
You are generating comprehensive technical requirements for a government digital transformation project using the CivicSpeed methodology. Transform stakeholder synthesis insights into detailed, implementable technical specifications that ensure government compliance and support citizen-centered service delivery.

**PROJECT CONTEXT:**
- Agency: [AGENCY_NAME]
- Project: [PROJECT_NAME]
- Phase: Week 2 Technical Requirements Development
- Methodology: CivicSpeed AI-Accelerated Government Digital Transformation
- Timeline: 26-week implementation (Phase 1: Weeks 1-2, Phase 2: Weeks 3-8, Phase 3: Weeks 9-24, Phase 4: Weeks 25-26)

**STAKEHOLDER SYNTHESIS INPUT:**
[PASTE COMPLETE STAKEHOLDER SYNTHESIS DOCUMENT HERE]

**TECHNICAL REQUIREMENTS FRAMEWORK:**
Generate requirements across 8 critical domains for government digital projects:

## REQUIREMENTS METHODOLOGY

### 1. GOVERNMENT COMPLIANCE FIRST
**Regulatory Requirements:**
- Extract all compliance standards mentioned in synthesis
- Map each requirement to specific technical implementations
- Identify compliance validation checkpoints

**Accessibility Standards:**
- Section 508 compliance minimum (WCAG 2.1 AA)
- Government-specific accessibility requirements
- Multi-modal access considerations

**Security Framework:**
- Government security standards (NIST, FedRAMP considerations)
- Data protection and privacy requirements
- Public transparency requirements

### 2. CITIZEN-CENTERED ARCHITECTURE
**User Experience Requirements:**
- Performance standards for citizen-facing services
- Multi-device and multi-channel support
- Language and cultural accessibility

**Service Delivery Standards:**
- Availability and uptime requirements
- Response time standards for different service types
- Error handling and user guidance requirements

### 3. TECHNICAL INTEGRATION
**Legacy System Integration:**
- Existing system interfaces and APIs
- Data migration and synchronization requirements
- Approval workflow integrations

**Modern Architecture:**
- Scalability and performance requirements
- Cloud infrastructure considerations
- Development framework standards

**OUTPUT FORMAT:**
Present technical requirements using this exact structure:

## EXECUTIVE SUMMARY
**Technical Scope:** [High-level description of technical solution]
**Architecture Approach:** [Modern web application/Legacy integration/Hybrid approach]
**Compliance Level:** [Federal/State/Local compliance requirements]
**Implementation Complexity:** [Low/Medium/High complexity with rationale]
**Estimated Technical Effort:** [Development weeks estimate based on requirements]

## FUNCTIONAL REQUIREMENTS

### Core User Functions
**Citizen Services:**
1. **[Service Function 1]**
   - **Description:** [What citizens can do]
   - **User Groups:** [Who can access this function]
   - **Business Rules:** [Constraints and validation rules]
   - **Success Criteria:** [How to measure successful implementation]
   - **Priority:** [High/Medium/Low based on stakeholder synthesis]

2. **[Service Function 2]**
   - **Description:** [What citizens can do]
   - **User Groups:** [Who can access this function]
   - **Business Rules:** [Constraints and validation rules]
   - **Success Criteria:** [How to measure successful implementation]
   - **Priority:** [High/Medium/Low based on stakeholder synthesis]

**Staff Functions:**
1. **[Staff Function 1]**
   - **Description:** [What staff can do]
   - **User Roles:** [Which staff roles have access]
   - **Workflow Integration:** [How this connects to existing processes]
   - **Efficiency Gain:** [Expected improvement in staff productivity]
   - **Priority:** [High/Medium/Low based on stakeholder synthesis]

**Administrative Functions:**
1. **[Admin Function 1]**
   - **Description:** [Administrative capabilities]
   - **Access Control:** [Who can perform administrative tasks]
   - **Audit Requirements:** [What must be logged and tracked]
   - **Compliance Impact:** [How this supports regulatory compliance]

### Data Management Requirements
**Data Collection:**
- **[Data Type 1]**: [Collection method, validation rules, storage requirements]
- **[Data Type 2]**: [Collection method, validation rules, storage requirements]
- **[Data Type 3]**: [Collection method, validation rules, storage requirements]

**Data Processing:**
- **Validation Rules:** [How data is validated before acceptance]
- **Business Logic:** [How data is processed and transformed]
- **Calculation Requirements:** [Any automated calculations or derivations]

**Data Storage:**
- **Retention Policies:** [How long different data types are kept]
- **Backup Requirements:** [Backup frequency and recovery time objectives]
- **Archive Processes:** [Long-term storage and retrieval requirements]

## TECHNICAL ARCHITECTURE REQUIREMENTS

### System Architecture
**Architecture Pattern:** [Microservices/Monolithic/Hybrid approach based on synthesis]
- **Rationale:** [Why this approach best serves stakeholder needs]
- **Scalability Plan:** [How system will handle growth]
- **Maintainability:** [How architecture supports long-term maintenance]

**Technology Stack:**
- **Frontend Framework:** [React/Next.js/etc. with government considerations]
- **Backend Framework:** [Node.js/Python/etc. with integration requirements]
- **Database Technology:** [PostgreSQL/etc. with performance and compliance needs]
- **Hosting Environment:** [Cloud/On-premise/Hybrid based on agency requirements]

### Integration Requirements
**Required Integrations:** (Based on synthesis findings)
1. **[System 1 Name]**
   - **Integration Type:** [API/Database/File transfer]
   - **Data Exchange:** [What data flows in each direction]
   - **Frequency:** [Real-time/Batch/On-demand]
   - **Authentication:** [How systems authenticate with each other]
   - **Error Handling:** [How integration failures are managed]
   - **Stakeholder Impact:** [Which stakeholders depend on this integration]

2. **[System 2 Name]**
   - **Integration Type:** [API/Database/File transfer]
   - **Data Exchange:** [What data flows in each direction]
   - **Frequency:** [Real-time/Batch/On-demand]
   - **Authentication:** [How systems authenticate with each other]
   - **Error Handling:** [How integration failures are managed]
   - **Stakeholder Impact:** [Which stakeholders depend on this integration]

**Integration Standards:**
- **API Design:** [RESTful/GraphQL standards for government systems]
- **Data Formats:** [JSON/XML standards with schema validation]
- **Error Handling:** [Standardized error responses and logging]

### Performance Requirements
**Response Time Standards:**
- **Page Load Time:** [Maximum acceptable load time for citizen-facing pages]
- **API Response Time:** [Maximum response time for API calls]
- **Search Performance:** [Maximum time for search results to appear]
- **File Upload/Download:** [Maximum time for file operations]

**Capacity Requirements:**
- **Concurrent Users:** [Maximum number of simultaneous users]
- **Transaction Volume:** [Peak transactions per minute/hour/day]
- **Data Volume:** [Expected data storage growth over 5 years]
- **Bandwidth Requirements:** [Network capacity needed for peak usage]

**Availability Standards:**
- **Uptime Requirement:** [99.9%/99.99% availability target]
- **Maintenance Windows:** [Acceptable downtime for updates and maintenance]
- **Disaster Recovery:** [Maximum acceptable downtime for major incidents]
- **Geographic Distribution:** [Multi-region requirements if applicable]

## SECURITY & COMPLIANCE REQUIREMENTS

### Security Standards
**Authentication & Authorization:**
- **User Authentication:** [Multi-factor authentication requirements]
- **Role-Based Access:** [How different user types are authorized]
- **Session Management:** [Session timeout and security requirements]
- **Password Policy:** [Government-compliant password requirements]

**Data Security:**
- **Encryption Standards:** [Data encryption at rest and in transit]
- **Data Classification:** [How different data types are classified and protected]
- **Access Logging:** [What user actions must be logged and monitored]
- **Data Loss Prevention:** [Controls to prevent unauthorized data access]

**Infrastructure Security:**
- **Network Security:** [Firewall and network segmentation requirements]
- **Server Security:** [Operating system and application security standards]
- **Monitoring:** [Security monitoring and incident response requirements]
- **Vulnerability Management:** [How security vulnerabilities are identified and addressed]

### Compliance Requirements
**Regulatory Compliance:** (Based on synthesis findings)
1. **[Compliance Standard 1]** (e.g., Section 508, NIST, etc.)
   - **Requirement Details:** [Specific compliance requirements]
   - **Implementation Approach:** [How compliance will be achieved]
   - **Validation Method:** [How compliance will be verified]
   - **Documentation Required:** [What documentation must be maintained]

2. **[Compliance Standard 2]**
   - **Requirement Details:** [Specific compliance requirements]
   - **Implementation Approach:** [How compliance will be achieved]
   - **Validation Method:** [How compliance will be verified]
   - **Documentation Required:** [What documentation must be maintained]

**Audit Requirements:**
- **Audit Logging:** [What actions must be logged for audit purposes]
- **Retention Periods:** [How long audit logs must be retained]
- **Access Controls:** [Who can access audit information]
- **Reporting Requirements:** [What audit reports must be generated]

### Accessibility Requirements
**WCAG 2.1 AA Compliance:**
- **Visual Accessibility:** [Requirements for users with visual impairments]
- **Motor Accessibility:** [Requirements for users with motor impairments]
- **Cognitive Accessibility:** [Requirements for users with cognitive impairments]
- **Technical Implementation:** [Specific technical approaches to achieve accessibility]

**Multi-Language Support:**
- **Primary Languages:** [Languages that must be supported]
- **Translation Requirements:** [How content translation will be managed]
- **Cultural Considerations:** [Cultural adaptations beyond language]

## INFRASTRUCTURE REQUIREMENTS

### Hosting Environment
**Deployment Architecture:**
- **Environment Strategy:** [Development/Staging/Production environment requirements]
- **Hosting Approach:** [Cloud/On-premise/Hybrid based on agency needs]
- **Geographic Requirements:** [Data residency and performance requirements]
- **Backup and Recovery:** [Backup strategy and recovery time objectives]

**Scalability Planning:**
- **Initial Capacity:** [Starting infrastructure capacity]
- **Growth Projections:** [Expected growth over 3-5 years]
- **Auto-scaling Requirements:** [How system will handle traffic spikes]
- **Performance Monitoring:** [How system performance will be monitored]

### Development Environment
**Development Standards:**
- **Code Quality:** [Code review and quality standards]
- **Testing Requirements:** [Unit testing, integration testing, user testing requirements]
- **Deployment Process:** [CI/CD pipeline requirements]
- **Documentation Standards:** [What technical documentation must be maintained]

**Version Control:**
- **Source Control:** [Git repository structure and access controls]
- **Release Management:** [How software releases are managed and deployed]
- **Change Management:** [How code changes are approved and tracked]

## OPERATIONAL REQUIREMENTS

### Monitoring & Maintenance
**System Monitoring:**
- **Performance Monitoring:** [What system metrics must be monitored]
- **User Activity Monitoring:** [What user actions are tracked]
- **Error Monitoring:** [How system errors are detected and reported]
- **Alert Thresholds:** [When administrators should be notified of issues]

**Maintenance Procedures:**
- **Regular Maintenance:** [Scheduled maintenance tasks and frequency]
- **Update Procedures:** [How software and security updates are applied]
- **Backup Procedures:** [How data backups are performed and verified]
- **Disaster Recovery:** [Procedures for recovering from major system failures]

### Support Requirements
**User Support:**
- **Help Documentation:** [Online help and user guide requirements]
- **Training Materials:** [Staff training requirements and materials]
- **Support Channels:** [How users can get help (phone, email, chat)]
- **Issue Tracking:** [How user issues are tracked and resolved]

**Technical Support:**
- **Issue Resolution:** [Service level agreements for issue resolution]
- **Escalation Procedures:** [How serious issues are escalated]
- **Knowledge Base:** [Technical documentation for support staff]

## QUALITY ASSURANCE REQUIREMENTS

### Testing Standards
**Functional Testing:**
- **Unit Testing:** [Code-level testing requirements]
- **Integration Testing:** [System integration testing requirements]
- **User Acceptance Testing:** [How stakeholder approval will be obtained]
- **Performance Testing:** [Load testing and stress testing requirements]

**Security Testing:**
- **Vulnerability Testing:** [Security vulnerability scanning requirements]
- **Penetration Testing:** [External security testing requirements]
- **Compliance Testing:** [How compliance requirements will be validated]

### Quality Metrics
**Success Criteria:** (Based on stakeholder synthesis)
- **User Satisfaction:** [Target satisfaction scores from stakeholder groups]
- **Performance Metrics:** [Specific performance targets]
- **Reliability Metrics:** [System uptime and error rate targets]
- **Security Metrics:** [Security incident targets and response times]

## IMPLEMENTATION ROADMAP

### Phase 2: Design & Prototyping (Weeks 3-8)
**Technical Setup Requirements:**
- **Week 3:** [Development environment setup requirements]
- **Week 4:** [Design system and component library requirements]
- **Weeks 5-6:** [Core service implementation requirements]
- **Weeks 7-8:** [Integration and testing requirements]

**Design Validation:**
- **Stakeholder Reviews:** [How technical designs will be validated]
- **Compliance Verification:** [How compliance will be verified during design]
- **Performance Validation:** [How performance requirements will be tested]

### Phase 3: Development & Integration (Weeks 9-24)
**Development Priorities:** (Based on stakeholder synthesis)
1. **[Priority 1 Feature]**: [Implementation details and timeline]
2. **[Priority 2 Feature]**: [Implementation details and timeline]
3. **[Priority 3 Feature]**: [Implementation details and timeline]

**Integration Schedule:**
- **Internal Systems:** [Timeline for integrating with existing government systems]
- **External Systems:** [Timeline for any external integrations]
- **Testing Milestones:** [Key testing and validation checkpoints]

### Risk Management
**Technical Risks:**
1. **[Risk 1]**: [Description, probability, impact, mitigation strategy]
2. **[Risk 2]**: [Description, probability, impact, mitigation strategy]
3. **[Risk 3]**: [Description, probability, impact, mitigation strategy]

**Compliance Risks:**
1. **[Risk 1]**: [Description, compliance impact, mitigation approach]
2. **[Risk 2]**: [Description, compliance impact, mitigation approach]

## STAKEHOLDER VALIDATION

### Technical Stakeholder Approval
**Review Process:**
- **Technical Review:** [How technical stakeholders will review and approve]
- **Security Review:** [Security stakeholder approval process]
- **Compliance Review:** [Compliance stakeholder approval process]

**Approval Criteria:**
- [ ] All functional requirements address stakeholder synthesis priorities
- [ ] Technical architecture supports identified user needs
- [ ] Security requirements meet all compliance standards
- [ ] Performance requirements support expected user volume
- [ ] Integration requirements address all identified systems
- [ ] Implementation roadmap aligns with project timeline
- [ ] Quality assurance approach ensures stakeholder satisfaction

### Documentation Requirements
**Technical Documentation:**
- **Architecture Documentation:** [Detailed technical architecture documents]
- **API Documentation:** [Interface documentation for integrations]
- **Security Documentation:** [Security architecture and procedures]
- **Compliance Documentation:** [Evidence of compliance requirement coverage]

## SUCCESS VALIDATION

### Requirements Quality Checklist
- [ ] All stakeholder synthesis priorities translated to technical requirements
- [ ] All compliance requirements identified and addressed
- [ ] Technical architecture supports 5-year scalability needs
- [ ] Security requirements meet government standards
- [ ] Performance requirements support citizen service delivery
- [ ] Integration requirements address all identified systems
- [ ] Implementation approach is realistic and achievable
- [ ] Quality assurance approach ensures project success
- [ ] Risk management addresses all identified concerns
- [ ] Stakeholder approval process is clearly defined

### Phase 1 Completion Standards
- [ ] Technical requirements comprehensive and stakeholder-approved
- [ ] Ready for information architecture development
- [ ] Ready for user journey mapping
- [ ] All government compliance requirements integrated
- [ ] Implementation roadmap validated with technical stakeholders

**REQUIREMENTS CONFIDENCE LEVEL:** [High/Medium/Low]
**READINESS FOR IA DESIGN:** [Ready/Needs Work/Blocked]
**CRITICAL DEPENDENCIES:** [Any external dependencies that could affect implementation]
```

**REQUIREMENTS GENERATION INSTRUCTIONS:**
1. Translate every stakeholder priority from synthesis into specific technical requirements
2. Ensure all government compliance standards are addressed with implementation details
3. Balance stakeholder needs with technical feasibility and budget constraints
4. Provide specific, measurable requirements that developers can implement
5. Include validation criteria for each requirement to ensure stakeholder satisfaction
6. Address the full 26-week project lifecycle with appropriate detail levels
7. Focus on citizen service delivery while meeting government operational needs

---

## Usage Notes

### Before Requirements Generation
- **Confirm stakeholder synthesis is complete** and validated
- **Review agency-specific compliance requirements** that may not be in synthesis
- **Identify any technical constraints** not captured in stakeholder interviews
- **Confirm project timeline and budget parameters**

### During Requirements Generation
- **Be specific and measurable** - vague requirements lead to scope creep
- **Balance stakeholder priorities** - not every stakeholder request can be highest priority
- **Consider implementation complexity** - requirements must be achievable within timeline
- **Validate compliance coverage** - missing compliance requirements cause project delays

### After Requirements Generation
- **Technical stakeholder review required** before proceeding to IA design
- **Security stakeholder approval needed** for security and compliance requirements
- **Executive approval required** for scope and timeline implications
- **Document any assumptions** that need validation during design phase

### Quality Standards
- **Government compliance focus** ensures all regulatory requirements addressed
- **Stakeholder priority alignment** maintains 95% satisfaction standard
- **Technical implementability** ensures Phase 3 development success
- **Scalability consideration** supports long-term agency needs

---

## File Naming Convention
Save requirements as: `Technical-Requirements-[ProjectName]-[Date].md`

Example: `Technical-Requirements-Denver-Parks-Portal-2024-03-22.md`
