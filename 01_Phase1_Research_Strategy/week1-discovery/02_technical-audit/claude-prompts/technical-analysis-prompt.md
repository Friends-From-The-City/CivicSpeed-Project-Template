# Technical Analysis - Claude Prompt (Screaming Frog Data)

## Context & Purpose
You are analyzing technical audit data from Screaming Frog SEO Spider for a government website transformation project. Your role is to identify critical technical issues, compliance gaps, and improvement opportunities that impact citizen service delivery and government operations.

**Analysis Objectives:**
- Identify technical barriers to citizen service access
- Document government compliance gaps (Section 508, security, transparency)
- Prioritize technical improvements by citizen impact
- Generate actionable technical requirements for development
- Connect technical findings to stakeholder priorities from interviews

## Required Inputs
Before beginning analysis, ensure you have:

1. **Screaming Frog audit data** (exported reports and analysis)
2. **Current website URL** and scope of audit
3. **Stakeholder interview insights** (for context and priorities)
4. **Government agency information:**
   - Agency type and service focus
   - Compliance requirements (federal, state, local)
   - Current traffic volume and peak usage patterns
   - Budget range for technical improvements

## Technical Analysis Framework

### Pre-Analysis Setup
**Audit Scope Validation:**
- [ ] **Complete site crawl** performed (all public pages)
- [ ] **Mobile responsiveness** testing included
- [ ] **Accessibility scanning** completed
- [ ] **Performance testing** conducted
- [ ] **Security headers** analysis included

**Government Context:**
- [ ] **Compliance requirements** identified (Section 508, WCAG, security)
- [ ] **Citizen service priorities** documented from stakeholder interviews
- [ ] **Peak usage periods** and traffic patterns understood
- [ ] **Legacy system constraints** noted from technical stakeholders

## Analysis Template

Generate analysis using this exact structure:

### TECHNICAL AUDIT OVERVIEW
**Website:** [Full URL and agency name]  
**Audit Date:** [Screaming Frog analysis date]  
**Analysis Completion:** [Current date]  
**Pages Analyzed:** [Total pages crawled]  
**Audit Scope:** [Full site, specific sections, or limitations]

**Tool Configuration:**
- **Screaming Frog Version:** [Version used]
- **Additional Tools:** [Any supplementary analysis tools]
- **Audit Limitations:** [Any technical constraints or scope limitations]

### CRITICAL ISSUES (Immediate Citizen Impact)

#### Accessibility Violations (Section 508 & WCAG 2.1 AA)
**Critical Violations:**
- **[Specific Issue]:** [Description, pages affected, citizen impact]
  - **Pages Affected:** [Number and percentage of pages]
  - **Citizen Impact:** [How this prevents access to government services]
  - **Compliance Risk:** [Legal/regulatory implications]
  - **Fix Priority:** [High/Medium/Low with rationale]

- **[Specific Issue]:** [Description, pages affected, citizen impact]
  - **Pages Affected:** [Number and percentage of pages]
  - **Citizen Impact:** [How this prevents access to government services]
  - **Compliance Risk:** [Legal/regulatory implications]
  - **Fix Priority:** [High/Medium/Low with rationale]

**Accessibility Summary:**
- **Total Violations:** [Count by severity level]
- **Most Common Issues:** [Top 3 accessibility problems]
- **Estimated Remediation Effort:** [Development time and complexity]

#### Performance Issues (Citizen Experience Impact)
**Page Load Performance:**
- **Average Load Time:** [Seconds across all pages]
- **Slowest Pages:** [Worst performing pages and load times]
- **Mobile Performance:** [Mobile-specific performance issues]
- **Peak Traffic Impact:** [How performance degrades under load]

**Core Web Vitals Issues:**
- **Largest Contentful Paint (LCP):** [Score and problematic pages]
- **First Input Delay (FID):** [Score and interaction delays]
- **Cumulative Layout Shift (CLS):** [Score and visual stability issues]

**Performance Impact Analysis:**
- **Citizen Abandonment Risk:** [Pages likely to lose users due to speed]
- **Government Service Delivery:** [How performance affects service completion]
- **Staff Productivity:** [How performance impacts internal users]

