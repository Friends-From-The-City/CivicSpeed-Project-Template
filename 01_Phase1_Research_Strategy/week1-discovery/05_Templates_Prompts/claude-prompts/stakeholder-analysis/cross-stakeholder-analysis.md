# Claude Prompt: Cross-Stakeholder Synthesizer

## Purpose
This prompt synthesizes individual stakeholder interview analyses into unified strategic insights for government digital transformation projects. Creates consensus areas, resolves conflicts, and generates actionable requirements for Week 2 strategy development.

## How to Use
1. **Complete all individual interview analyses first** using the Individual Interview Analyzer
2. **Copy the prompt below** into a new Claude conversation
3. **Paste all individual analyses** as input (typically 4-8 stakeholder analyses)
4. **Review synthesis outputs** for completeness and accuracy
5. **Use results to begin** technical requirements and IA development

---

## THE CLAUDE PROMPT
**Copy everything from this line down to the end of the code block into Claude:**

```
You are synthesizing stakeholder interview analyses for a government digital transformation project using the CivicSpeed methodology. Your goal is to identify consensus, resolve conflicts, and create unified strategic direction for technical requirements and design development.

**PROJECT CONTEXT:**
- Agency: [AGENCY_NAME]
- Project: [PROJECT_NAME]
- Phase: Week 1 Completion → Week 2 Strategy Development
- Methodology: CivicSpeed AI-Accelerated Government Digital Transformation

**INDIVIDUAL STAKEHOLDER ANALYSES TO SYNTHESIZE:**
[PASTE ALL INDIVIDUAL INTERVIEW ANALYSES HERE]

**SYNTHESIS FRAMEWORK:**
Analyze patterns across all stakeholder interviews to create unified insights:

## SYNTHESIS METHODOLOGY

### 1. CONSENSUS IDENTIFICATION
**Strong Consensus (All stakeholders agree):**
- Identify areas where 100% of stakeholders align
- These become foundational requirements and priorities

**Majority Consensus (75%+ stakeholders agree):**
- Identify areas where most stakeholders align
- Note dissenting stakeholders and their concerns

**Emerging Consensus (50-74% stakeholders agree):**
- Identify areas with growing agreement
- Determine what's needed to reach stronger consensus

### 2. CONFLICT ANALYSIS
**Priority Conflicts:**
- Where stakeholders have competing priorities
- Resource allocation disagreements
- Timeline expectation mismatches

**Technical Conflicts:**
- Different technical approaches preferred
- Integration requirement disagreements
- Performance expectation differences

**Process Conflicts:**
- Workflow preference differences
- Approval process disagreements
- Communication style preferences

### 3. PATTERN RECOGNITION
**User Experience Patterns:**
- Common citizen pain points across stakeholder perspectives
- Consistent staff frustrations
- Shared service delivery challenges

**Technical Requirement Patterns:**
- Recurring integration needs
- Common performance requirements
- Consistent security/compliance needs

**Business Process Patterns:**
- Similar efficiency opportunities
- Common change management needs
- Shared success metrics

**OUTPUT FORMAT:**
Present your synthesis using this exact structure:

## EXECUTIVE SUMMARY
**Project Readiness Assessment:** [High/Medium/Low readiness for Week 2]
**Stakeholder Alignment Level:** [Strong/Moderate/Weak alignment]
**Critical Success Factors:** [Top 3 factors for project success]
**Immediate Action Items:** [Top 3 actions needed before Week 2]

## CONSENSUS ANALYSIS

### Strong Consensus Areas (100% Agreement)
**User Experience Priorities:**
1. [Priority 1] - [All stakeholders who mentioned this]
2. [Priority 2] - [All stakeholders who mentioned this]
3. [Priority 3] - [All stakeholders who mentioned this]

**Technical Requirements:**
1. [Requirement 1] - [All stakeholders who mentioned this]
2. [Requirement 2] - [All stakeholders who mentioned this]
3. [Requirement 3] - [All stakeholders who mentioned this]

**Business Process Improvements:**
1. [Improvement 1] - [All stakeholders who mentioned this]
2. [Improvement 2] - [All stakeholders who mentioned this]
3. [Improvement 3] - [All stakeholders who mentioned this]

### Majority Consensus Areas (75%+ Agreement)
**Near-Universal Priorities:**
- [Priority 1]: [Stakeholders who agree] vs [Stakeholders who dissent: concerns]
- [Priority 2]: [Stakeholders who agree] vs [Stakeholders who dissent: concerns]
- [Priority 3]: [Stakeholders who agree] vs [Stakeholders who dissent: concerns]

## CONFLICT RESOLUTION STRATEGY

### Priority Conflicts
**Conflict 1:** [Description of conflict]
- **Stakeholders:** [Who disagrees and why]
- **Impact:** [How this affects project success]
- **Resolution Strategy:** [Recommended approach to resolve]
- **Decision Authority:** [Who should make final decision]
- **Timeline:** [When this needs to be resolved]

**Conflict 2:** [Description of conflict]
- **Stakeholders:** [Who disagrees and why]
- **Impact:** [How this affects project success]
- **Resolution Strategy:** [Recommended approach to resolve]
- **Decision Authority:** [Who should make final decision]
- **Timeline:** [When this needs to be resolved]

### Technical Conflicts
**Conflict 1:** [Technical disagreement]
- **Technical Options:** [Different approaches stakeholders prefer]
- **Trade-offs:** [Pros/cons of each approach]
- **Recommendation:** [Best technical solution with rationale]
- **Stakeholder Buy-in Strategy:** [How to get agreement]

### Process Conflicts
**Conflict 1:** [Process disagreement]
- **Current State:** [How things work now]
- **Competing Visions:** [Different future states stakeholders want]
- **Hybrid Solution:** [Compromise approach that addresses concerns]
- **Implementation Plan:** [How to transition to new process]

## UNIFIED REQUIREMENTS

### User Experience Requirements
**Primary User Groups:** (Ranked by priority and service volume)
1. **[User Group 1]**
   - **Needs:** [Specific needs from all stakeholder perspectives]
   - **Pain Points:** [Current problems all stakeholders mentioned]
   - **Success Metrics:** [How all stakeholders measure success for this group]

2. **[User Group 2]**
   - **Needs:** [Specific needs from all stakeholder perspectives]
   - **Pain Points:** [Current problems all stakeholders mentioned]
   - **Success Metrics:** [How all stakeholders measure success for this group]

**Service Delivery Priorities:**
1. [Service 1]: [Why this is top priority based on stakeholder input]
2. [Service 2]: [Why this is second priority based on stakeholder input]
3. [Service 3]: [Why this is third priority based on stakeholder input]

### Technical Requirements
**Integration Requirements:** (Validated across all stakeholders)
- **[System 1]**: [Integration needs, stakeholders who mentioned, priority level]
- **[System 2]**: [Integration needs, stakeholders who mentioned, priority level]
- **[System 3]**: [Integration needs, stakeholders who mentioned, priority level]

**Performance Requirements:**
- **Speed:** [Specific requirements mentioned by stakeholders]
- **Availability:** [Uptime requirements from operational stakeholders]
- **Scalability:** [Growth expectations from executive stakeholders]

**Security & Compliance:**
- **[Compliance Standard 1]**: [Requirements, which stakeholders emphasized]
- **[Security Requirement 1]**: [Details, operational impact]
- **[Accessibility Requirement 1]**: [WCAG level, implementation details]

### Business Process Requirements
**Workflow Changes:**
1. **[Process 1]**: [Current state → Future state → Stakeholder impact]
2. **[Process 2]**: [Current state → Future state → Stakeholder impact]
3. **[Process 3]**: [Current state → Future state → Stakeholder impact]

**Approval Processes:**
- **[Approval Type 1]**: [Who approves, when, criteria, stakeholder concerns]
- **[Approval Type 2]**: [Who approves, when, criteria, stakeholder concerns]

## STRATEGIC RECOMMENDATIONS

### Week 2 Priorities (Immediate Focus)
1. **[Priority 1]**: [Why this must be addressed first, stakeholder support]
2. **[Priority 2]**: [Why this is second priority, implementation approach]
3. **[Priority 3]**: [Why this is third priority, timeline considerations]

### Phase 2 Design Implications
**Information Architecture:**
- [IA consideration 1 based on synthesis]
- [IA consideration 2 based on synthesis]
- [IA consideration 3 based on synthesis]

**User Journey Focus Areas:**
- [Journey area 1]: [Why this is critical based on stakeholder input]
- [Journey area 2]: [Why this needs special attention]
- [Journey area 3]: [Why this affects multiple stakeholder groups]

**Technical Architecture:**
- [Technical direction 1 based on requirements synthesis]
- [Technical direction 2 based on stakeholder consensus]
- [Technical direction 3 based on compliance requirements]

### Risk Mitigation
**High-Risk Areas:**
1. **[Risk 1]**: [Description, stakeholders affected, mitigation strategy]
2. **[Risk 2]**: [Description, stakeholders affected, mitigation strategy]
3. **[Risk 3]**: [Description, stakeholders affected, mitigation strategy]

## STAKEHOLDER MANAGEMENT PLAN

### Communication Strategy
**Executive Level:** [How to keep executives engaged and informed]
**Operational Level:** [How to maintain operational stakeholder support]
**Technical Level:** [How to ensure technical stakeholder collaboration]
**Communications Level:** [How to leverage communications stakeholder expertise]

### Validation Process
**Stakeholder Review:** [How to validate synthesis with original stakeholders]
**Conflict Resolution Sessions:** [Planned meetings to resolve identified conflicts]
**Approval Workflow:** [How to get formal approval for Week 2 strategy]

## SUCCESS METRICS

### Week 2 Success Criteria
- [ ] All priority conflicts resolved with stakeholder agreement
- [ ] Technical requirements comprehensive and approved by technical stakeholders
- [ ] User experience priorities validated by operational stakeholders
- [ ] Executive strategic alignment confirmed
- [ ] Communications strategy approved by communications stakeholders

### Phase 1 Completion Standards
- [ ] 95%+ stakeholder satisfaction achieved
- [ ] Zero major requirement changes requested
- [ ] All compliance requirements identified and validated
- [ ] Clear direction for Phase 2 design work established

## NEXT STEPS

### Immediate Actions (Next 48 Hours)
1. [Action 1]: [Who, what, when]
2. [Action 2]: [Who, what, when]
3. [Action 3]: [Who, what, when]

### Week 2 Preparation
- **Technical Requirements Development:** [Key focus areas]
- **Information Architecture Design:** [Starting points and constraints]
- **User Journey Mapping:** [Priority journeys to map first]

### Stakeholder Validation
- **Review Schedule:** [When to present synthesis to each stakeholder group]
- **Approval Timeline:** [When final approval needed for Phase 2]
- **Documentation Updates:** [What needs to be updated based on synthesis]

**SYNTHESIS CONFIDENCE LEVEL:** [High/Medium/Low]
**READINESS FOR WEEK 2:** [Ready/Needs Work/Blocked]
**CRITICAL PATH ITEMS:** [Any blockers that must be resolved immediately]
```

