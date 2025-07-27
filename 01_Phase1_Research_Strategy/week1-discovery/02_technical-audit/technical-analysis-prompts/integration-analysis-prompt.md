# Technical Analysis Prompt: Integration Analysis

## Purpose
This prompt analyzes current system integrations, API capabilities, and data flow requirements to identify integration constraints, opportunities, and technical requirements for government digital transformation projects.

## How to Use
1. **Complete integration discovery** through system documentation, API analysis, and stakeholder interviews
2. **Copy the prompt below** into a new Claude conversation
3. **Paste integration documentation and findings** as input
4. **Review integration analysis** for accuracy and completeness
5. **Use results to inform** technical requirements and architecture planning

---

## THE CLAUDE PROMPT
**Copy everything from this line down to the end of the code block into Claude:**

```
You are analyzing system integration requirements and capabilities for a government digital transformation project using the CivicSpeed methodology. Map current integrations, identify integration constraints, and define integration requirements that enable seamless government service delivery while maintaining security and compliance.

**PROJECT CONTEXT:**
- Agency: [AGENCY_NAME]
- Current Systems Environment: [BRIEF_DESCRIPTION]
- Integration Scope: [NEW_SYSTEM_INTEGRATION_REQUIREMENTS]
- Government Level: [Federal/State/Local]
- Methodology: CivicSpeed AI-Accelerated Government Digital Transformation

**INTEGRATION DISCOVERY INPUT:**
[PASTE CURRENT SYSTEM INVENTORY HERE]
[PASTE API DOCUMENTATION HERE]
[PASTE DATA FLOW DIAGRAMS HERE]
[PASTE VENDOR INTEGRATION SPECIFICATIONS HERE]
[PASTE STAKEHOLDER INTEGRATION REQUIREMENTS HERE]

**INTEGRATION ANALYSIS FRAMEWORK:**
Analyze integration data across 6 critical dimensions for government system connectivity:

## ANALYSIS METHODOLOGY

### 1. CURRENT INTEGRATION LANDSCAPE
**Existing System Inventory:**
- Document all current systems and their integration points
- Map data flows between existing systems
- Identify integration technologies and protocols currently used
- Assess integration maintenance and operational status

**Legacy System Assessment:**
- Evaluate legacy system integration capabilities
- Document technical constraints of older systems
- Assess modernization requirements for legacy integrations
- Identify systems requiring replacement vs. integration

### 2. GOVERNMENT DATA STANDARDS
**Data Format & Standards Compliance:**
- Government data exchange standards compliance
- Cross-agency data sharing requirements
- Federal/state data format mandates
- Industry-specific data standards adherence

**Interoperability Requirements:**
- Cross-jurisdictional data sharing needs
- Multi-agency coordination requirements
- Public-private partnership data exchanges
- Citizen data portability requirements

### 3. INTEGRATION SECURITY & COMPLIANCE
**Government Security Requirements:**
- Federal/state security standards for data exchange
- Authentication requirements for system integration
- Data protection during transmission and storage
- Audit and monitoring requirements for integrations

**Compliance Framework Integration:**
- Regulatory compliance through system integrations
- Automated compliance reporting capabilities
- Data governance and lineage tracking
- Privacy protection in cross-system data flows

**OUTPUT FORMAT:**
Present integration analysis using this exact structure:

## EXECUTIVE SUMMARY
**Integration Complexity:** [Simple/Moderate/Complex based on number and type of required integrations]
**Current Integration Health:** [Excellent/Good/Fair/Poor status of existing integrations]
**New System Integration Feasibility:** [High/Medium/Low feasibility for required integrations]
**Technical Risk Level:** [High/Medium/Low risk for integration-related project delays]
**Government Compliance Status:** [Compliant/Partially Compliant/Non-Compliant with government data standards]

## CURRENT INTEGRATION ENVIRONMENT

### Existing System Landscape
**Core Government Systems:**
1. **[System Name 1]** (e.g., Permit Management System)
   - **System Type:** [Database/Application/Service]
   - **Technology Platform:** [Technology stack and version]
   - **Integration Method:** [API/Database/File Transfer/Manual]
   - **Data Exchange Frequency:** [Real-time/Daily/Weekly/Monthly/As-needed]
   - **Integration Health:** [Stable/Issues/Failing]
   - **Business Criticality:** [High/Medium/Low impact on operations]

2. **[System Name 2]** (e.g., Financial Management System)
   - **System Type:** [Database/Application/Service]
   - **Technology Platform:** [Technology stack and version]
   - **Integration Method:** [API/Database/File Transfer/Manual]
   - **Data Exchange Frequency:** [Real-time/Daily/Weekly/Monthly/As-needed]
   - **Integration Health:** [Stable/Issues/Failing]
   - **Business Criticality:** [High/Medium/Low impact on operations]

3. **[System Name 3]** (e.g., Customer Relationship Management)
   - **System Type:** [Database/Application/Service]
   - **Technology Platform:** [Technology stack and version]
   - **Integration Method:** [API/Database/File Transfer/Manual]
   - **Data Exchange Frequency:** [Real-time/Daily/Weekly/Monthly/As-needed]
   - **Integration Health:** [Stable/Issues/Failing]
   - **Business Criticality:** [High/Medium/Low impact on operations]

### Current Data Flow Analysis
**Primary Data Flows:**
- **[Data Flow 1]**: [System A] → [System B] ([Data Type], [Frequency])
- **[Data Flow 2]**: [System B] → [System C] ([Data Type], [Frequency])
- **[Data Flow 3]**: [System C] → [External System] ([Data Type], [Frequency])

**Data Flow Issues:**
- **Manual Data Entry:** [Where manual processes create bottlenecks]
- **Data Synchronization Problems:** [Systems with data consistency issues]
- **Performance Bottlenecks:** [Slow or unreliable data transfers]
- **Error Handling Gaps:** [Where data transfer failures cause problems]

### Integration Technology Assessment
**Current Integration Technologies:**
- **API Standards:** [REST/SOAP/GraphQL usage and standards]
- **Data Formats:** [XML/JSON/CSV/Database direct]
- **Authentication Methods:** [OAuth/API Keys/Certificate-based]
- **Message Queuing:** [Message queue technologies if used]
- **File Transfer Methods:** [FTP/SFTP/Direct file sharing]

**Technology Constraints:**
- **Legacy Protocol Support:** [Older systems requiring specific protocols]
- **Security Requirements:** [Government-mandated security protocols]
- **Performance Limitations:** [Network or system capacity constraints]
- **Vendor Dependencies:** [Third-party system limitations]

## NEW SYSTEM INTEGRATION REQUIREMENTS

### Required Integrations for New System
**High-Priority Integrations:** (Must-have for system functionality)
1. **[Integration Name 1]** (e.g., Citizen Identity Verification)
   - **Target System:** [System to integrate with]
   - **Business Purpose:** [Why this integration is needed]
   - **Data Exchange:** [What data flows in each direction]
   - **Frequency Requirements:** [Real-time/Batch/On-demand]
   - **Technical Approach:** [Preferred integration method]
   - **Compliance Requirements:** [Government standards that apply]
   - **Success Criteria:** [How to measure integration success]

2. **[Integration Name 2]** (e.g., Payment Processing)
   - **Target System:** [System to integrate with]
   - **Business Purpose:** [Why this integration is needed]
   - **Data Exchange:** [What data flows in each direction]
   - **Frequency Requirements:** [Real-time/Batch/On-demand]
   - **Technical Approach:** [Preferred integration method]
   - **Compliance Requirements:** [Government standards that apply]
   - **Success Criteria:** [How to measure integration success]

**Medium-Priority Integrations:** (Important but not critical for launch)
- **[Integration 1]**: [Brief description and business justification]
- **[Integration 2]**: [Brief description and business justification]
- **[Integration 3]**: [Brief description and business justification]

**Future Integration Opportunities:** (Nice-to-have or future phase)
- **[Future Integration 1]**: [Potential benefit and timeline]
- **[Future Integration 2]**: [Potential benefit and timeline]

### Data Requirements Analysis
**Inbound Data Needs:** (Data the new system needs from other systems)
- **[Data Type 1]**: From [Source System] - [Business purpose and usage]
- **[Data Type 2]**: From [Source System] - [Business purpose and usage]
- **[Data Type 3]**: From [Source System] - [Business purpose and usage]

**Outbound Data Sharing:** (Data the new system will provide to other systems)
- **[Data Type 1]**: To [Target System] - [Business purpose and usage]
- **[Data Type 2]**: To [Target System] - [Business purpose and usage]
- **[Data Type 3]**: To [Target System] - [Business purpose and usage]

**Bidirectional Data Exchange:** (Systems requiring two-way data flow)
- **[System 1]**: [Data exchanged and synchronization requirements]
- **[System 2]**: [Data exchanged and synchronization requirements]

## TECHNICAL INTEGRATION CONSTRAINTS

### Legacy System Limitations
**Technical Constraints:**
1. **[Legacy System 1]** Constraints:
   - **Technology Limitations:** [Outdated protocols, limited API capabilities]
   - **Performance Constraints:** [Processing speed, data volume limitations]
   - **Security Limitations:** [Outdated security protocols, compliance gaps]
   - **Maintenance Issues:** [Vendor support, documentation gaps]
   - **Workaround Requirements:** [How to work with system limitations]

2. **[Legacy System 2]** Constraints:
   - **Technology Limitations:** [Outdated protocols, limited API capabilities]
   - **Performance Constraints:** [Processing speed, data volume limitations]
   - **Security Limitations:** [Outdated security protocols, compliance gaps]
   - **Maintenance Issues:** [Vendor support, documentation gaps]
   - **Workaround Requirements:** [How to work with system limitations]

### Infrastructure Constraints
**Network and Connectivity:**
- **Bandwidth Limitations:** [Network capacity constraints affecting integrations]
- **Latency Requirements:** [Real-time vs. batch processing needs]
- **Security Perimeter:** [Firewall and network security constraints]
- **Geographic Distribution:** [Multi-location integration challenges]

**Government IT Environment:**
- **Security Policies:** [Government security requirements limiting integration approaches]
- **Change Management:** [IT change control processes affecting integration timeline]
- **Vendor Restrictions:** [Approved vendor lists and procurement constraints]
- **Budget Constraints:** [Funding limitations affecting integration scope]

### Data Governance Constraints
**Data Quality Issues:**
- **Data Standardization:** [Inconsistent data formats across systems]
- **Data Validation:** [Data quality and accuracy problems]
- **Master Data Management:** [Lack of single source of truth for key data]
- **Data Lineage:** [Difficulty tracking data origin and transformations]

**Regulatory Constraints:**
- **Data Residency:** [Where government data must be stored and processed]
- **Data Sharing Restrictions:** [Legal limitations on data sharing]
- **Privacy Protection:** [Citizen data protection requirements]
- **Audit Requirements:** [Data tracking and reporting requirements]

## INTEGRATION ARCHITECTURE RECOMMENDATIONS

### Recommended Integration Approach
**Integration Architecture Pattern:**
- **API-First Design:** [RESTful API strategy for new integrations]
- **Event-Driven Architecture:** [Event streaming for real-time data sync]
- **Service Mesh:** [Microservices integration coordination]
- **Data Lake/Warehouse:** [Centralized data integration and analytics]

**Government-Specific Considerations:**
- **Security-First Integration:** [Zero-trust integration security model]
- **Compliance by Design:** [Built-in compliance checking and reporting]
- **Auditability:** [Complete integration logging and monitoring]
- **Resilience:** [Fault tolerance and disaster recovery]

### Technical Implementation Strategy
**Phase 1: Foundation Integrations** (Critical for system launch)
1. **[Integration 1]**: [Implementation approach and timeline]
2. **[Integration 2]**: [Implementation approach and timeline]
3. **[Integration 3]**: [Implementation approach and timeline]

**Phase 2: Enhancement Integrations** (Improve functionality)
1. **[Integration 1]**: [Implementation approach and timeline]
2. **[Integration 2]**: [Implementation approach and timeline]

**Phase 3: Advanced Integrations** (Future capabilities)
1. **[Integration 1]**: [Implementation approach and timeline]
2. **[Integration 2]**: [Implementation approach and timeline]

### Data Integration Strategy
**Master Data Management:**
- **Citizen/Entity IDs:** [Unified identification across systems]
- **Reference Data:** [Shared lookup tables and code lists]
- **Data Synchronization:** [Real-time vs. batch data sync strategy]
- **Conflict Resolution:** [How to handle data conflicts between systems]

**Data Quality Assurance:**
- **Validation Rules:** [Data quality checks during integration]
- **Error Handling:** [How to handle data integration errors]
- **Monitoring:** [Data quality monitoring and alerting]
- **Remediation:** [Process for fixing data quality issues]

## INTEGRATION SECURITY & COMPLIANCE

### Security Requirements for Integrations
**Authentication & Authorization:**
- **API Security:** [OAuth 2.0, API keys, certificate-based authentication]
- **Service-to-Service Auth:** [How systems authenticate with each other]
- **Role-Based Access:** [Granular permissions for data access]
- **Token Management:** [Secure token handling and renewal]

**Data Protection in Transit:**
- **Encryption Standards:** [TLS requirements for data transmission]
- **Message Security:** [Message-level encryption and signing]
- **VPN Requirements:** [Secure network connectivity requirements]
- **Certificate Management:** [SSL/TLS certificate management]

**Data Protection at Rest:**
- **Integration Data Storage:** [How integration data is stored securely]
- **Temporary Data Handling:** [Security for data during processing]
- **Backup Security:** [Encryption and protection of integration backups]
- **Key Management:** [Encryption key management for integration data]

### Compliance Requirements
**Government Data Standards:**
- **Data Format Standards:** [Required government data formats and schemas]
- **Metadata Requirements:** [Required data documentation and lineage]
- **Retention Policies:** [How long integration data must be retained]
- **Disposal Requirements:** [Secure data disposal procedures]

**Audit and Monitoring:**
- **Integration Logging:** [What integration activities must be logged]
- **Access Monitoring:** [Monitoring and alerting for data access]
- **Performance Monitoring:** [Integration performance tracking]
- **Compliance Reporting:** [Automated compliance report generation]

## INTEGRATION TESTING STRATEGY

### Testing Requirements
**Integration Testing Approach:**
- **Unit Testing:** [Testing individual integration components]
- **Integration Testing:** [Testing system-to-system connections]
- **End-to-End Testing:** [Testing complete business processes across systems]
- **Performance Testing:** [Load testing for integration endpoints]

**Test Environment Strategy:**
- **Development Testing:** [Safe testing environment for integration development]
- **Staging Environment:** [Production-like testing environment]
- **Production Testing:** [Limited production testing approach]
- **Rollback Planning:** [How to revert integration changes if issues occur]

**Data Testing Requirements:**
- **Data Validation Testing:** [Ensuring data accuracy across integrations]
- **Data Volume Testing:** [Testing with realistic data volumes]
- **Data Security Testing:** [Verifying data protection during integration]
- **Error Scenario Testing:** [Testing integration failure and recovery]

## RISK ASSESSMENT & MITIGATION

### Integration Risk Analysis
**High-Risk Integration Areas:**
1. **[Risk Area 1]** (e.g., Legacy System Integration Failure)
   - **Risk Description:** [Specific integration risk and potential impact]
   - **Likelihood:** [High/Medium/Low probability of occurrence]
   - **Impact:** [Effect on government operations and citizen services]
   - **Current Mitigation:** [Existing measures to reduce risk]
   - **Additional Mitigation:** [Recommended additional risk reduction measures]

2. **[Risk Area 2]** (e.g., Data Synchronization Problems)
   - **Risk Description:** [Specific integration risk and potential impact]
   - **Likelihood:** [High/Medium/Low probability of occurrence]
   - **Impact:** [Effect on government operations and citizen services]
   - **Current Mitigation:** [Existing measures to reduce risk]
   - **Additional Mitigation:** [Recommended additional risk reduction measures]

### Technical Risk Mitigation
**Integration Failure Mitigation:**
- **Fallback Procedures:** [Manual processes when integrations fail]
- **Circuit Breakers:** [Automatic failure detection and isolation]
- **Retry Logic:** [Intelligent retry mechanisms for failed operations]
- **Health Monitoring:** [Proactive monitoring of integration health]

**Data Risk Mitigation:**
- **Data Backup:** [Backup strategies for integration data]
- **Data Validation:** [Real-time data quality checking]
- **Error Recovery:** [Procedures for recovering from data errors]
- **Audit Trail:** [Complete tracking of data changes and access]

## VENDOR & THIRD-PARTY CONSIDERATIONS

### External System Dependencies
**Government Vendor Systems:**
- **[Vendor System 1]**: [Integration capabilities, SLA requirements, costs]
- **[Vendor System 2]**: [Integration capabilities, SLA requirements, costs]
- **[Vendor System 3]**: [Integration capabilities, SLA requirements, costs]

**Cloud Service Integrations:**
- **[Cloud Service 1]**: [Government compliance status, integration approach]
- **[Cloud Service 2]**: [Government compliance status, integration approach]

### Procurement and Compliance
**Vendor Management:**
- **Security Clearance:** [Vendor security clearance requirements]
- **Compliance Certification:** [Required vendor compliance certifications]
- **SLA Requirements:** [Service level agreements for integration services]
- **Contract Terms:** [Integration-specific contract requirements]

## IMPLEMENTATION ROADMAP

### Integration Development Timeline
**Phase 1: Foundation (Weeks 3-8)**
- **Week 3-4:** [Core integration infrastructure setup]
- **Week 5-6:** [Critical integration development]
- **Week 7-8:** [Integration testing and validation]

**Phase 2: Enhancement (Weeks 9-16)**
- **Weeks 9-12:** [Secondary integration development]
- **Weeks 13-16:** [Advanced integration features]

**Phase 3: Optimization (Weeks 17-24)**
- **Weeks 17-20:** [Performance optimization]
- **Weeks 21-24:** [Advanced features and monitoring]

### Success Metrics
**Integration Success Criteria:**
- [ ] All critical integrations functional and tested
- [ ] Data synchronization working correctly
- [ ] Security and compliance requirements met
- [ ] Performance requirements achieved
- [ ] Error handling and recovery tested
- [ ] Monitoring and alerting operational
- [ ] Documentation complete
- [ ] Staff training completed

**Performance Targets:**
- **Integration Response Time:** [Maximum acceptable response time]
- **Data Accuracy:** [Minimum data quality standards]
- **System Uptime:** [Required availability for integrations]
- **Error Rate:** [Maximum acceptable error rate]

## STAKEHOLDER INTEGRATION REQUIREMENTS

### Validating Integration Needs
**Stakeholder Requirements Validation:**
- **Executive Requirements:** [Strategic integration needs from executive stakeholders]
- **Operational Requirements:** [Day-to-day integration needs from operations staff]
- **Technical Requirements:** [Technical integration constraints from IT stakeholders]
- **Communication Requirements:** [Public-facing integration needs]

### Supporting Business Processes
**Process Integration Requirements:**
- **Workflow Automation:** [How integrations support automated government processes]
- **Approval Workflows:** [Integration with government approval processes]
- **Reporting Integration:** [How integrations support government reporting requirements]
- **Citizen Services:** [How integrations improve citizen service delivery]

## INTEGRATION VALIDATION

### Analysis Quality Checklist
- [ ] All current integrations documented and assessed
- [ ] New integration requirements clearly defined
- [ ] Technical constraints and limitations identified
- [ ] Security and compliance requirements addressed
- [ ] Integration architecture strategy defined
- [ ] Risk assessment completed with mitigation strategies
- [ ] Implementation timeline realistic and achievable
- [ ] Success criteria and performance targets defined

### Integration Analysis Confidence Level
**Current State Analysis Confidence:** [High/Medium/Low]
**Requirements Definition Confidence:** [High/Medium/Low]
**Technical Feasibility Confidence:** [High/Medium/Low]
**Timeline Estimate Confidence:** [High/Medium/Low]

**CRITICAL INTEGRATION DEPENDENCIES:** [Any integrations that could block project progress]
**INTEGRATION RISKS REQUIRING IMMEDIATE ATTENTION:** [High-risk integrations needing early focus]
```

