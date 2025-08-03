# Information Architecture Development - Claude Prompt

## Context & Purpose
You are developing comprehensive information architecture for a government digital transformation project. Your role is to create citizen-centered site structure that optimizes government service delivery, ensures accessibility compliance, and supports efficient cross-departmental operations while addressing all stakeholder priorities identified in Week 1 discovery.

**Analysis Objectives:**
- Design citizen-centered information architecture based on Week 1 stakeholder insights
- Optimize government service discovery and completion workflows
- Ensure Section 508/WCAG 2.1 AA compliance throughout site structure
- Create scalable architecture supporting future service expansion
- Integrate technical constraints and capabilities from technical audit
- Support cross-departmental coordination and data sharing

## Required Inputs
Before beginning analysis, ensure you have:

1. **Week 1 Stakeholder Interview Synthesis** (citizen needs, service priorities, pain points)
2. **Technical Requirements Analysis** (platform capabilities, compliance requirements, performance constraints)
3. **Current Site Technical Audit** (existing structure analysis, performance baseline)
4. **Government Agency Context:**
   - Agency type and primary service focus
   - Department structure and service distribution
   - Current website traffic patterns and peak usage
   - Cross-departmental integration requirements
   - Budget parameters for implementation

## Information Architecture Framework

### Pre-Analysis Setup
**Discovery Foundation Validation:**
- [ ] **Stakeholder priorities** documented and prioritized by citizen impact
- [ ] **Service delivery workflows** mapped from citizen and staff interviews
- [ ] **Technical constraints** understood from audit and requirements analysis
- [ ] **Compliance requirements** identified (Section 508, state/local standards)
- [ ] **Content inventory** completed for existing site structure
- [ ] **User mental models** documented from stakeholder feedback

**Government Context Integration:**
- [ ] **Departmental service boundaries** understood and mapped
- [ ] **Inter-agency coordination** requirements identified
- [ ] **Public information access** mandates documented
- [ ] **Emergency service protocols** integrated into structure planning
- [ ] **Multilingual requirements** assessed and planned
- [ ] **Mobile-first usage patterns** validated from technical audit

## Analysis Template

Generate comprehensive IA documentation using this exact structure:

### INFORMATION ARCHITECTURE OVERVIEW
**Government Agency:** [Full agency name and jurisdiction level]  
**IA Development Date:** [Current analysis date]  
**Stakeholder Foundation:** [Week 1 discovery completion date]  
**Technical Foundation:** [Technical requirements completion date]  
**Implementation Target:** [Phase 2 design integration timeline]

**Architecture Scope:**
- **Primary Services Covered:** [Core government services included in IA]
- **User Types Supported:** [All user categories from stakeholder analysis]
- **Content Volume:** [Estimated pages/content items for structure]
- **Integration Requirements:** [External systems and departments]

### CITIZEN-CENTERED CONTENT STRATEGY

#### Service Discovery Optimization
**Primary Citizen Pathways:**
- **[Service Category]:** [How citizens naturally group and seek these services]
  - **Mental Model Rationale:** [Why citizens expect this grouping based on stakeholder insights]
  - **Discovery Method:** [How citizens typically learn about or search for these services]
  - **Completion Workflow:** [End-to-end process from awareness to service completion]
  - **Cross-Service Connections:** [Related services citizens often need simultaneously]
  - **Support Requirements:** [Help, documentation, and assistance needs]

- **[Service Category]:** [How citizens naturally group and seek these services]
  - **Mental Model Rationale:** [Why citizens expect this grouping based on stakeholder insights]
  - **Discovery Method:** [How citizens typically learn about or search for these services]  
  - **Completion Workflow:** [End-to-end process from awareness to service completion]
  - **Cross-Service Connections:** [Related services citizens often need simultaneously]
  - **Support Requirements:** [Help, documentation, and assistance needs]

**Citizen Journey Integration:**
- **New Citizens:** [IA structure supporting first-time government interaction]
- **Returning Citizens:** [Architecture enabling efficient service updates and renewals]
- **Emergency Situations:** [Priority access and clear pathways for urgent needs]
- **Business Users:** [Separate but integrated pathways for business services]
- **Multi-Language Users:** [Content organization supporting language accessibility]

#### Content Hierarchy Strategy
**Level 1 (Primary Navigation):**
```
[Primary Category Name] - [Rationale from citizen mental models]
├── Service subcategory based on citizen task groupings
├── Information subcategory based on transparency requirements  
├── Support subcategory based on citizen assistance needs
└── Department subcategory based on government structure (where citizen-beneficial)
```

