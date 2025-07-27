# Technical Analysis Prompt: Website Audit Analyzer

## Purpose
This prompt analyzes raw technical audit data from website crawls, performance assessments, and accessibility scans to identify technical requirements, constraints, and optimization opportunities for government digital transformation projects.

## How to Use
1. **Complete website audit** using Screaming Frog, Google PageSpeed Insights, and accessibility tools
2. **Copy the prompt below** into a new Claude conversation
3. **Paste audit data and findings** as input
4. **Review technical analysis** for accuracy and completeness
5. **Use results to inform** technical requirements and stakeholder synthesis

---

## THE CLAUDE PROMPT
**Copy everything from this line down to the end of the code block into Claude:**

```
You are analyzing comprehensive website audit data for a government digital transformation project using the CivicSpeed methodology. Extract technical insights that will inform requirements development, identify modernization opportunities, and highlight compliance gaps that must be addressed.

**PROJECT CONTEXT:**
- Agency: [AGENCY_NAME]
- Current Website: [WEBSITE_URL]
- Audit Date: [AUDIT_DATE]
- Methodology: CivicSpeed AI-Accelerated Government Digital Transformation

**AUDIT DATA INPUT:**
[PASTE SCREAMING FROG EXPORT DATA HERE]
[PASTE GOOGLE PAGESPEED INSIGHTS RESULTS HERE]
[PASTE ACCESSIBILITY SCAN RESULTS HERE]
[PASTE SECURITY HEADERS SCAN RESULTS HERE]

**TECHNICAL ANALYSIS FRAMEWORK:**
Analyze audit data across 6 critical dimensions for government website modernization:

## ANALYSIS METHODOLOGY

### 1. CURRENT STATE ASSESSMENT
**Technology Stack Analysis:**
- Identify current CMS, hosting, and technology platforms
- Document third-party integrations and dependencies
- Map content management and publication workflows
- Assess current development and maintenance processes

**Architecture Evaluation:**
- Analyze site structure and information architecture
- Identify technical debt and legacy code issues
- Document server infrastructure and hosting environment
- Evaluate scalability and performance architecture

### 2. PERFORMANCE & USER EXPERIENCE
**Core Web Vitals Analysis:**
- Analyze Largest Contentful Paint (LCP) performance
- Evaluate First Input Delay (FID) responsiveness
- Assess Cumulative Layout Shift (CLS) stability
- Identify specific performance bottlenecks and optimization opportunities

**Mobile & Multi-Device Assessment:**
- Evaluate mobile responsiveness and optimization
- Analyze cross-device user experience consistency
- Identify mobile-specific performance issues
- Assess touch interface and mobile navigation effectiveness

### 3. ACCESSIBILITY & COMPLIANCE
**Section 508 Compliance Analysis:**
- Document WCAG 2.1 AA compliance gaps
- Identify accessibility barriers for users with disabilities
- Evaluate keyboard navigation and screen reader compatibility
- Assess color contrast, alt text, and semantic markup quality

**Government Requirements Assessment:**
- Analyze compliance with government web standards
- Evaluate plain language implementation
- Assess multi-language support and cultural accessibility
- Document transparency and public information requirements

**OUTPUT FORMAT:**
Present technical analysis using this exact structure:

## EXECUTIVE SUMMARY
**Technical Health Score:** [Excellent/Good/Fair/Poor with percentage score]
**Modernization Priority:** [High/Medium/Low urgency for technical overhaul]
**Performance Status:** [Meeting/Not Meeting government web performance standards]
**Compliance Status:** [Compliant/Partially Compliant/Non-Compliant with government standards]
**Estimated Technical Debt:** [High/Medium/Low level of legacy issues requiring resolution]

## CURRENT STATE ANALYSIS

### Technology Infrastructure
**Current Technology Stack:**
- **Content Management System:** [CMS platform, version, customizations]
- **Hosting Environment:** [Server type, location, configuration]
- **Frontend Framework:** [Technologies used for user interface]
- **Backend Systems:** [Server-side technologies and databases]
- **Third-Party Integrations:** [External services and APIs currently used]

**Architecture Assessment:**
- **Scalability:** [Current system's ability to handle growth]
- **Maintainability:** [Ease of updates and ongoing maintenance]
- **Security Architecture:** [Current security implementation and gaps]
- **Integration Capabilities:** [Ability to connect with other government systems]

### Content & Information Architecture
**Content Analysis:**
- **Total Pages/Content:** [Volume of content requiring migration or optimization]
- **Content Quality:** [Assessment of content accuracy, currency, and usefulness]
- **Content Management:** [Current workflow efficiency and bottlenecks]
- **SEO Performance:** [Search visibility and optimization status]

**Information Architecture Issues:**
- **Navigation Problems:** [User wayfinding and menu structure issues]
- **Content Organization:** [Logical structure and categorization problems]
- **Search Functionality:** [Current search capabilities and limitations]
- **User Journey Disruptions:** [Where current IA breaks down user flows]

## PERFORMANCE ANALYSIS

### Core Web Vitals Assessment
**Largest Contentful Paint (LCP):**
- **Current Score:** [Time in seconds and performance rating]
- **Primary Issues:** [Specific elements causing slow loading]
- **Optimization Opportunities:** [Technical improvements to implement]
- **Government Impact:** [How performance affects citizen service delivery]

**First Input Delay (FID):**
- **Current Score:** [Time in milliseconds and performance rating]
- **Interaction Issues:** [Problems with user input responsiveness]
- **JavaScript Problems:** [Script-related performance bottlenecks]
- **Mobile Impact:** [Specific mobile interaction delays]

**Cumulative Layout Shift (CLS):**
- **Current Score:** [CLS score and stability rating]
- **Layout Problems:** [Elements causing visual instability]
- **User Experience Impact:** [How layout shifts affect usability]
- **Fix Requirements:** [Technical changes needed for stability]

### Mobile Performance Assessment
**Mobile Optimization Status:**
- **Mobile Performance Score:** [PageSpeed Insights mobile score]
- **Responsive Design Quality:** [Assessment of mobile layout adaptation]
- **Touch Interface Effectiveness:** [Mobile interaction usability]
- **Mobile-Specific Issues:** [Problems unique to mobile devices]

**Cross-Device Consistency:**
- **Desktop vs Mobile Experience:** [Differences in functionality and content]
- **Tablet Optimization:** [How well site works on tablet devices]
- **Browser Compatibility:** [Cross-browser performance and functionality]

## ACCESSIBILITY & COMPLIANCE ANALYSIS

### WCAG 2.1 AA Compliance Assessment
**Accessibility Score:** [Percentage compliance with specific gap count]

**Critical Accessibility Issues:**
1. **[Issue Type 1]** (e.g., Missing Alt Text)
   - **Scope:** [Number of instances and affected pages]
   - **Impact:** [Which disabilities are affected]
   - **Fix Complexity:** [Simple/Moderate/Complex technical solution]
   - **Priority:** [High/Medium/Low based on user impact]

2. **[Issue Type 2]** (e.g., Color Contrast Failures)
   - **Scope:** [Number of instances and affected pages]
   - **Impact:** [Which disabilities are affected]
   - **Fix Complexity:** [Simple/Moderate/Complex technical solution]
   - **Priority:** [High/Medium/Low based on user impact]

3. **[Issue Type 3]** (e.g., Keyboard Navigation Problems)
   - **Scope:** [Number of instances and affected pages]
   - **Impact:** [Which disabilities are affected]
   - **Fix Complexity:** [Simple/Moderate/Complex technical solution]
   - **Priority:** [High/Medium/Low based on user impact]

### Government Compliance Assessment
**Section 508 Compliance:**
- **Current Compliance Level:** [Percentage or rating]
- **Missing Requirements:** [Specific Section 508 standards not met]
- **Remediation Timeline:** [Estimated time to achieve compliance]
- **Legal Risk Assessment:** [Compliance risk evaluation]

**Government Web Standards:**
- **Plain Language Implementation:** [Quality of citizen-friendly language]
- **Government Branding Compliance:** [Adherence to agency brand standards]
- **Transparency Requirements:** [Public information accessibility]
- **Multi-Language Support:** [Current language accessibility]

## SECURITY ANALYSIS

### Security Headers Assessment
**Security Implementation Status:**
- **HTTPS Implementation:** [SSL/TLS configuration quality]
- **Security Headers Present:** [Which security headers are implemented]
- **Missing Security Measures:** [Critical security gaps identified]
- **Vulnerability Assessment:** [Potential security risks identified]

**Government Security Requirements:**
- **NIST Framework Alignment:** [Current alignment with government security standards]
- **Data Protection Implementation:** [How personal data is currently protected]
- **Authentication Security:** [Current user authentication methods]
- **Third-Party Security:** [Security assessment of external integrations]

## TECHNICAL REQUIREMENTS IMPLICATIONS

### Modernization Requirements
**Critical Technical Upgrades:**
1. **[Requirement 1]** (e.g., Performance Optimization)
   - **Current Gap:** [Specific technical deficiency]
   - **Required Solution:** [Technical approach needed]
   - **Implementation Complexity:** [Development effort required]
   - **Business Impact:** [How this affects citizen services]

2. **[Requirement 2]** (e.g., Accessibility Compliance)
   - **Current Gap:** [Specific technical deficiency]
   - **Required Solution:** [Technical approach needed]
   - **Implementation Complexity:** [Development effort required]
   - **Business Impact:** [How this affects citizen services]

3. **[Requirement 3]** (e.g., Security Enhancement)
   - **Current Gap:** [Specific technical deficiency]
   - **Required Solution:** [Technical approach needed]
   - **Implementation Complexity:** [Development effort required]
   - **Business Impact:** [How this affects citizen services]

### Integration Constraints
**Current System Limitations:**
- **Integration Capabilities:** [What systems can currently connect]
- **API Availability:** [Current API access and limitations]
- **Data Export/Import:** [Current data portability options]
- **Legacy System Dependencies:** [Systems that must be maintained during transition]

**Migration Considerations:**
- **Content Migration Complexity:** [Effort required to move existing content]
- **URL Structure Changes:** [SEO and user impact of site restructuring]
- **User Account Migration:** [Current user data and access considerations]
- **Downtime Requirements:** [Necessary service interruptions during migration]

## OPTIMIZATION OPPORTUNITIES

### Performance Improvements
**High-Impact Optimizations:**
- **Image Optimization:** [Potential performance gains from image compression/formatting]
- **Code Optimization:** [JavaScript/CSS optimization opportunities]
- **Caching Implementation:** [Server and browser caching improvements]
- **Content Delivery:** [CDN implementation benefits]

**User Experience Enhancements:**
- **Navigation Improvements:** [Specific IA and navigation optimizations]
- **Search Enhancement:** [Search functionality improvement opportunities]
- **Mobile Optimization:** [Mobile-specific user experience improvements]
- **Accessibility Enhancements:** [Beyond compliance - usability improvements]

### Content Strategy Implications
**Content Management Improvements:**
- **Workflow Optimization:** [More efficient content creation and approval processes]
- **Content Quality:** [Opportunities for better citizen-focused content]
- **SEO Enhancement:** [Search visibility improvement opportunities]
- **Multi-Channel Content:** [Content reuse across different platforms]

## RISK ASSESSMENT

### Technical Risks
**High-Risk Areas:**
1. **[Risk 1]** (e.g., Legacy System Failure)
   - **Risk Description:** [What could go wrong]
   - **Probability:** [High/Medium/Low likelihood]
   - **Impact:** [Effect on citizen services and agency operations]
   - **Mitigation Strategy:** [How to prevent or minimize risk]

2. **[Risk 2]** (e.g., Performance Degradation)
   - **Risk Description:** [What could go wrong]
   - **Probability:** [High/Medium/Low likelihood]
   - **Impact:** [Effect on citizen services and agency operations]
   - **Mitigation Strategy:** [How to prevent or minimize risk]

**Compliance Risks:**
- **Accessibility Legal Risk:** [Potential ADA/Section 508 compliance issues]
- **Security Vulnerability Risk:** [Data protection and security concerns]
- **Performance Standard Risk:** [Government web performance requirement violations]

## RECOMMENDATIONS

### Immediate Actions (Week 1 Completion)
1. **[Action 1]**: [Specific technical action needed before Week 2]
2. **[Action 2]**: [Specific technical action needed before Week 2]
3. **[Action 3]**: [Specific technical action needed before Week 2]

### Phase 2 Design Implications
**Technical Architecture Decisions:**
- **Technology Stack Recommendations:** [Preferred technologies based on audit findings]
- **Performance Requirements:** [Specific performance targets based on current gaps]
- **Accessibility Integration:** [How to build accessibility into new design from start]
- **Security Implementation:** [Security requirements based on current vulnerabilities]

### Phase 3 Development Priorities
**Development Sequence Recommendations:**
1. **[Priority 1]**: [Most critical technical issue to address first]
2. **[Priority 2]**: [Second priority based on technical and user impact]
3. **[Priority 3]**: [Third priority considering dependencies and complexity]

## STAKEHOLDER SYNTHESIS INTEGRATION

### Validating Stakeholder Claims
**Performance Complaints:** [Do audit findings support stakeholder performance concerns?]
**Accessibility Issues:** [Do compliance gaps match stakeholder accessibility feedback?]
**Integration Challenges:** [Do technical limitations align with stakeholder integration needs?]
**User Experience Problems:** [Do technical issues explain stakeholder UX concerns?]

### Supporting Requirements Development
**Technical Constraints:** [Technical limitations that will affect new development]
**Performance Baselines:** [Current metrics to improve upon]
**Compliance Requirements:** [Technical standards that must be met]
**Integration Capabilities:** [Current system connection possibilities]

## AUDIT VALIDATION

### Data Quality Checklist
- [ ] All major site sections crawled and analyzed
- [ ] Performance testing completed across multiple devices
- [ ] Accessibility scan covered representative page types
- [ ] Security assessment included all critical vulnerabilities
- [ ] Integration analysis documented all current connections
- [ ] Technical findings specific and actionable
- [ ] Compliance gaps clearly identified with remediation paths
- [ ] Risk assessment realistic and complete

### Analysis Confidence Level
**Technical Assessment Confidence:** [High/Medium/Low]
**Performance Analysis Confidence:** [High/Medium/Low]
**Compliance Analysis Confidence:** [High/Medium/Low]
**Integration Analysis Confidence:** [High/Medium/Low]

**CRITICAL TECHNICAL DEPENDENCIES:** [Any technical issues that could block project progress]
**IMMEDIATE TECHNICAL CONCERNS:** [Technical issues requiring immediate attention]
```