#### Mobile Responsiveness Issues
**Mobile Usability Problems:**
- **[Specific Issue]:** [Description and affected pages]
  - **Citizen Impact:** [How this affects mobile service access]
  - **Usage Data:** [Mobile traffic percentage if available]
  - **Fix Complexity:** [Technical effort required]

- **[Specific Issue]:** [Description and affected pages]
  - **Citizen Impact:** [How this affects mobile service access]
  - **Usage Data:** [Mobile traffic percentage if available]  
  - **Fix Complexity:** [Technical effort required]

**Mobile Strategy Requirements:**
- **Current Mobile Traffic:** [Percentage of total traffic]
- **Mobile Service Priorities:** [Critical services citizens access on mobile]
- **Mobile-First Redesign Needs:** [Components requiring mobile optimization]

### COMPLIANCE & SECURITY ANALYSIS

#### Government Compliance Status
**Section 508 Compliance:**
- **Current Compliance Level:** [Estimated percentage compliance with detailed gap analysis]
- **Critical Accessibility Barriers:** [Specific WCAG 2.1 AA failures preventing citizen access]
- **Screen Reader Compatibility:** [Navigation and form accessibility for assistive technology]
- **Keyboard Navigation:** [Full site accessibility without mouse interaction]
- **Color and Contrast:** [Visual accessibility for citizens with visual impairments]
- **Alternative Text and Media:** [Image, video, and audio accessibility compliance]
- **Form Accessibility:** [Government form completion accessibility for all citizens]

**WCAG 2.1 AA Compliance:**
- **Perceivable Compliance:** [Text alternatives, captions, color contrast issues]
- **Operable Compliance:** [Keyboard accessibility, timing, seizure prevention]
- **Understandable Compliance:** [Readable text, predictable functionality, input assistance]
- **Robust Compliance:** [Compatibility with assistive technologies]
- **Quick Wins vs. Complex Fixes:** [Easy accessibility improvements vs. major development needs]

**Open Data & Transparency:**
- **Public Information Access:** [How well citizens can find required information]
- **Document Accessibility:** [PDF and document accessibility status]
- **Search Functionality:** [Effectiveness of site search for finding information]

#### Security Assessment
**NIST Cybersecurity Framework Compliance:**
- **Identify:** [Asset management, governance, risk assessment capabilities]
- **Protect:** [Access control, data security, protective technology implementation]
- **Detect:** [Continuous monitoring, detection processes, anomaly identification]
- **Respond:** [Incident response planning, communication, analysis capabilities]
- **Recover:** [Recovery planning, improvements, communication during recovery]

**Authority to Operate (ATO) Requirements:**
- **Security Control Assessment:** [Required security controls and current implementation status]
- **Risk Assessment Documentation:** [Security risk analysis and mitigation strategies]
- **System Security Plan:** [Comprehensive security documentation requirements]
- **Continuous Monitoring:** [Ongoing security assessment and reporting procedures]
- **ATO Timeline:** [Realistic timeline for security authorization process]

**Government Security Standards:**
- **FedRAMP Compliance:** [Federal cloud security requirements if applicable]
- **State Security Frameworks:** [State-specific security standards and requirements]
- **Local Security Policies:** [Municipal or county security requirements]
- **Data Classification:** [Government data classification and protection requirements]

### TECHNICAL ARCHITECTURE ASSESSMENT

