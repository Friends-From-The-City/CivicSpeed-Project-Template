# Claude Prompt: User Journey Mapper

## Purpose
This prompt creates detailed user journeys for government digital transformation projects using the CivicSpeed methodology. Transforms information architecture and technical requirements into comprehensive user experience maps that guide Phase 2 design and development.

## How to Use
1. **Complete IA design and technical requirements first** using previous analysis tools
2. **Copy the prompt below** into a new Claude conversation
3. **Paste IA document and technical requirements** as input
4. **Review user journeys** for completeness and government compliance
5. **Validate with stakeholders** representing each user type
6. **Use output to guide** Phase 2 design system and service implementations

---

## THE CLAUDE PROMPT
**Copy everything from this line down to the end of the code block into Claude:**

```
You are creating comprehensive user journeys for a government digital transformation project using the CivicSpeed methodology. Map detailed user experiences across all user types, touchpoints, and scenarios to guide Phase 2 design and development while ensuring government compliance and citizen-centered service delivery.

**PROJECT CONTEXT:**
- Agency: [AGENCY_NAME]
- Project: [PROJECT_NAME]
- Phase: Week 2 User Journey Development (Final Phase 1 deliverable)
- Methodology: CivicSpeed AI-Accelerated Government Digital Transformation
- Focus: Multi-user-type journey mapping for government service delivery

**INFORMATION ARCHITECTURE & REQUIREMENTS INPUT:**
[PASTE INFORMATION ARCHITECTURE DOCUMENT HERE]
[PASTE TECHNICAL REQUIREMENTS DOCUMENT HERE]

**USER JOURNEY MAPPING FRAMEWORK:**
Create journeys across 5 critical user types and multiple scenarios for government digital services:

## JOURNEY MAPPING METHODOLOGY

### 1. GOVERNMENT-SPECIFIC USER TYPES
**Primary User Categories:**
- **New Citizens** (First-time service users)
- **Returning Citizens** (Familiar with agency services)
- **Business Users** (Organizations interacting with government)
- **Emergency/Urgent Access** (Time-sensitive service needs)
- **Staff/Administrative** (Internal government users)

### 2. CITIZEN-CENTERED DESIGN PRINCIPLES
**Service Delivery Focus:**
- Minimize citizen effort and cognitive load
- Provide clear progress indicators and expectations
- Offer multiple pathways to accomplish tasks
- Support various accessibility needs and preferences

**Government Context Integration:**
- Incorporate compliance and approval workflows
- Address transparency and communication requirements
- Support multi-channel service delivery
- Accommodate varying levels of digital literacy

### 3. COMPREHENSIVE JOURNEY SCOPE
**Journey Coverage:**
- Pre-service awareness and discovery
- Service initiation and authentication
- Information gathering and form completion
- Submission and processing
- Status tracking and communication
- Service completion and follow-up

**OUTPUT FORMAT:**
Present user journeys using this exact structure:

## EXECUTIVE SUMMARY
**Journey Scope:** [Number and types of user journeys mapped]
**Critical User Paths:** [Top 3 most important citizen journeys]
**Complexity Assessment:** [Simple/Moderate/Complex journey complexity with rationale]
**Design Priority Recommendations:** [Which journeys should be designed first in Phase 2]
**Success Metrics Framework:** [How journey effectiveness will be measured]

## USER JOURNEY: NEW CITIZEN
**User Profile:**
- **Demographics:** [Typical new user characteristics based on technical requirements]
- **Digital Literacy:** [Expected comfort level with online services]
- **Primary Needs:** [What brings them to the service for the first time]
- **Key Concerns:** [Barriers and anxieties about using government services]
- **Success Definition:** [What constitutes a successful experience for this user]

### Discovery & Awareness Phase
**Step 1: Need Recognition**
- **Trigger:** [What event/situation brings user to seek this service]
- **Emotional State:** [User feelings and mindset at journey start]
- **Information Needs:** [What user needs to know before starting]
- **Current Challenges:** [Pain points with existing service access methods]

**Step 2: Service Discovery**
- **Discovery Channels:** [How user finds the digital service - web search, referral, etc.]
- **Landing Experience:** [First interaction with website/application]
- **Information Architecture Touchpoints:** [Which IA elements user encounters]
- **Decision Factors:** [What convinces user to proceed vs. seek alternative channels]

**Step 3: Service Understanding**
- **Service Overview:** [How user learns what the service offers]
- **Eligibility Verification:** [How user determines if they qualify]
- **Requirements Gathering:** [How user learns what documents/information needed]
- **Timeline Expectations:** [How user learns about processing time and next steps]

**Touchpoints:** [Digital platform, phone support, in-person options]
**Pain Points:** [Confusion about eligibility, unclear requirements, intimidating language]
**Opportunities:** [Clear service descriptions, eligibility checkers, preparation checklists]
**Technical Requirements Impact:** [How technical requirements support this phase]

### Service Initiation Phase
**Step 4: Account Creation/Access**
- **Authentication Method:** [How user creates account or logs in]
- **Identity Verification:** [What identity verification is required]
- **Accessibility Accommodations:** [How accessibility needs are addressed]
- **Privacy Understanding:** [How user learns about data collection and use]

**Step 5: Application/Request Initiation**
- **Service Selection:** [How user chooses specific service or form]
- **Process Overview:** [How user understands multi-step process]
- **Progress Tracking Setup:** [How user will track application status]
- **Save/Resume Functionality:** [How user can save progress and return later]

**Touchpoints:** [Login system, help documentation, customer service]
**Pain Points:** [Complex authentication, unclear data privacy, overwhelming process]
**Opportunities:** [Streamlined registration, clear privacy notices, progress indicators]
**Technical Requirements Impact:** [Security requirements, performance needs, accessibility features]

### Information Gathering & Completion Phase
**Step 6: Form/Application Completion**
- **Information Collection:** [What data user must provide and how]
- **Document Upload:** [What documents required and upload process]
- **Validation & Error Handling:** [How errors are identified and corrected]
- **Help & Support Access:** [How user gets help when stuck]

**Step 7: Review & Submission**
- **Application Review:** [How user reviews completed application]
- **Correction Process:** [How user makes changes before submission]
- **Final Confirmation:** [What user sees/receives upon submission]
- **Next Steps Communication:** [How user learns what happens next]

**Touchpoints:** [Application forms, file upload system, help chat/phone]
**Pain Points:** [Complex forms, unclear field requirements, file upload failures]
**Opportunities:** [Smart forms with validation, clear help text, multiple save points]
**Technical Requirements Impact:** [Form design requirements, file handling, error management]

### Processing & Communication Phase
**Step 8: Application Processing**
- **Status Tracking:** [How user monitors application progress]
- **Communication Touchpoints:** [When and how agency communicates with user]
- **Additional Information Requests:** [How additional documents/info are requested]
- **Processing Timeline:** [How user understands current status and expected timeline]

**Step 9: Decision Communication**
- **Decision Notification:** [How user learns about approval/denial/additional requirements]
- **Next Steps Guidance:** [What user needs to do based on decision]
- **Appeal/Correction Process:** [How user can address issues or appeal decisions]
- **Service Delivery:** [How approved services are delivered to user]

**Touchpoints:** [Email notifications, portal dashboard, phone calls, mail]
**Pain Points:** [Lack of status updates, unclear communication, long wait times]
**Opportunities:** [Proactive status updates, clear timelines, multiple notification preferences]
**Technical Requirements Impact:** [Notification systems, status tracking, communication preferences]

### Service Completion & Follow-up Phase
**Step 10: Service Delivery & Usage**
- **Service Access:** [How user accesses approved services or benefits]
- **Service Understanding:** [How user learns to use approved services]
- **Ongoing Requirements:** [Any ongoing obligations or renewal requirements]
- **Support Access:** [How user gets help with using approved services]

**Step 11: Follow-up & Renewal**
- **Satisfaction Feedback:** [How user provides feedback on experience]
- **Service Updates:** [How user stays informed about service changes]
- **Renewal Process:** [How user renews or maintains services]
- **Related Services:** [How user discovers other relevant services]

**Touchpoints:** [Service delivery systems, renewal notifications, feedback forms]
**Pain Points:** [Unclear service usage, missed renewal deadlines, poor follow-up]
**Opportunities:** [Clear service instructions, automated renewal reminders, proactive communication]
**Technical Requirements Impact:** [Service delivery systems, renewal automation, feedback collection]

## USER JOURNEY: RETURNING CITIZEN
**User Profile:**
- **Experience Level:** [Previous experience with agency services]
- **Familiarity:** [Comfort level with existing processes and systems]
- **Efficiency Expectations:** [Expectation for faster, streamlined experience]
- **Change Adaptation:** [How user adapts to new digital processes]

### Streamlined Service Access
**Returning User Advantages:**
- **Saved Information:** [How previous data speeds current application]
- **Process Familiarity:** [How previous experience reduces cognitive load]
- **Expedited Pathways:** [Special processes for returning users]
- **Historical Access:** [How user accesses previous applications/services]

**Key Journey Differences from New Users:**
- **Shortened Discovery:** [Faster service identification and understanding]
- **Simplified Authentication:** [Existing account access and verification]
- **Prefilled Information:** [Reduced data entry through saved information]
- **Expedited Processing:** [Faster review based on history and trust]

**Touchpoints:** [Returning user portal, saved application data, expedited queues]
**Pain Points:** [Outdated saved information, changed requirements, process modifications]
**Opportunities:** [Smart defaults, change notifications, upgrade paths]
**Technical Requirements Impact:** [Data retention, user history, personalization features]

## USER JOURNEY: BUSINESS USER
**User Profile:**
- **Organization Type:** [Small business, large corporation, nonprofit, etc.]
- **Regulatory Context:** [Business compliance and reporting requirements]
- **Volume Considerations:** [Single application vs. bulk/recurring submissions]
- **Delegation Needs:** [Multiple staff members managing applications]

### Business-Specific Requirements
**Organizational Processes:**
- **Multi-User Access:** [How multiple staff access and manage applications]
- **Approval Workflows:** [Internal business approval before government submission]
- **Bulk Processing:** [How multiple applications are managed efficiently]
- **Record Keeping:** [How business maintains records for compliance/audit]

**Compliance Integration:**
- **Business Documentation:** [Additional business verification requirements]
- **Regulatory Reporting:** [How service connects to other business compliance]
- **Tax Integration:** [How service affects business tax obligations]
- **Ongoing Monitoring:** [How business maintains compliance over time]

**Touchpoints:** [Business portal, bulk upload systems, account management, compliance reporting]
**Pain Points:** [Complex business verification, limited bulk processing, poor delegation tools]
**Opportunities:** [Business-specific interfaces, delegation management, compliance integration]
**Technical Requirements Impact:** [Multi-user access, bulk processing, business verification systems]

## USER JOURNEY: EMERGENCY/URGENT ACCESS
**User Profile:**
- **Urgency Level:** [Time-sensitive situations requiring immediate service]
- **Stress Context:** [High-stress situations affecting user decision-making]
- **Information Limitations:** [May not have all typical required information]
- **Alternative Needs:** [Requiring expedited or alternative processes]

### Expedited Service Pathways
**Emergency Processes:**
- **Priority Identification:** [How urgent cases are identified and prioritized]
- **Expedited Review:** [Faster processing for emergency situations]
- **Alternative Documentation:** [Accepting alternative documents for urgent cases]
- **Immediate Support:** [Enhanced customer service for emergency situations]

**Crisis Communication:**
- **Clear Urgency Indicators:** [How users identify emergency pathways]
- **Realistic Timeline Communication:** [Clear expectations for emergency processing]
- **Status Priority:** [Enhanced tracking and communication for urgent cases]
- **Escalation Pathways:** [How to escalate when emergency process insufficient]

**Touchpoints:** [Emergency hotlines, priority processing queues, expedited review teams]
**Pain Points:** [Unclear emergency criteria, normal processing times, inadequate crisis support]
**Opportunities:** [Clear emergency pathways, priority processing, enhanced communication]
**Technical Requirements Impact:** [Priority flagging, expedited workflows, emergency notification systems]

## USER JOURNEY: STAFF/ADMINISTRATIVE
**User Profile:**
- **Role Types:** [Customer service, application reviewers, managers, IT staff]
- **Daily Workflow:** [How digital service fits into daily work responsibilities]
- **Training Needs:** [Support needed to effectively use new systems]
- **Efficiency Goals:** [How new system improves staff productivity]

### Internal Process Flows
**Application Review Workflow:**
- **Application Receipt:** [How staff receive and prioritize new applications]
- **Review Process:** [Step-by-step application evaluation procedures]
- **Decision Making:** [How approval/denial decisions are made and documented]
- **Communication Management:** [How staff communicate with applicants]

**Administrative Functions:**
- **User Support:** [How staff provide customer service and technical support]
- **System Administration:** [How staff manage system settings and user accounts]
- **Reporting & Analytics:** [How staff generate reports and monitor performance]
- **Quality Assurance:** [How staff ensure process quality and compliance]

**Collaboration & Handoffs:**
- **Inter-Department Coordination:** [How different departments work together]
- **Supervisor Review:** [How supervisory approval processes work]
- **External Coordination:** [How staff coordinate with other agencies or organizations]
- **Documentation Requirements:** [How staff maintain required records and documentation]

**Touchpoints:** [Admin dashboard, review interfaces, communication tools, reporting systems]
**Pain Points:** [Complex review interfaces, poor communication tools, manual processes]
**Opportunities:** [Streamlined workflows, integrated communication, automated reporting]
**Technical Requirements Impact:** [Admin interfaces, workflow automation, reporting capabilities]

## CROSS-JOURNEY ANALYSIS

### Common Touchpoints
**Shared Experience Elements:**
- **Landing Page Experience:** [How all user types first encounter the service]
- **Help & Support Systems:** [Common support needs across user types]
- **Status Tracking:** [Universal need for application status visibility]
- **Communication Preferences:** [How different users prefer to receive updates]

### Journey Intersections
**Multi-User Scenarios:**
- **Business Representatives:** [When business users need to help individual citizens]
- **Family/Caregiver Assistance:** [When citizens need help from others]
- **Staff Customer Service:** [When citizens need staff assistance during digital processes]
- **Emergency Escalation:** [When normal processes need to become emergency processes]

### Technical Architecture Implications
**System Requirements from Journey Analysis:**
- **User Management:** [How different user types are authenticated and authorized]
- **Data Flow:** [How information moves between user types and system components]
- **Notification Systems:** [How different communication needs are met]
- **Integration Points:** [Where journeys require system integrations]

## SUCCESS METRICS & VALIDATION

### Journey Effectiveness Metrics
**User Success Indicators:**
- **Task Completion Rate:** [Percentage of users who successfully complete their intended task]
- **Time to Completion:** [How long each journey type takes from start to finish]
- **Error/Abandonment Points:** [Where users get stuck or give up]
- **User Satisfaction Scores:** [Satisfaction ratings for each journey type]

**Operational Efficiency Metrics:**
- **Staff Productivity:** [How new system affects staff efficiency]
- **Processing Time:** [How quickly applications move through review]
- **Support Ticket Volume:** [How much customer service support is needed]
- **Error Reduction:** [Decrease in errors and rework]

### Validation Process
**User Testing Requirements:**
- **Representative User Testing:** [Testing with actual members of each user type]
- **Accessibility Testing:** [Validation with users requiring accommodations]
- **Stress Testing:** [How journeys perform under emergency/urgent conditions]
- **Cross-Device Testing:** [How journeys work across different devices and contexts]

**Stakeholder Validation:**
- **Citizen Validation:** [How citizen stakeholders review and approve journeys]
- **Staff Validation:** [How operational stakeholders validate internal workflows]
- **Technical Validation:** [How technical stakeholders confirm implementability]
- **Compliance Validation:** [How compliance stakeholders verify regulatory adherence]

## PHASE 2 DESIGN IMPLICATIONS

### Design System Requirements
**Component Needs from Journey Analysis:**
- **Form Components:** [Complex form interactions identified in journeys]
- **Navigation Components:** [Navigation patterns needed across journeys]
- **Communication Components:** [Status updates, notifications, help systems]
- **Accessibility Components:** [Specific accessibility needs from journey analysis]

### Service Implementation Priorities
**Development Sequence Recommendations:**
1. **[Priority Service 1]:** [Rationale based on journey analysis and user impact]
2. **[Priority Service 2]:** [Rationale based on complexity and dependencies]
3. **[Priority Service 3]:** [Rationale based on compliance requirements and risk]

### Integration Requirements
**System Connections from Journey Analysis:**
- **Authentication Systems:** [User login and verification requirements]
- **Notification Systems:** [Communication and update delivery requirements]
- **Document Management:** [File upload, storage, and retrieval requirements]
- **Status Tracking:** [Real-time status and progress monitoring requirements]

## RISK ASSESSMENT

### Journey Risk Analysis
**High-Risk Journey Points:**
1. **[Risk Point 1]:** [Description, impact, mitigation strategy]
2. **[Risk Point 2]:** [Description, impact, mitigation strategy]
3. **[Risk Point 3]:** [Description, impact, mitigation strategy]

**User Experience Risks:**
- **Digital Divide Considerations:** [How journeys accommodate varying digital literacy]
- **Accessibility Barriers:** [Potential barriers for users with disabilities]
- **Language/Cultural Barriers:** [Challenges for non-English speakers or cultural differences]
- **Technical Failure Points:** [How journeys handle system outages or technical problems]

### Mitigation Strategies
**Design Solutions:**
- **Alternative Pathways:** [Multiple ways to accomplish the same task]
- **Progressive Enhancement:** [Basic functionality works, enhanced features add value]
- **Graceful Degradation:** [How system handles failures and limitations]
- **Human Backup Systems:** [When and how human support supplements digital processes]

## IMPLEMENTATION ROADMAP

### Phase 2 Journey Implementation
**Week 3-4: Foundation**
- **Core journey infrastructure:** [Basic user flows and navigation]
- **Authentication systems:** [User login and account management]
- **Basic form systems:** [Simple information collection]

**Week 5-6: Service Implementation**
- **Priority service journeys:** [Most critical user paths]
- **Status tracking systems:** [Application progress monitoring]
- **Communication systems:** [User notifications and updates]

**Week 7-8: Enhancement & Testing**
- **Advanced journey features:** [Personalization, saved progress, etc.]
- **Cross-journey integration:** [How different user types interact]
- **Comprehensive testing:** [All journey types and scenarios]

### Success Validation Checkpoints
**Journey Completion Criteria:**
- [ ] All user types have complete, tested journeys
- [ ] Cross-journey interactions identified and designed
- [ ] Accessibility requirements integrated throughout all journeys
- [ ] Staff workflows fully integrated with citizen journeys
- [ ] Emergency/urgent pathways clearly defined and tested
- [ ] Success metrics defined and measurable
- [ ] Phase 2 design implications clearly documented
- [ ] All compliance requirements addressed in journey design

**USER JOURNEY CONFIDENCE LEVEL:** [High/Medium/Low]
**READINESS FOR PHASE 2 DESIGN:** [Ready/Needs Work/Blocked]
**CRITICAL JOURNEY DEPENDENCIES:** [Any dependencies that could affect implementation]
```