**TECHNICAL ANALYSIS INSTRUCTIONS:**
1. Focus on objective, measurable technical data rather than subjective assessments
2. Identify specific technical constraints that will affect new development
3. Prioritize government compliance requirements (Section 508, security standards)
4. Connect technical findings to citizen service delivery impact
5. Provide specific, actionable recommendations with implementation complexity estimates
6. Validate or challenge stakeholder technical claims with audit evidence
7. Ensure analysis supports both technical requirements development and stakeholder synthesis

---

## Usage Notes

### Before Analysis
- **Ensure complete audit data collection** across all critical site areas
- **Verify tool configurations** are appropriate for government website analysis
- **Coordinate with IT stakeholders** for any access or permission requirements
- **Document audit methodology** for validation and repeatability

### During Analysis
- **Focus on government-specific requirements** - accessibility, security, transparency
- **Quantify performance impacts** on citizen service delivery
- **Identify integration constraints** that affect technical requirements
- **Document compliance gaps** with specific remediation approaches

### After Analysis
- **Cross-reference with stakeholder feedback** to validate or challenge claims
- **Integrate findings into technical requirements** development process
- **Flag critical issues** that need immediate attention
- **Prepare technical constraints** documentation for design phase

### Quality Standards
- **Objective data focus** ensures technical requirements based on measurable criteria
- **Government compliance priority** addresses regulatory requirements early
- **Citizen service impact** connects technical issues to user experience
- **Implementation feasibility** ensures recommendations are actionable

---

## File Naming Convention
Save analysis as: `Website-Audit-Analysis-[ProjectName]-[Date].md`

Example: `Website-Audit-Analysis-Denver-Parks-Portal-2024-03-15.md`
