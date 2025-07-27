# Stakeholder Interviews

## 🎯 Purpose
Conduct comprehensive stakeholder discovery across all levels of government organization to understand priorities, challenges, and requirements for digital transformation.

## ⏱️ Time Investment
**Total Time:** 12-16 hours over 3-4 days  
**Per Interview:** 20 minutes interview + 15 minutes analysis  
**Setup Time:** 4-6 hours for identification and scheduling  
**AI Analysis:** 6-8 hours for complete synthesis

## 👥 Required Stakeholder Matrix

### Executive Level (Strategic Direction) - **2 Required**
**Primary Stakeholder:**
- **Agency Director/Commissioner** - Ultimate decision maker, public accountability
- **Deputy Director/Assistant Director** - Strategic implementation, day-to-day oversight

**Interview Focus:**
- Strategic priorities and public service mission alignment
- Political considerations and public accountability measures
- Budget constraints and funding timeline pressures
- Inter-agency coordination and external dependencies
- Public relations and media attention management

**Why Critical:** Sets strategic direction, approves budget, manages public accountability

### Operational Level (Daily Impact) - **2 Required**
**Primary Stakeholders:**
- **Operations Manager/Program Director** - Daily service delivery oversight
- **Customer Service Manager** - Direct citizen interaction management

**Interview Focus:**
- Current operational challenges affecting citizen services
- Staff workflow impacts and training requirements
- Peak usage periods and capacity planning
- Manual processes that could benefit from automation
- Citizen complaint patterns and service delivery gaps

**Why Critical:** Understands real impact on citizens and daily government operations

### Technical Level (Implementation) - **2 Required**
**Primary Stakeholders:**
- **IT Manager/CIO** - Technology infrastructure and standards
- **Security Officer/CISO** - Security frameworks and compliance requirements

**Interview Focus:**
- Legacy system integration requirements and constraints
- Government technology standards and procurement rules
- Security frameworks and compliance requirements (NIST, FedRAMP, etc.)
- Performance and scalability requirements
- Authority to Operate (ATO) processes and timeline

**Why Critical:** Determines technical feasibility and security compliance requirements

### Communications Level (Public Interface) - **1-2 Required**
**Primary Stakeholders:**
- **Communications Director/PIO** - Public messaging and transparency
- **Web Content Manager** - Day-to-day content and website management

**Interview Focus:**
- Content creation and approval workflows
- Emergency communication requirements
- Public transparency and records management
- Multi-language and accessibility requirements
- Citizen engagement and feedback processes

**Why Critical:** Manages public-facing content and citizen communication

## 📋 Interview Process Framework

### Pre-Interview Preparation (15 minutes per stakeholder)

#### 1. Stakeholder Research
- **Review role and responsibilities** from agency website/org chart
- **Understand department focus** and primary citizen services
- **Identify potential pain points** based on role level
- **Research recent agency initiatives** that might affect priorities

#### 2. Technical Setup
- **Test Otter.ai recording** with government compliance settings
- **Verify video conferencing** platform and recording capability
- **Prepare backup recording** method (phone app, local recording)
- **Test internet connection** and audio quality

#### 3. Template Customization
- **Select appropriate interview template** from `interview-templates/`
- **Customize questions** for specific agency context and services
- **Prepare follow-up questions** based on stakeholder research
- **Review timing** to ensure 20-minute target

### Interview Execution (20 minutes structured)

#### Introduction (2 minutes)
**Script Template:**
> "Thank you for your time today. I'm [Name] leading the digital transformation discovery for [Agency]. This 20-minute interview helps us understand your priorities and ensure our approach serves your needs and citizens effectively. 
> 
> I'll be recording this for analysis - is that okay? Everything is confidential and will be used only for project planning.
> 
> Could you briefly confirm your role and main responsibilities?"

#### Core Questions (15 minutes)
**Use role-specific template from `interview-templates/` folder:**
- Follow question sequence but allow natural conversation flow
- **Listen for emotional indicators** - frustration, excitement, concern
- **Capture specific examples** - real situations, not hypotheticals
- **Note exact quotes** - powerful language that reveals priorities
- **Probe deeper** when stakeholders mention challenges or priorities