**Level 2-3 Content Organization:**
```
Service Category > Specific Service > Service Completion
├── Service Overview (what, why, eligibility)
├── Requirements & Process (how, when, where)
├── Forms & Applications (digital service delivery)
├── Status & Follow-up (tracking and next steps)
└── Help & Support (assistance and troubleshooting)
```

**Content Governance Structure:**
- **Department Ownership:** [Which departments own which content areas]
- **Update Responsibilities:** [Content maintenance and currency requirements]
- **Quality Standards:** [Content accessibility, plain language, accuracy standards]
- **Review Cycles:** [Regular content validation and improvement processes]

### NAVIGATION ARCHITECTURE DESIGN

#### Primary Navigation Strategy
**Top-Level Navigation Rationale:**
1. **[Navigation Item]:** [Citizen service need this addresses]
   - **Scope:** [Services and content included]
   - **Target Users:** [Primary and secondary user types]
   - **Usage Patterns:** [When and how citizens access this section]
   - **Mobile Considerations:** [Mobile-specific navigation needs]
   - **Accessibility Features:** [Screen reader, keyboard navigation requirements]

2. **[Navigation Item]:** [Citizen service need this addresses]
   - **Scope:** [Services and content included]
   - **Target Users:** [Primary and secondary user types]
   - **Usage Patterns:** [When and how citizens access this section]
   - **Mobile Considerations:** [Mobile-specific navigation needs]
   - **Accessibility Features:** [Screen reader, keyboard navigation requirements]

3. **[Navigation Item]:** [Citizen service need this addresses]
   - **Scope:** [Services and content included]
   - **Target Users:** [Primary and secondary user types]
   - **Usage Patterns:** [When and how citizens access this section]
   - **Mobile Considerations:** [Mobile-specific navigation needs]
   - **Accessibility Features:** [Screen reader, keyboard navigation requirements]

#### Secondary Navigation Systems
**Utility Navigation:**
- **Account/Login:** [Citizen account access and management]
- **Search:** [Government content and service search functionality]
- **Language Options:** [Multi-language content access]
- **Accessibility Tools:** [Text size, contrast, screen reader optimization]
- **Emergency Information:** [Crisis services and urgent information access]

**Footer Navigation:**
- **Transparency Information:** [Required government transparency content]
- **Legal Information:** [Privacy, terms, accessibility statements]
- **Contact Information:** [Department contacts, office locations, hours]
- **Government Structure:** [About agency, leadership, organizational information]

**Breadcrumb Strategy:**
- **Service Completion Support:** [Help citizens understand their location in complex processes]
- **Content Relationship Clarity:** [Show content connections and hierarchy]
- **Back Navigation:** [Easy return to previous steps or sections]

#### Mobile Navigation Optimization
**Mobile-First Considerations:**
- **Touch Target Sizing:** [Navigation elements sized for finger interaction]
- **Thumb Navigation Zones:** [Primary actions within easy thumb reach]
- **Progressive Disclosure:** [Revealing information hierarchy gradually]
- **Offline Access Planning:** [Critical service information available offline]

**Responsive Navigation Patterns:**
- **Hamburger Menu Strategy:** [When and how to collapse navigation]
- **Tab Bar Navigation:** [Bottom navigation for frequent actions]
- **Search Prominence:** [Mobile search visibility and functionality]

### ACCESSIBILITY COMPLIANCE ARCHITECTURE

#### WCAG 2.1 AA Integration
**Perceivable Architecture:**
- **Color Independence:** [Navigation and content organization not dependent on color alone]
- **Text Scalability:** [IA structure maintains usability at 200% text size]
- **Alternative Content:** [Structure accommodates alt text, captions, transcripts]
- **Contrast Requirements:** [Navigation elements meet contrast standards]

**Operable Architecture:**
- **Keyboard Navigation:** [Complete site navigation possible without mouse]
- **Focus Management:** [Logical focus order throughout complex structures]
- **Timing Considerations:** [No time limits on government service completion]
- **Seizure Prevention:** [Content organization avoids flashing or animation triggers]

**Understandable Architecture:**
- **Consistent Navigation:** [Predictable navigation patterns throughout site]
- **Clear Labeling:** [Navigation and content labels use plain language]
- **Error Prevention:** [IA structure reduces user errors in service completion]
- **Help Integration:** [Contextual help available throughout site structure]

