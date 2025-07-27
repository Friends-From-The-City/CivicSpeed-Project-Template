# Claude Prompt: Individual Interview Analyzer

## Purpose
This prompt transforms raw stakeholder interview transcripts into structured insights for government digital transformation projects. Use this for each individual interview before cross-stakeholder synthesis.

## How to Use
1. **Copy the prompt below** into a new Claude conversation
2. **Replace [INTERVIEW_TRANSCRIPT]** with the actual transcript
3. **Specify stakeholder type** (Executive, Operations, Technical, Communications)
4. **Review and validate** the extracted insights
5. **Save results** using the provided template format

---

## The Prompt

```
You are analyzing a stakeholder interview transcript for a government digital transformation project using the CivicSpeed methodology. Extract key insights that will inform technical requirements, information architecture, and user journey development.

**INTERVIEW CONTEXT:**
- Stakeholder Type: [EXECUTIVE/OPERATIONS/TECHNICAL/COMMUNICATIONS]
- Agency: [AGENCY_NAME]
- Project: [PROJECT_NAME]
- Interview Date: [DATE]
- Interviewer: [NAME]
- Interviewee: [NAME, TITLE]

**TRANSCRIPT TO ANALYZE:**
[INTERVIEW_TRANSCRIPT]

**ANALYSIS FRAMEWORK:**
Extract insights across these 5 critical dimensions:

## 1. USER NEEDS & PAIN POINTS
**Current Citizen Experience:**
- What specific problems do citizens face with current services?
- Where do citizens get frustrated or confused?
- What workarounds do citizens currently use?
- Which user groups have the most difficulty?

**Staff Experience:**
- What daily challenges does staff face?
- Where do current systems create inefficiencies?
- What manual processes could be automated?
- What training or support gaps exist?

## 2. BUSINESS GOALS & PRIORITIES
**Strategic Objectives:**
- What are this stakeholder's top 3 priorities for the project?
- How does this project align with agency mission?
- What success metrics matter most to this stakeholder?
- What budget or timeline constraints were mentioned?

**Operational Impact:**
- How will this project change daily operations?
- What efficiency gains are expected?
- What risks or concerns were expressed?
- What level of change management will be needed?

## 3. TECHNICAL CONSTRAINTS & REQUIREMENTS
**Current Technology:**
- What existing systems must be integrated with?
- What technical limitations were mentioned?
- What security or compliance requirements are critical?
- What infrastructure constraints exist?

**Future Technology Needs:**
- What new capabilities are required?
- What accessibility requirements were specified?
- What performance expectations were set?
- What data management needs were discussed?

## 4. COMPLIANCE & GOVERNANCE
**Regulatory Requirements:**
- What specific compliance standards were mentioned?
- What approval processes must be followed?
- What audit or reporting requirements exist?
- What accessibility standards must be met?

**Internal Policies:**
- What agency policies affect this project?
- What approval workflows are required?
- What documentation standards must be followed?
- What quality assurance processes are needed?

## 5. STAKEHOLDER RELATIONSHIPS & COMMUNICATION
**Internal Relationships:**
- How does this stakeholder interact with other departments?
- What coordination challenges were mentioned?
- Who are the key decision-makers they work with?
- What communication preferences were expressed?

**External Relationships:**
- How does this stakeholder interact with citizens?
- What partner organizations are involved?
- What public communication requirements exist?
- What community engagement is needed?

**OUTPUT FORMAT:**
Present your analysis using this exact structure:

## STAKEHOLDER PROFILE
**Name:** [Name, Title]
**Stakeholder Type:** [Executive/Operations/Technical/Communications]
**Primary Responsibilities:** [Key areas they oversee]
**Project Influence Level:** [High/Medium/Low]

## KEY INSIGHTS SUMMARY
**Top 3 Priorities:**
1. [Priority 1 with specific details]
2. [Priority 2 with specific details]  
3. [Priority 3 with specific details]

**Critical Success Factors:**
- [Factor 1]
- [Factor 2]
- [Factor 3]

**Major Concerns/Risks:**
- [Concern 1]
- [Concern 2]
- [Concern 3]

## DETAILED ANALYSIS

### User Needs & Pain Points
**Citizen Experience Issues:**
- [Specific pain point 1]
- [Specific pain point 2]
- [Specific pain point 3]

**Staff Experience Issues:**
- [Specific challenge 1]
- [Specific challenge 2]
- [Specific challenge 3]

**User Groups Identified:**
- [User group 1]: [Specific needs]
- [User group 2]: [Specific needs]
- [User group 3]: [Specific needs]

### Business Goals & Priorities
**Strategic Alignment:**
- [How project supports agency mission]
- [Expected business outcomes]
- [Success metrics mentioned]

**Operational Changes:**
- [Process changes required]
- [Efficiency opportunities]
- [Change management needs]

### Technical Requirements
**Integration Needs:**
- [System 1]: [Integration details]
- [System 2]: [Integration details]
- [System 3]: [Integration details]

**Performance Requirements:**
- [Performance expectation 1]
- [Performance expectation 2]
- [Performance expectation 3]

**Security/Compliance:**
- [Security requirement 1]
- [Compliance standard 1]
- [Accessibility requirement 1]

### Compliance & Governance
**Regulatory Compliance:**
- [Specific regulation 1]: [Requirements]
- [Specific regulation 2]: [Requirements]

**Internal Processes:**
- [Approval process 1]
- [Documentation requirement 1]
- [Quality standard 1]

### Communication & Relationships
**Internal Coordination:**
- [Department/role 1]: [Interaction type]
- [Department/role 2]: [Interaction type]

**External Communication:**
- [Stakeholder group 1]: [Communication needs]
- [Stakeholder group 2]: [Communication needs]

## QUOTES & EVIDENCE
**Verbatim Quotes:** (Include 3-5 key quotes that capture essential insights)
1. "[Quote 1]" - [Context/significance]
2. "[Quote 2]" - [Context/significance]
3. "[Quote 3]" - [Context/significance]

## IMPLICATIONS FOR DESIGN
**Information Architecture:**
- [IA consideration 1 based on this interview]
- [IA consideration 2 based on this interview]

**User Journey Impact:**
- [Journey consideration 1]
- [Journey consideration 2]

**Technical Architecture:**
- [Technical consideration 1]
- [Technical consideration 2]

## FOLLOW-UP QUESTIONS
**Clarifications Needed:**
- [Question 1 for this stakeholder]
- [Question 2 for this stakeholder]

**Additional Stakeholders to Interview:**
- [Suggested person/role 1]: [Why needed]
- [Suggested person/role 2]: [Why needed]

## VALIDATION CHECKLIST
- [ ] All 5 analysis dimensions addressed
- [ ] Specific examples and details captured
- [ ] Verbatim quotes included for key insights
- [ ] Technical requirements clearly documented
- [ ] Compliance requirements identified
- [ ] User groups and needs specified
- [ ] Success metrics captured
- [ ] Risks and concerns documented
- [ ] Follow-up actions identified
- [ ] Ready for cross-stakeholder synthesis

**ANALYSIS CONFIDENCE LEVEL:** [High/Medium/Low]
**ADDITIONAL NOTES:** [Any important context or observations]
```

