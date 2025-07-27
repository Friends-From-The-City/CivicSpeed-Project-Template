
# Claude Prompt: Information Architecture Designer

## Purpose
This prompt transforms technical requirements into citizen-centered information architecture for government digital transformation projects. Creates IA that prioritizes citizen service delivery while meeting government compliance requirements and stakeholder priorities.

## How to Use
1. **Complete technical requirements first** using the Technical Requirements Generator
2. **Copy the prompt below** into a new Claude conversation
3. **Paste the technical requirements document** as input
4. **Review IA structure** for citizen-centricity and compliance coverage
5. **Validate with stakeholders** before proceeding to user journey mapping
6. **Use output to guide** user journey development and Phase 2 design work

---

## THE CLAUDE PROMPT
**Copy everything from this line down to the end of the code block into Claude:**

```
You are designing information architecture for a government digital transformation project using the CivicSpeed methodology. Create citizen-centered IA that prioritizes service delivery while meeting government compliance requirements and supporting stakeholder priorities identified in technical requirements.

**PROJECT CONTEXT:**
- Agency: [AGENCY_NAME]
- Project: [PROJECT_NAME]
- Phase: Week 2 Information Architecture Development
- Methodology: CivicSpeed AI-Accelerated Government Digital Transformation
- Focus: Citizen-centered service delivery with government compliance

**TECHNICAL REQUIREMENTS INPUT:**
[PASTE COMPLETE TECHNICAL REQUIREMENTS DOCUMENT HERE]

**INFORMATION ARCHITECTURE FRAMEWORK:**
Design IA across 6 critical dimensions for government digital services:

## IA DESIGN METHODOLOGY

### 1. CITIZEN-FIRST APPROACH
**Service-Centered Organization:**
- Organize by citizen needs and tasks, not government structure
- Prioritize most common citizen interactions
- Minimize cognitive load for service discovery

**Accessibility-First Design:**
- Multiple pathways to the same information
- Clear language and plain English requirements
- Visual and text-based navigation options

### 2. GOVERNMENT COMPLIANCE INTEGRATION
**Transparency Requirements:**
- Public information accessibility
- Clear government contact information
- Required disclosure and notice placements

**Approval Workflow Support:**
- Multi-level approval process integration
- Status tracking and communication
- Document management and version control

### 3. TECHNICAL CONSTRAINT ACCOMMODATION
**Performance Optimization:**
- IA structure supports technical performance requirements
- Content grouping reduces system load
- Efficient data retrieval patterns

**Integration-Friendly Design:**
- IA supports backend system integrations
- Clear data flow pathways
- Scalable content organization

**OUTPUT FORMAT:**
Present information architecture using this exact structure:

## EXECUTIVE SUMMARY
**IA Approach:** [Service-centered/Hybrid/Department-centered with rationale]
**Primary Navigation Strategy:** [How citizens will navigate services]
**Content Organization Principle:** [Key organizing principle for information]
**Accessibility Level:** [WCAG 2.1 AA compliance approach]
**Technical Compatibility:** [How IA supports technical requirements]

## SITE ARCHITECTURE OVERVIEW

### Top-Level Navigation Structure
**Primary Navigation:** (Maximum 7 items for cognitive load management)
1. **[Navigation Item 1]**
   - **Purpose:** [What citizen need this serves]
   - **Content:** [What information/services are included]
   - **User Priority:** [High/Medium/Low based on technical requirements]
   - **Technical Notes:** [Any performance or integration considerations]

2. **[Navigation Item 2]**
   - **Purpose:** [What citizen need this serves]
   - **Content:** [What information/services are included]
   - **User Priority:** [High/Medium/Low based on technical requirements]
   - **Technical Notes:** [Any performance or integration considerations]

3. **[Navigation Item 3]**
   - **Purpose:** [What citizen need this serves]
   - **Content:** [What information/services are included]
   - **User Priority:** [High/Medium/Low based on technical requirements]
   - **Technical Notes:** [Any performance or integration considerations]

**Secondary Navigation:** (Support and compliance items)
- **About/Transparency:** [Required government information]
- **Contact/Support:** [Help and contact information]
- **Accessibility:** [Accessibility resources and alternative formats]
- **Legal/Privacy:** [Legal notices and privacy information]

### Information Hierarchy
**Level 1: Service Categories** (Based on citizen needs from technical requirements)
```
[Service Category 1]
├── [Service 1.1]
├── [Service 1.2]
└── [Service 1.3]