**Robust Architecture:**
- **Assistive Technology:** [Structure compatible with screen readers, voice navigation]
- **Future Compatibility:** [IA approach adaptable to new accessibility technologies]
- **Standards Compliance:** [Architecture meets current and emerging accessibility standards]

#### Section 508 Government Requirements
**Electronic Accessibility:**
- **Federal Compliance:** [If federal agency, full Section 508 compliance integration]
- **State Standards:** [State-specific accessibility requirements]
- **Local Requirements:** [Municipal accessibility standards and policies]

**Document Accessibility Integration:**
- **PDF Strategy:** [How PDFs integrate with overall IA structure]
- **Form Accessibility:** [Government forms integrated into accessible workflows]
- **Media Strategy:** [Video and audio content integration with accessibility]

### GOVERNMENT SERVICE DELIVERY OPTIMIZATION

#### Cross-Departmental Integration
**Service Integration Points:**
- **[Department A] + [Department B]:** [Services requiring inter-departmental coordination]
  - **Citizen Journey Impact:** [How integration improves citizen experience]
  - **Data Sharing Requirements:** [Information that must flow between departments]
  - **Workflow Coordination:** [Staff processes requiring coordination]
  - **IA Structure Support:** [How site architecture facilitates integration]

- **[Department C] + [Department D]:** [Services requiring inter-departmental coordination]
  - **Citizen Journey Impact:** [How integration improves citizen experience]
  - **Data Sharing Requirements:** [Information that must flow between departments]
  - **Workflow Coordination:** [Staff processes requiring coordination]
  - **IA Structure Support:** [How site architecture facilitates integration]

**Shared Service Architecture:**
- **Common Forms:** [Forms used across multiple departments]
- **Shared Authentication:** [Single sign-on for citizen accounts across services]
- **Document Sharing:** [Citizens providing documents once for multiple services]
- **Status Integration:** [Unified status tracking across departments]

#### Emergency and Priority Service Architecture
**Crisis Communication Structure:**
- **Emergency Alerts:** [How urgent information integrates with normal site structure]
- **Priority Service Access:** [Fast-track navigation for emergency services]
- **Alternative Access Methods:** [IA structure when normal access is disrupted]

**High-Volume Service Optimization:**
- **Peak Usage Planning:** [IA structure supporting traffic spikes]
- **Load Distribution:** [Content organization supporting performance under load]
- **Service Prioritization:** [Critical vs. routine service access hierarchy]

### TECHNICAL INTEGRATION REQUIREMENTS

#### Platform Architecture Alignment
**Content Management Integration:**
- **CMS Compatibility:** [IA structure fitting technical platform capabilities]
- **Content Workflow:** [How content creation and updates align with IA]
- **Multi-Site Management:** [IA approach for agencies with multiple sites]
- **Version Control:** [Content versioning and approval workflows]

**Search and Discovery Integration:**
- **Site Search Strategy:** [How search integrates with navigation architecture]
- **External Search Optimization:** [SEO strategy supporting government service discovery]
- **Content Tagging:** [Metadata strategy supporting content discovery]

#### Performance and Scale Considerations
**Load Time Optimization:**
- **Content Delivery:** [IA structure supporting fast content access]
- **Image and Media Strategy:** [How multimedia content integrates with architecture]
- **Progressive Loading:** [Content prioritization for performance]

**Scalability Planning:**
- **Growth Accommodation:** [IA structure expandable for new services]
- **Traffic Scaling:** [Architecture supporting increased usage]
- **Content Volume:** [Structure handling growing content inventory]

### STAKEHOLDER ALIGNMENT VALIDATION

#### Week 1 Discovery Integration
**Citizen Stakeholder Validation:**
- **[Key Citizen Need]:** [How IA structure addresses this stakeholder priority]
  - **Discovery Source:** [Which stakeholder interviews identified this need]
  - **IA Solution:** [Specific architecture decisions addressing the need]
  - **Success Measurement:** [How to validate that architecture meets the need]

- **[Key Citizen Need]:** [How IA structure addresses this stakeholder priority]
  - **Discovery Source:** [Which stakeholder interviews identified this need]
  - **IA Solution:** [Specific architecture decisions addressing the need]
  - **Success Measurement:** [How to validate that architecture meets the need]

**Staff Stakeholder Validation:**
- **[Staff Workflow Need]:** [How IA supports internal operations]
  - **Operational Impact:** [How architecture improves staff efficiency]
  - **Content Management:** [How staff will maintain and update content]
  - **Citizen Support:** [How architecture helps staff assist citizens]

