# Technical Analysis Prompts

## 🎯 Purpose
This folder contains Claude prompts for analyzing raw technical audit data collected during Week 1 discovery. These prompts transform technical scan results, performance data, and compliance assessments into actionable insights for government digital transformation projects.

## 📋 Prompt Overview

### Analysis Workflow
1. **Collect Technical Data** → Use audit tools to gather raw technical data
2. **Apply Analysis Prompts** → Use Claude prompts to extract insights from data
3. **Generate Findings** → Create structured technical findings documents
4. **Inform Requirements** → Feed insights into Week 2 technical requirements development

---

## AVAILABLE ANALYSIS PROMPTS

### 1. Website Audit Analysis Prompt
**File:** `website-audit-analysis-prompt.md`
**Purpose:** Analyzes comprehensive website audit data from crawls, performance tests, and accessibility scans
**Input:** Screaming Frog exports, PageSpeed Insights results, accessibility scan data
**Output:** Structured analysis of current website technical status with modernization recommendations

**Key Analysis Areas:**
- Current technology stack assessment
- Performance bottleneck identification
- Content and information architecture issues
- Mobile optimization gaps
- SEO and content quality analysis

**Best For:**
- Understanding current website technical limitations
- Identifying performance optimization opportunities
- Planning content migration and IA improvements
- Setting performance baselines and targets

### 2. Security Assessment Analysis Prompt
**File:** `security-assessment-analysis-prompt.md`
**Purpose:** Analyzes security scan results, vulnerability assessments, and compliance evaluations
**Input:** Vulnerability scan results, penetration test findings, security configuration audits
**Output:** Comprehensive security gap analysis with government compliance focus

**Key Analysis Areas:**
- Critical vulnerability identification and prioritization
- Government security framework compliance (NIST, FedRAMP)
- Data protection and privacy requirements
- Authentication and access control assessment
- Incident response and monitoring capabilities

**Best For:**
- Identifying critical security risks requiring immediate attention
- Planning government security compliance implementation
- Developing security requirements for new system
- Risk assessment and mitigation strategy development

### 3. Integration Analysis Prompt
**File:** `integration-analysis-prompt.md`
**Purpose:** Analyzes current system integrations and defines requirements for new system connectivity
**Input:** System inventories, API documentation, data flow diagrams, integration test results
**Output:** Integration requirements and architecture recommendations

**Key Analysis Areas:**
- Current integration landscape mapping
- Legacy system constraint identification
- New system integration requirements definition
- Data flow and synchronization needs
- Government data standards compliance

**Best For:**
- Understanding current system connectivity limitations
- Planning integration architecture for new system
- Identifying data management and synchronization requirements
- Assessing vendor and third-party integration needs

### 4. Compliance Gap Analysis Prompt
**File:** `compliance-gap-analysis-prompt.md`
**Purpose:** Analyzes compliance with government regulations and identifies remediation requirements
**Input:** Compliance audit results, regulatory checklists, accessibility assessments
**Output:** Comprehensive compliance gap analysis with remediation strategies

**Key Analysis Areas:**
- Section 508 and WCAG accessibility compliance
- Government transparency and public access requirements
- Data protection and privacy compliance
- Security and cybersecurity framework compliance
- Domain-specific regulatory requirements

**Best For:**
- Ensuring all government compliance requirements identified
- Planning compliance remediation strategies
- Building compliance requirements into new system architecture
- Risk assessment for regulatory violations

---

## PROMPT USAGE GUIDE

### Getting Started
1. **Complete Technical Audit** using the tools and processes in the main technical audit README
2. **Choose Appropriate Prompt** based on the type of technical data you've collected
3. **Prepare Input Data** by organizing audit results according to prompt requirements
4. **Run Analysis** by copying prompt to Claude and providing your technical data
5. **Review Results** for accuracy and completeness before using in requirements development

### Data Preparation Tips
**For Website Audit Analysis:**
- Export complete Screaming Frog crawl data
- Run PageSpeed Insights on key pages (homepage, top services, forms)
- Perform accessibility scans using WAVE and manual testing
- Document current hosting and technology infrastructure

**For Security Assessment Analysis:**
- Run comprehensive vulnerability scans (with appropriate permissions)
- Document current security configurations and policies
- Include results from any penetration testing or security reviews
- Gather compliance audit results if available

**For Integration Analysis:**
- Create complete inventory of current systems and their capabilities
- Document existing integration methods and performance
- Gather API documentation and technical specifications
- Test current integration reliability and speed

**For Compliance Gap Analysis:**
- Research all applicable federal, state, and local regulations
- Perform accessibility compliance testing against WCAG 2.1 AA
- Review government transparency and public access requirements
- Assess data protection and privacy policy compliance

---

## PROMPT INTEGRATION WORKFLOW

### Week 1 Technical Analysis Sequence
**Days 1-2: Data Collection**
- Set up audit tools and obtain necessary permissions
- Perform comprehensive website crawl using Screaming Frog
- Run initial performance and accessibility scans
- Begin system inventory and integration documentation

**Days 3-4: Deep Analysis**
- Complete security vulnerability assessments
- Perform detailed performance testing across devices
- Document compliance requirements and current status
- Analyze integration capabilities and constraints

**Days 5-6: Claude Analysis**
- Run **Website Audit Analysis Prompt** with collected website data
- Run **Security Assessment Analysis Prompt** with security scan results
- Run **Integration Analysis Prompt** with system integration data
- Run **Compliance Gap Analysis Prompt** with regulatory assessment data

**Day 7: Synthesis & Documentation**
- Combine insights from all technical analysis prompts
- Complete **Technical Findings Summary Template**
- Validate findings with technical stakeholders
- Prepare technical constraints for Week 2 strategy development