**INTEGRATION ANALYSIS INSTRUCTIONS:**
1. Map complete current integration landscape - don't miss any existing connections
2. Prioritize integrations by business criticality and citizen service impact
3. Identify realistic technical constraints - legacy systems have real limitations
4. Focus on government compliance requirements for data sharing and security
5. Plan for integration failure scenarios - government services must be resilient
6. Consider vendor dependencies and procurement constraints early
7. Ensure integration approach supports stakeholder workflow requirements

---

## Usage Notes

### Before Analysis
- **Inventory all current systems** including legacy and third-party systems
- **Document existing integrations** with performance and reliability data
- **Review government data standards** applicable to your jurisdiction
- **Coordinate with IT team** for system access and documentation

### During Analysis
- **Focus on business-critical integrations** first - what's essential for citizen services
- **Assess realistic technical constraints** - don't assume all integrations are possible
- **Document compliance requirements** for each integration
- **Consider operational impact** of integration changes on government staff

### After Analysis
- **Validate with IT stakeholders** technical feasibility and constraints
- **Review with operations staff** impact on business processes
- **Coordinate with vendors** on integration capabilities and requirements
- **Plan integration testing** strategy early in project timeline

### Quality Standards
- **Business-driven integration priorities** ensure citizen service delivery focus
- **Technical reality assessment** prevents unrealistic integration expectations
- **Government compliance focus** ensures regulatory requirements met
- **Operational sustainability** ensures integrations can be maintained long-term

---

## File Naming Convention
Save analysis as: `Integration-Analysis-[ProjectName]-[Date].md`

Example: `Integration-Analysis-Denver-Parks-Portal-2024-03-17.md`