**Executive Stakeholder Validation:**
- **[Strategic Priority]:** [How IA advances agency strategic goals]
  - **Service Delivery:** [Architecture impact on government service mission]
  - **Efficiency Gains:** [Operational improvements enabled by structure]
  - **Compliance Achievement:** [How architecture ensures regulatory compliance]

#### Technical Stakeholder Integration
**IT Requirements Alignment:**
- **[Technical Constraint]:** [How IA accommodates technical limitations]
- **[Integration Need]:** [Architecture decisions supporting technical requirements]
- **[Security Requirement]:** [IA structure supporting security and privacy needs]

### IMPLEMENTATION PLANNING

#### Phase 2 Design Integration
**Design Team Handoff Requirements:**
1. **Visual Design Foundation:** [IA decisions that will guide visual design]
   - **Navigation Design Specs:** [Specific requirements for navigation components]
   - **Content Layout Requirements:** [How content hierarchy affects visual design]
   - **Responsive Design Guidelines:** [Mobile-first architecture implications]

2. **User Experience Design Foundation:** [IA decisions informing UX design]
   - **User Flow Integration:** [How site architecture supports user journeys]
   - **Interaction Design Requirements:** [IA elements requiring specific interactions]
   - **Accessibility Design Standards:** [Compliance requirements affecting UX design]

3. **Content Strategy Implementation:** [IA requirements for content development]
   - **Content Creation Guidelines:** [Content requirements based on architecture]
   - **Content Migration Planning:** [How existing content fits new structure]
   - **Content Governance Implementation:** [Ongoing content management processes]

#### Development Implementation Planning
**Technical Development Requirements:**
- **Database Architecture:** [Content structure requirements for development]
- **URL Structure:** [SEO-friendly URL patterns based on IA]
- **Navigation Implementation:** [Technical requirements for navigation functionality]
- **Search Implementation:** [Search functionality requirements]

**Quality Assurance Integration:**
- **IA Testing Requirements:** [How to validate that development matches IA]
- **User Testing Integration:** [Testing IA decisions with real users]
- **Accessibility Testing:** [Compliance validation throughout development]

### QUALITY ASSURANCE STANDARDS

#### IA Completeness Verification
- [ ] All citizen service needs from Week 1 stakeholder analysis addressed in IA structure
- [ ] Navigation architecture supports all identified user types and workflows
- [ ] Content hierarchy enables efficient service discovery and completion
- [ ] Cross-departmental integration requirements incorporated into structure
- [ ] Emergency and priority service access clearly established in architecture
- [ ] Mobile-first approach validated throughout all IA decisions

#### Government Compliance Confirmation
- [ ] Section 508 accessibility requirements integrated throughout IA structure
- [ ] WCAG 2.1 AA compliance validated for all navigation and content organization
- [ ] Government transparency requirements accommodated in content strategy
- [ ] Multi-language accessibility planned and integrated where required
- [ ] Plain language principles applied to all navigation and content labeling

#### Technical Integration Validation
- [ ] IA structure compatible with technical requirements and platform capabilities
- [ ] Performance requirements addressed in content organization and structure
- [ ] Security and privacy requirements integrated into architecture planning
- [ ] Scalability considerations incorporated for future growth and service expansion
- [ ] Content management workflow aligned with government operational needs

#### Stakeholder Alignment Verification
- [ ] All Week 1 stakeholder priorities directly addressed in IA decisions
- [ ] Citizen mental models and service expectations reflected in content organization
- [ ] Staff operational needs supported through architecture and content strategy
- [ ] Executive strategic goals advanced through IA structure and service integration
- [ ] Technical stakeholder constraints and requirements accommodated throughout

## Integration with Week 1 Foundation

### Discovery Synthesis Integration
- [ ] **Citizen priorities** directly inform primary navigation and content hierarchy
- [ ] **Service delivery challenges** addressed through IA structure and workflow integration
- [ ] **Accessibility gaps** resolved through comprehensive compliance architecture
- [ ] **Cross-departmental needs** accommodated through integration planning

### Week 2 Strategy Foundation
- [ ] **IA structure** ready for user journey mapping and optimization
- [ ] **Content strategy** prepared for detailed user experience design
- [ ] **Navigation architecture** validated for technical implementation planning
- [ ] **Accessibility framework** established for comprehensive compliance validation

---

**Quality Guarantee:** This information architecture framework ensures comprehensive citizen-centered structure that advances government service delivery mission while maintaining strict accessibility compliance and supporting all stakeholder priorities identified in discovery phase.