### Integration with Stakeholder Analysis
**Technical Validation of Stakeholder Claims:**
- Use technical analysis results to validate or challenge stakeholder technical concerns
- Identify objective data that supports stakeholder priorities
- Highlight technical constraints that may affect stakeholder expectations
- Provide measurable baselines for improvement claims

**Supporting Requirements Development:**
- Technical analysis provides specific technical constraints for requirements
- Performance data establishes improvement targets and baselines
- Security findings define non-negotiable security requirements
- Integration analysis informs system architecture decisions

---

## PROMPT CUSTOMIZATION GUIDE

### Adapting Prompts for Agency Context
**Government Level Adaptations:**
- **Federal Agencies:** Emphasize FedRAMP, FISMA, and federal accessibility requirements
- **State Agencies:** Focus on state-specific regulations and compliance frameworks
- **Local Government:** Prioritize local ordinances, transparency requirements, and citizen service delivery

**Domain-Specific Customizations:**
- **Healthcare Agencies:** Add HIPAA compliance and health data protection requirements
- **Education Agencies:** Include FERPA compliance and student data protection
- **Financial Agencies:** Add financial regulation compliance and PCI DSS requirements
- **Public Safety:** Include criminal justice data protection and emergency service requirements

### Technical Environment Adaptations
**Legacy System Considerations:**
- Modify integration analysis for agencies with significant legacy system constraints
- Adjust security analysis for mixed modern/legacy environments
- Account for budget constraints affecting modernization scope
- Consider gradual migration strategies for complex legacy environments

**Resource Constraint Adaptations:**
- Adjust recommendations based on available technical staff capabilities
- Consider vendor dependency limitations for agencies with procurement constraints
- Account for budget limitations affecting technology choices
- Plan for phased implementation based on resource availability

---

## QUALITY ASSURANCE

### Analysis Quality Standards
**Completeness Validation:**
- [ ] All major technical systems and components analyzed
- [ ] Current state accurately documented with specific metrics
- [ ] Compliance requirements comprehensively identified
- [ ] Integration constraints and opportunities clearly defined
- [ ] Security risks prioritized with realistic remediation timelines

**Accuracy Validation:**
- [ ] Technical findings validated with IT stakeholders
- [ ] Performance data collected using standardized tools and methodologies
- [ ] Security assessments performed with appropriate permissions and scope
- [ ] Compliance requirements researched and verified with legal/compliance team
- [ ] Integration capabilities tested and documented with evidence

### Common Analysis Pitfalls
**Technical Analysis Mistakes to Avoid:**
- **Incomplete Data Collection:** Missing critical systems or components in analysis
- **Unrealistic Recommendations:** Suggesting solutions beyond agency technical capabilities
- **Compliance Oversights:** Missing applicable regulations or requirements
- **Integration Assumptions:** Assuming integration capabilities without testing
- **Security Superficiality:** Surface-level security assessment missing critical vulnerabilities

**Quality Improvement Tips:**
- **Cross-Reference Results:** Validate findings across multiple analysis types
- **Stakeholder Validation:** Review technical findings with agency technical staff
- **Documentation Standards:** Maintain consistent documentation and evidence
- **Timeline Realism:** Ensure implementation timelines account for government constraints
- **Resource Planning:** Consider actual agency resources and capabilities

---

## TROUBLESHOOTING GUIDE

### Common Technical Analysis Challenges
**Data Collection Issues:**
- **Limited System Access:** Work with IT team to gain appropriate access levels
- **Legacy System Documentation:** Focus on observable behavior and interface analysis
- **Security Restrictions:** Use external analysis tools and coordinate with security team
- **Complex Integration Environments:** Prioritize critical integrations and document assumptions

**Analysis Quality Issues:**
- **Incomplete Audit Data:** Re-run scans with broader scope or different tools
- **Conflicting Results:** Cross-reference findings and document discrepancies
- **Tool Limitations:** Use multiple analysis tools and manual validation
- **Technical Complexity:** Break complex analysis into smaller, manageable components

### When to Seek Additional Expertise
**Specialist Consultation Needed:**
- **Complex Security Environments:** Engage cybersecurity specialists for advanced threats
- **Legacy System Integration:** Consult with specialists in specific legacy technologies
- **Compliance Complexity:** Work with legal/compliance experts for complex regulatory environments
- **Performance Optimization:** Engage performance specialists for complex optimization challenges

---

## SUCCESS METRICS

### Technical Analysis Success Criteria
**Analysis Completeness:**
- [ ] All technical analysis prompts completed with comprehensive data
- [ ] Technical findings validated by agency technical stakeholders
- [ ] Compliance requirements identified and verified
- [ ] Integration constraints and opportunities clearly documented
- [ ] Performance baselines established with improvement targets defined

**Requirements Development Readiness:**
- [ ] Technical constraints clearly defined for requirements development
- [ ] Performance targets established based on current baseline data
- [ ] Security requirements defined based on risk assessment and compliance needs
- [ ] Integration requirements specified with realistic implementation approaches
- [ ] Compliance requirements integrated into technical architecture planning

**Week 2 Preparation:**
- [ ] Technical findings summary completed and approved
- [ ] Technical constraints documented for IA design
- [ ] Performance requirements established for user journey mapping
- [ ] Security and compliance requirements ready for technical requirements development

---

**Next Steps:** After completing technical analysis using these prompts, proceed to Week 2 strategy development using the technical findings as input for technical requirements generation, information architecture design, and user journey mapping.

**For Support:** Refer to the main technical audit README for overall process guidance, or contact the technical analysis team lead for specific prompt usage questions.