**SYNTHESIS INSTRUCTIONS:**
1. Look for patterns across ALL stakeholder types - don't let one voice dominate
2. Identify conflicts early and provide specific resolution strategies
3. Prioritize based on: citizen impact, operational efficiency, technical feasibility, executive priorities
4. Ensure all government compliance requirements are captured and reconciled
5. Flag any stakeholder concerns that could derail the project if not addressed
6. Focus on actionable insights that directly inform Week 2 technical work
7. Validate that the synthesis supports the 95% stakeholder satisfaction requirement

---

## Usage Notes

### Before Synthesis
- **Confirm all stakeholder interviews complete** - missing perspectives create incomplete synthesis
- **Review individual analyses** for quality and consistency
- **Identify obvious conflicts** that will need special attention during synthesis

### During Synthesis
- **Focus on government-specific needs** - compliance, approval workflows, public transparency
- **Balance stakeholder perspectives** - executive vision + operational reality + technical constraints + communication requirements
- **Be specific about conflicts** - vague conflict descriptions don't lead to resolution
- **Provide actionable recommendations** - synthesis must inform immediate Week 2 decisions

### After Synthesis
- **Validate with stakeholder representatives** before proceeding to Week 2
- **Document any synthesis assumptions** that need stakeholder confirmation
- **Prepare conflict resolution meetings** for any unresolved disagreements
- **Update project timeline** if synthesis reveals scope or complexity changes

### Quality Standards
- **Government compliance focus** ensures all regulatory requirements integrated
- **95% stakeholder satisfaction standard** requires addressing all major concerns
- **Technical precision** ensures Week 2 requirements development can proceed smoothly
- **Strategic clarity** provides clear direction for Phase 2 design decisions

---

## File Naming Convention
Save synthesis results as: `Stakeholder-Synthesis-[ProjectName]-[Date].md`

Example: `Stakeholder-Synthesis-Denver-Parks-Portal-2024-03-20.md`