**USER JOURNEY MAPPING INSTRUCTIONS:**
1. Map comprehensive journeys for all user types - don't focus only on citizens
2. Include pre-service and post-service phases for complete experience understanding
3. Identify specific touchpoints where technical requirements enable better experiences
4. Address government-specific needs like compliance, transparency, and multi-level approval
5. Plan for accessibility, multiple languages, and varying digital literacy levels
6. Connect journeys to Phase 2 design priorities and implementation sequence
7. Include concrete success metrics that support the 95% stakeholder satisfaction standard

---

## Usage Notes

### Before Journey Mapping
- **Confirm IA and technical requirements are complete** and stakeholder-approved
- **Review any existing user research** or journey maps from the agency
- **Identify specific user types** beyond the standard categories if needed
- **Understand peak usage scenarios** and emergency/crisis situations

### During Journey Mapping
- **Focus on citizen effort reduction** - minimize steps and cognitive load
- **Map emotional journey** alongside functional steps - government services often involve stress
- **Include failure scenarios** - what happens when things go wrong
- **Consider offline touchpoints** - how digital integrates with phone/in-person service

### After Journey Mapping
- **Validate with real users** from each user type if possible
- **Review with operational staff** who will implement these workflows
- **Get compliance review** for any regulatory requirements
- **Prioritize implementation order** based on impact and complexity

### Quality Standards
- **Citizen-centered design** reduces effort and increases satisfaction
- **Government compliance** ensures all regulatory requirements addressed
- **Multi-channel integration** supports citizens who need multiple service channels
- **Staff workflow optimization** improves operational efficiency and service quality

---

## File Naming Convention
Save user journeys as: `User-Journeys-[ProjectName]-[Date].md`

Example: `User-Journeys-Denver-Parks-Portal-2024-03-25.md`