**INSTRUCTIONS:**
1. Be thorough but concise - extract specific, actionable insights
2. Focus on information that will directly inform technical requirements and design decisions
3. Identify conflicts or gaps that need resolution in cross-stakeholder synthesis
4. Capture exact quotes for critical insights to maintain authenticity
5. Flag any compliance or security requirements that seem non-negotiable
6. Note where this stakeholder's priorities might conflict with others
7. Ensure all technical requirements are specific enough to be actionable

---

## Usage Notes

### Before Analysis
- **Review interview transcript** for completeness
- **Confirm stakeholder type** classification  
- **Verify project context** information

### During Analysis
- **Take your time** - thorough analysis prevents rework
- **Be specific** - vague insights don't help design decisions
- **Capture verbatim quotes** - exact words matter for validation
- **Note confidence levels** - flag where clarification is needed

### After Analysis
- **Review for completeness** using the validation checklist
- **Save in structured format** for easy synthesis
- **Flag urgent issues** that need immediate attention
- **Prepare for cross-stakeholder synthesis**

### Quality Standards
- **95% stakeholder satisfaction requirement** means insights must be accurate and complete
- **Government compliance focus** requires capturing all regulatory requirements
- **Technical precision** ensures requirements are implementable
- **Citizen-centered approach** prioritizes user experience insights

---

## File Naming Convention
Save analysis results as: `Interview-Analysis-[StakeholderType]-[LastName]-[Date].md`

Examples:
- `Interview-Analysis-Executive-Johnson-2024-03-15.md`
- `Interview-Analysis-Technical-Rodriguez-2024-03-16.md`