[Service Category 2]
├── [Service 2.1]
├── [Service 2.2]
└── [Service 2.3]
```

**Level 2: Service Details** (Individual service pages)
- Service description and eligibility
- Step-by-step process guidance
- Required documents and forms
- Timeline and processing information
- Contact information for questions

**Level 3: Support Content** (Help and guidance)
- Frequently asked questions
- How-to guides and tutorials
- Troubleshooting information
- Alternative service access methods

## DETAILED INFORMATION ARCHITECTURE

### Service-Centered Organization
**[Primary Service Category 1]** (Based on technical requirements priority)
- **Overview Page:** [What citizens see first - service summary and entry points]
- **Eligibility & Requirements:** [Who can use service, what's needed]
- **Application Process:** [Step-by-step service process]
- **Forms & Documents:** [Required forms, supporting documents]
- **Status & Tracking:** [How to check application/request status]
- **Contact & Support:** [Service-specific help and contact information]
- **Related Services:** [Connected or similar services]

**Content Strategy:**
- **Plain Language Requirement:** [How content will meet plain language standards]
- **Multi-Format Support:** [Text, video, audio alternatives]
- **Translation Needs:** [Languages beyond English that must be supported]
- **Update Frequency:** [How often content needs refreshing]

**Technical Integration:**
- **Backend Connections:** [Which systems provide data for this category]
- **Real-Time Requirements:** [What information must be live/current]
- **Performance Considerations:** [Page load and search requirements]

### User Account & Authentication Area
**Account Management Structure:** (If applicable based on technical requirements)
- **Login/Registration:** [Account creation and access]
- **Dashboard/My Services:** [Personalized service overview]
- **Application History:** [Past and current service requests]
- **Document Library:** [Saved forms and uploaded documents]
- **Notification Preferences:** [Communication settings]
- **Profile Management:** [Personal information updates]

**Privacy & Security:**
- **Data Protection:** [How personal information is protected]
- **Access Controls:** [What users can see and modify]
- **Session Management:** [Login duration and security measures]

### Administrative & Staff Areas
**Staff Interface Organization:** (Based on technical requirements for staff functions)
- **Dashboard:** [Overview of pending work and priorities]
- **Application Processing:** [Tools for reviewing and approving requests]
- **Document Management:** [File storage and version control]
- **Reporting & Analytics:** [Performance metrics and compliance reporting]
- **System Administration:** [User management and system configuration]

**Workflow Integration:**
- **Approval Processes:** [How multi-level approvals are structured]
- **Status Tracking:** [How staff track application progress]
- **Communication Tools:** [Internal messaging and citizen communication]

## CONTENT STRATEGY

### Content Types & Organization
**Service Content:** (Primary citizen-facing content)
1. **Service Descriptions**
   - **Format:** [Standardized description template]
   - **Length:** [Target length for scannability]
   - **Required Elements:** [Eligibility, process, timeline, contacts]
   - **Accessibility:** [Alt text, plain language, multiple formats]

2. **Process Guidance**
   - **Step-by-Step Instructions:** [Numbered processes with visual aids]
   - **Decision Trees:** [Help citizens find the right path]
   - **Checklists:** [Required documents and preparation items]
   - **Video Tutorials:** [For complex processes]

3. **Forms & Documents**
   - **Form Organization:** [How forms are categorized and found]
   - **Version Control:** [How form updates are managed]
   - **Accessibility:** [Screen reader compatibility, large print options]
   - **Multi-Language:** [Translation and cultural adaptation]

**Support Content:** (Help and guidance)
- **FAQ Organization:** [How questions are grouped and searchable]
- **Help Articles:** [Detailed guidance for common issues]
- **Contact Information:** [Service-specific and general contact options]
- **Accessibility Resources:** [Alternative access methods and accommodations]

### Content Management Requirements
**Update Workflows:** (Based on technical requirements for staff functions)
- **Content Approval:** [Who approves different types of content updates]
- **Publication Schedule:** [When and how content goes live]
- **Version Control:** [How content changes are tracked and managed]
- **Quality Assurance:** [Content review and validation processes]

**Compliance Requirements:**
- **Legal Review:** [What content requires legal approval]
- **Accessibility Testing:** [How content accessibility is validated]
- **Plain Language:** [Content review for clarity and understanding]
- **Translation Management:** [How multi-language content is maintained]

## NAVIGATION DESIGN

### Primary Navigation Strategy
**Navigation Approach:** [Horizontal menu/Vertical menu/Mega menu based on content volume]
- **Rationale:** [Why this approach best serves citizen needs]
- **Accessibility Features:** [Keyboard navigation, screen reader support]
- **Mobile Optimization:** [How navigation works on small screens]
- **Performance Impact:** [How navigation affects page load times]

### Search & Discovery
**Search Functionality:** (Based on technical requirements for search performance)
- **Search Scope:** [What content is searchable]
- **Search Features:** [Auto-complete, spell correction, filters]
- **Result Organization:** [How search results are ranked and displayed]
- **Advanced Search:** [Filters and refinement options]

**Alternative Discovery Methods:**
- **Browse by Category:** [Topic-based browsing options]
- **Browse by Audience:** [Role-based content organization]
- **Popular Services:** [Most-used services prominently featured]
- **Related Content:** [Cross-linking strategy for related information]

### Breadcrumbs & Wayfinding
**Orientation Tools:**
- **Breadcrumb Strategy:** [How users understand their location]
- **Page Titles:** [Clear, descriptive page naming]
- **Section Indicators:** [Visual cues for site areas]
- **Progress Indicators:** [For multi-step processes]

## RESPONSIVE & ACCESSIBLE DESIGN

### Multi-Device Strategy
**Device Optimization:** (Based on technical requirements for multi-device support)
- **Mobile-First Approach:** [How content prioritization changes by device]
- **Tablet Considerations:** [Unique tablet interaction patterns]
- **Desktop Enhancement:** [Additional features for larger screens]
- **Print Optimization:** [How content appears when printed]

### Accessibility Integration
**WCAG 2.1 AA Implementation:**
- **Navigation Accessibility:** [Keyboard navigation, focus management]
- **Content Accessibility:** [Alt text strategy, heading structure]
- **Form Accessibility:** [Label association, error handling]
- **Media Accessibility:** [Captions, transcripts, audio descriptions]

**Government-Specific Accessibility:**
- **Section 508 Compliance:** [Federal accessibility requirements]
- **Plain Language:** [Content complexity and readability standards]
- **Multiple Format Support:** [Large print, audio, simplified versions]
- **Assistive Technology:** [Screen reader and voice recognition support]

## TECHNICAL IMPLEMENTATION SUPPORT

### Performance Optimization
**Content Organization for Speed:** (Based on technical requirements for performance)
- **Page Weight Management:** [How content grouping affects load times]
- **Image Optimization:** [Image usage and optimization strategy]
- **Content Caching:** [What content can be cached for performance]
- **Progressive Loading:** [How content loads incrementally]

### Backend Integration Support
**Content Management Integration:**
- **CMS Structure:** [How IA maps to content management system]
- **Workflow Integration:** [How IA supports approval processes]
- **Data Integration:** [How IA accommodates real-time data]
- **API Organization:** [How IA structure supports API design]

### Scalability Planning
**Growth Accommodation:**
- **Content Expansion:** [How IA handles new services and content]
- **User Growth:** [How IA performs with increased usage]
- **Feature Addition:** [How new functionality integrates with existing IA]
- **Maintenance Efficiency:** [How IA supports ongoing management]

## COMPLIANCE & GOVERNANCE

### Government Requirements Integration
**Transparency Requirements:**
- **Public Information Access:** [Required government information placement]
- **Contact Requirements:** [Government contact information standards]
- **Legal Notices:** [Required legal and policy information]
- **Accessibility Statements:** [Accessibility policy and contact information]

**Multi-Language Compliance:**
- **Primary Language:** [English language requirements]
- **Secondary Languages:** [Additional languages based on community needs]
- **Translation Standards:** [Quality and accuracy requirements]
- **Cultural Adaptation:** [Beyond translation - cultural considerations]

### Quality Assurance Framework
**Content Quality Standards:**
- **Accuracy Requirements:** [How content accuracy is maintained]
- **Currency Standards:** [How often content must be updated]
- **Consistency Guidelines:** [Style and format consistency across content]
- **User Testing:** [How IA effectiveness is validated with real users]

## STAKEHOLDER VALIDATION

### Review Process
**Stakeholder Review Structure:**
- **Citizen Testing:** [How IA is tested with real citizens]
- **Staff Validation:** [How staff workflows are validated against IA]
- **Technical Review:** [How IA supports technical requirements]
- **Compliance Review:** [How IA meets all regulatory requirements]

**Approval Criteria:**
- [ ] IA prioritizes citizen service delivery over government structure
- [ ] Navigation supports identified user groups and their tasks
- [ ] Content organization reduces cognitive load for citizens
- [ ] Accessibility requirements fully integrated into IA structure
- [ ] Technical requirements supported by IA organization
- [ ] Compliance requirements addressed throughout IA
- [ ] Staff workflows accommodated in IA design
- [ ] Scalability and maintenance considerations included
- [ ] Performance requirements supported by content organization
- [ ] Multi-device and responsive needs addressed

## USER JOURNEY PREPARATION

### Journey Mapping Support
**IA-to-Journey Connection:**
- **Primary User Paths:** [Most important citizen journeys through IA]
- **Alternative Pathways:** [Different ways to accomplish the same task]
- **Error Recovery:** [How IA helps when citizens get lost or confused]
- **Cross-Service Connections:** [How related services connect in IA]

**Journey Starting Points:**
- **Homepage Pathways:** [How different user types enter the system]
- **Direct Entry Points:** [Deep links and external referrals]
- **Search Entry:** [How search results lead to service completion]
- **Return User Paths:** [How returning users navigate efficiently]

## SUCCESS METRICS

### IA Effectiveness Measures
**User Success Metrics:**
- **Task Completion Rate:** [Percentage of users who complete intended tasks]
- **Time to Find Information:** [How quickly users locate needed information]
- **Navigation Efficiency:** [Number of clicks/pages to complete tasks]
- **User Satisfaction:** [Satisfaction scores for information findability]

**Technical Success Metrics:**
- **Page Load Performance:** [How IA organization affects performance]
- **Search Effectiveness:** [Search success and refinement rates]
- **Mobile Usage Patterns:** [How IA performs across devices]
- **Accessibility Compliance:** [Automated and manual accessibility testing results]

### Continuous Improvement
**IA Optimization Process:**
- **User Feedback Integration:** [How user feedback improves IA]
- **Analytics-Driven Changes:** [How usage data informs IA updates]
- **Content Performance:** [How content effectiveness drives IA refinements]
- **Technical Performance:** [How system performance influences IA decisions]

**INFORMATION ARCHITECTURE CONFIDENCE LEVEL:** [High/Medium/Low]
**READINESS FOR USER JOURNEY MAPPING:** [Ready/Needs Work/Blocked]
**CRITICAL IA DEPENDENCIES:** [Any dependencies that could affect IA implementation]
```