#### Wrap-up (3 minutes)
**Closing Script:**
> "This has been really valuable. Two final questions:
> 1. What would make this digital transformation a clear success for you personally?
> 2. Is there anything critical I haven't asked about that affects your work?
>
> May I follow up if we need clarification on anything? Thank you for your time."

### Post-Interview Tasks (15 minutes per interview)

#### 1. Technical Cleanup (5 minutes)
- **Stop and save Otter.ai recording** with clear filename
- **Export transcript** as text file immediately
- **Test transcript quality** - ensure speaker identification works
- **Save backup recording** if available

#### 2. Immediate Documentation (10 minutes)
- **Write initial impressions** while conversation is fresh
- **Note key quotes and emotional responses** 
- **Identify potential conflicts** with other stakeholder priorities
- **Document follow-up questions** if needed

#### 3. File Organization
- **Save recording:** `Raw_Recordings/[StakeholderTitle]_[Date]_Interview.mp3`
- **Save transcript:** `Transcripts/[StakeholderTitle]_[Date]_Transcript.txt`
- **Save notes:** `Interview_Notes_[StakeholderTitle].md`

## 🎧 Recording & Transcription Best Practices

### Audio Quality Requirements
- **Quiet environment** - minimal background noise
- **Clear audio levels** - test beforehand with Otter.ai
- **Stable internet** - recording quality depends on connection
- **Backup method** - always have secondary recording option

### Otter.ai Government Compliance Setup
```
Settings to Configure:
✅ Business/Enterprise account (required for government compliance)
✅ Encryption enabled for all recordings
✅ Retention policy set according to government requirements
✅ Speaker identification enabled
✅ Real-time transcription quality set to highest
✅ Export permissions configured for team access
```

### Transcript Cleaning Process
1. **Download raw transcript** immediately after interview
2. **Clean obvious errors** - speech-to-text mistakes, unclear words
3. **Add speaker labels** if missing: `[Interviewer]:` and `[Stakeholder]:`
4. **Remove filler words** if excessive (um, uh, you know)
5. **Preserve meaning** - don't change context or intent
6. **Mark unclear sections** with `[unclear]` rather than guessing

## 🤖 AI Analysis Preparation