#### Current Technology Stack
**Content Management System:**
- **Platform:** [CMS platform identified and version]
- **Strengths:** [What's working well with current system]
- **Limitations:** [Technical constraints and bottlenecks]
- **Upgrade Path:** [Options for improvement or replacement]

**Hosting & Infrastructure:**
- **Hosting Environment:** [Server configuration and hosting type]
- **Performance Capacity:** [Ability to handle traffic spikes]
- **Backup & Recovery:** [Data protection and disaster recovery status]
- **Scalability:** [Ability to grow with agency needs]

**Third-Party Integrations:**
- **Current Integrations:** [External systems and services connected]
- **Integration Quality:** [Reliability and performance of connections]
- **Legacy System Dependencies:** [Old systems that must remain connected]
- **Future Integration Needs:** [Systems stakeholders want to connect]

#### Code Quality & Standards
**HTML/CSS Quality:**
- **Code Validation:** [W3C validation errors and warnings]
- **CSS Efficiency:** [Stylesheet optimization opportunities]
- **JavaScript Performance:** [Script loading and execution issues]
- **Code Maintainability:** [Ease of ongoing development and updates]

**SEO & Discoverability:**
- **Search Engine Optimization:** [How well citizens can find information via search]
- **Site Structure:** [URL structure and navigation hierarchy quality]
- **Content Organization:** [Information architecture effectiveness]
- **Internal Linking:** [How well pages connect and guide users]

### CITIZEN SERVICE IMPACT ANALYSIS

#### Service Delivery Barriers
**High-Impact Issues:**
- **[Technical Issue]:** [How this prevents citizens from completing tasks]
  - **Affected Services:** [Government services impacted]
  - **Citizen Frustration Level:** [Severity of user experience problem]
  - **Workaround Requirements:** [What citizens must do instead]
  - **Resolution Impact:** [Benefit of fixing this issue]

- **[Technical Issue]:** [How this prevents citizens from completing tasks]
  - **Affected Services:** [Government services impacted]
  - **Citizen Frustration Level:** [Severity of user experience problem]
  - **Workaround Requirements:** [What citizens must do instead]
  - **Resolution Impact:** [Benefit of fixing this issue]

#### Priority Service Areas
**Most Critical to Fix:**
1. **[Service Area]:** [Why this technical fix would most improve citizen experience]
2. **[Service Area]:** [Government service that needs immediate technical attention]
3. **[Service Area]:** [Technical improvement with highest public benefit]

**Quick Wins for Citizens:**
- **[Technical Fix]:** [Easy improvement with immediate citizen benefit]
- **[Technical Fix]:** [Low-effort change that improves service access]
- **[Technical Fix]:** [Simple fix that removes major citizen frustration]

### STAKEHOLDER ALIGNMENT

#### Technical Stakeholder Validation
**IT Team Priorities (from interviews):**
- **[Priority]:** [How technical audit findings support IT stakeholder goals]
- **[Priority]:** [Technical issues that align with IT team concerns]
- **[Priority]:** [Audit findings that validate IT stakeholder requests]

**Operations Team Impact:**
- **[Finding]:** [How technical issues affect daily operations]
- **[Finding]:** [Technical improvements that would help staff efficiency]
- **[Finding]:** [Audit results that explain operational pain points]

#### Executive Priority Alignment
**Strategic Goal Support:**
- **[Executive Priority]:** [How technical improvements support strategic goals]
- **[Executive Priority]:** [Technical barriers to achieving leadership vision]
- **[Executive Priority]:** [Technology investments needed for strategic success]

**Budget Considerations:**
- **High-ROI Fixes:** [Technical improvements with best cost/benefit ratio]
- **Critical Infrastructure:** [Must-fix items for basic government operations]
- **Phased Implementation:** [How to spread technical improvements over time/budget]

### IMPLEMENTATION ROADMAP

#### Phase 2 Technical Requirements (Immediate - Months 1-6)
**Critical Path Items:**
1. **[Technical Requirement]:** [Essential for citizen service improvement]
   - **Implementation Effort:** [Development time and resources needed]
   - **Dependencies:** [What must be completed first]
   - **Success Criteria:** [How to measure successful implementation]

2. **[Technical Requirement]:** [Essential for compliance or security]
   - **Implementation Effort:** [Development time and resources needed]
   - **Dependencies:** [What must be completed first]
   - **Success Criteria:** [How to measure successful implementation]

3. **[Technical Requirement]:** [Essential for operational efficiency]
   - **Implementation Effort:** [Development time and resources needed]
   - **Dependencies:** [What must be completed first]  
   - **Success Criteria:** [How to measure successful implementation]

#### Medium-Term Improvements (Months 6-12)
**Infrastructure Upgrades:**
- **[Upgrade]:** [System improvement for long-term sustainability]
- **[Upgrade]:** [Platform enhancement for expanded capabilities]
- **[Upgrade]:** [Security improvement for ongoing protection]

**Enhanced Functionality:**
- **[Enhancement]:** [Advanced feature for improved citizen service]
- **[Enhancement]:** [Integration capability for better government operations]
- **[Enhancement]:** [Performance optimization for peak usage handling]

#### Long-Term Strategic Goals (12+ Months)
**Technology Modernization:**
- **[Modernization Goal]:** [Long-term technology vision]
- **[Integration Goal]:** [Future system integration capabilities]
- **[Innovation Goal]:** [Emerging technology adoption for citizen benefit]

### PERFORMANCE BENCHMARKS

#### Current Performance Baseline
**Speed Metrics:**
- **Average Page Load:** [Current performance across all pages]
- **Mobile Performance:** [Mobile-specific speed measurements]
- **Peak Traffic Performance:** [How site performs under load]

**Availability Metrics:**
- **Current Uptime:** [Reliability measurement if available]
- **Error Rates:** [404 errors, broken links, server errors]
- **Service Availability:** [Critical service accessibility rates]

#### Improvement Targets
**Post-Implementation Goals:**
- **Load Time Target:** [<3 seconds based on government best practices]
- **Mobile Performance Target:** [Mobile-first optimization goals]
- **Uptime Target:** [99.9% availability for government services]
- **Accessibility Target:** [100% WCAG 2.1 AA compliance]

### TECHNICAL RECOMMENDATIONS

#### Immediate Actions (Week 1-2 of Phase 2)
1. **[Action]:** [Quick fix with high citizen impact]
2. **[Action]:** [Critical security or compliance fix]
3. **[Action]:** [Performance improvement with immediate effect]

#### Development Priorities (Phase 2 Design)
1. **[Priority]:** [Technical requirement that must guide design decisions]
2. **[Priority]:** [Infrastructure consideration for design planning]
3. **[Priority]:** [Compliance requirement that affects all design choices]

#### Quality Assurance Requirements
**Testing Standards:**
- **Accessibility Testing:** [Ongoing WCAG compliance validation]
- **Performance Testing:** [Load testing and speed optimization validation]
- **Security Testing:** [Vulnerability scanning and security validation]
- **Mobile Testing:** [Cross-device compatibility validation]

## Quality Assurance Standards

### Analysis Completeness Checklist
- [ ] All critical technical issues identified and prioritized by citizen impact
- [ ] Government compliance gaps documented with remediation plans
- [ ] Performance issues analyzed with specific improvement targets
- [ ] Security vulnerabilities assessed with government context
- [ ] Mobile responsiveness evaluated for citizen service access
- [ ] Technical recommendations aligned with stakeholder priorities

### Government Focus Requirements
- [ ] Citizen service delivery impact assessed for all technical issues
- [ ] Section 508 and WCAG compliance status thoroughly documented
- [ ] Government security and transparency requirements addressed
- [ ] Budget and resource constraints considered in all recommendations
- [ ] Public accountability and accessibility prioritized throughout analysis

### Technical Analysis Standards
- [ ] Move beyond surface issues to identify root technical causes
- [ ] Connect technical problems to citizen experience and government operations
- [ ] Provide specific, actionable recommendations with effort estimates
- [ ] Support all conclusions with data from Screaming Frog audit
- [ ] Balance technical excellence with government resource realities

## Integration with Week 1 Synthesis

### Technical Input for Cross-Stakeholder Synthesis
- [ ] **Priority technical issues** ranked by stakeholder impact
- [ ] **Compliance requirements** validated against government obligations
- [ ] **Implementation timeline** realistic based on technical complexity
- [ ] **Resource requirements** estimated for budgeting and planning

### Phase 2 Technical Foundation
- [ ] **Technical requirements** ready for design team briefing
- [ ] **Performance standards** established for development planning
- [ ] **Compliance framework** prepared for design and development
- [ ] **Quality assurance** requirements defined for ongoing validation

---

**Quality Guarantee:** This technical analysis framework ensures comprehensive evaluation of government website technical health while maintaining focus on citizen service improvement and government compliance requirements.