**IA DESIGN INSTRUCTIONS:**
1. Prioritize citizen service delivery over government organizational structure
2. Integrate accessibility requirements into every aspect of IA design
3. Ensure IA supports all technical requirements identified in previous analysis
4. Balance compliance requirements with user experience optimization
5. Design for scalability - IA must accommodate future services and content
6. Consider multi-device usage patterns from the start
7. Prepare IA structure to support detailed user journey mapping

---

## Usage Notes

### Before IA Design
- **Confirm technical requirements are complete** and stakeholder-approved
- **Review agency-specific content and compliance requirements**
- **Identify any existing content** that must be accommodated
- **Understand citizen user research** if available from previous projects

### During IA Design
- **Focus on citizen tasks, not government structure** - organize by what citizens need to do
- **Test navigation concepts** mentally by walking through common citizen scenarios
- **Balance depth vs. breadth** - avoid both too-shallow and too-deep information hierarchies
- **Consider content volume** - IA must work with realistic content loads

### After IA Design
- **Validate with representative citizens** if possible before finalizing
- **Review with technical stakeholders** to ensure implementability
- **Get compliance review** for government requirement coverage
- **Prepare for user journey mapping** by identifying key user paths

### Quality Standards
- **Citizen-centered organization** prioritizes service delivery over government structure
- **Accessibility integration** ensures WCAG 2.1 AA compliance throughout
- **Technical compatibility** supports all identified performance and integration requirements
- **Scalable design** accommodates future growth and changes

---

## File Naming Convention
Save IA design as: `Information-Architecture-[ProjectName]-[Date].md`

Example: `Information-Architecture-Denver-Parks-Portal-2024-03-24.md`