### Input Quality Requirements
**For optimal Claude analysis, ensure:**
- **Clean transcript format** with clear speaker identification
- **Complete stakeholder context** (role, department, responsibilities)
- **Agency background** (mission, services, current challenges)
- **Project scope** (what's being transformed, timeline, budget level)

### Analysis Prompt Location
**Individual Analysis:** `05_Templates_Prompts/claude-prompts/stakeholder-analysis/individual-stakeholder-analysis-prompt.md`

**Synthesis Analysis:** `05_Templates_Prompts/claude-prompts/stakeholder-analysis/cross-stakeholder-synthesis-prompt.md`

### Expected Analysis Output
Each stakeholder analysis produces:
1. **Strategic Priorities** - Top 3 stated priorities with government context
2. **Operational Challenges** - Specific problems affecting public service
3. **Compliance Requirements** - Federal, state, local requirements mentioned
4. **Technical Constraints** - System limitations and government standards
5. **Stakeholder Ecosystem** - Approval processes and coordination needs
6. **Success Metrics** - How they'll measure project success
7. **Implementation Risks** - Government-specific project risks
8. **Quoted Insights** - Direct quotes capturing priorities and concerns
9. **Potential Conflicts** - Areas of disagreement with other stakeholders

## 📊 Quality Assurance Metrics

### Interview Coverage Validation
- [ ] **All 4 levels represented:** Executive, Operational, Technical, Communications
- [ ] **Minimum 6 stakeholders:** Can be more, but not fewer
- [ ] **Key roles covered:** Director, IT, Operations, Communications minimum
- [ ] **Balanced perspective:** Not dominated by single department/viewpoint

### Interview Quality Standards
- [ ] **Clear audio quality:** Transcription accuracy >85%
- [ ] **Complete responses:** All key questions answered substantively
- [ ] **Emotional indicators:** Captured stakeholder frustrations and priorities
- [ ] **Specific examples:** Real situations and pain points documented

### AI Analysis Quality
- [ ] **Complete analysis:** All 9 sections addressed for each stakeholder
- [ ] **Government context:** Analysis reflects public sector priorities
- [ ] **Conflict identification:** Disagreements between stakeholders noted
- [ ] **Actionable insights:** Analysis provides clear direction for requirements

## 🚨 Common Interview Challenges & Solutions

### Challenge: Stakeholder Unavailability
**Problem:** Key stakeholders too busy or unresponsive to interview requests

**Solutions:**
- **Executive sponsor engagement** - Have agency director encourage participation
- **Flexible scheduling** - Offer early morning, lunch, or after-hours options
- **Shorter time commitment** - Emphasize 20-minute duration
- **Value proposition** - Explain how their input directly improves their work

### Challenge: Surface-Level Responses
**Problem:** Stakeholders giving generic answers without specific details

**Solutions:**
- **Ask for examples** - "Can you give me a specific situation where..."
- **Probe emotional responses** - "How does that make you feel when..."
- **Focus on pain points** - "What's the most frustrating part of..."
- **Request quantification** - "How much time does that take..." or "How often does..."

### Challenge: Conflicting Information
**Problem:** Different stakeholders providing contradictory information

**Solutions:**
- **Document all perspectives** - Don't try to resolve during interviews
- **Note specific contexts** - Different roles see different aspects
- **Ask for clarification** - "Others have mentioned X, what's your perspective?"
- **Use synthesis process** - AI analysis will identify and help resolve conflicts

### Challenge: Technical Recording Issues
**Problem:** Poor audio quality or failed recordings affecting analysis

**Solutions:**
- **Always test equipment** before starting interviews
- **Use backup recording** methods (phone app, local recording)
- **Conduct interviews in quiet** environments with stable internet
- **Have technical backup plan** - someone to help with recording if needed

## ✅ Interview Completion Checklist

### Per Interview Checklist
- [ ] **Pre-interview setup complete:** Equipment tested, template prepared
- [ ] **Recording successful:** Clear audio, Otter.ai working properly
- [ ] **Complete transcript:** Downloaded and cleaned for analysis
- [ ] **Initial notes documented:** Key insights and quotes captured
- [ ] **Files organized:** Saved in proper folder structure

### Overall Interview Phase Checklist
- [ ] **All stakeholder levels covered:** 4 government levels represented
- [ ] **Minimum interview count:** 6+ stakeholders interviewed
- [ ] **Quality standards met:** All interviews useful for analysis
- [ ] **AI analysis ready:** Clean transcripts prepared for Claude Pro
- [ ] **Timeline adherence:** Interviews completed within 3-4 day window

### Handoff to Analysis Phase
- [ ] **All recordings saved** in `Raw_Recordings/` folder
- [ ] **All transcripts cleaned** and saved in `Transcripts/` folder
- [ ] **Interview notes complete** for immediate reference
- [ ] **Stakeholder context documented** for AI analysis input
- [ ] **Analysis prompts prepared** with agency-specific context

## ➡️ Next Steps

**After Interview Completion:**
1. **Begin AI Analysis** using prompts in `../claude-prompts/`
2. **Individual stakeholder analysis** for each interview
3. **Cross-stakeholder synthesis** to identify themes and conflicts
4. **Week 1 deliverable creation** based on synthesis results

**Success Criteria:**
Complete all stakeholder interviews within 3-4 days with high-quality recordings and transcripts ready for AI analysis that will produce actionable insights for government digital transformation strategy.

---

## 🎯 Interview Success Framework

**Quality Interviews = Quality Analysis = Quality Strategy**

Follow this systematic approach to ensure stakeholder interviews provide the foundation for successful government digital transformation discovery and strategy development.
