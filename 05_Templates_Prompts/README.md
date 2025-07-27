# 05_Templates_Prompts - Central Catalog & Cross-Phase Resources

## Purpose
This folder serves as the **central catalog** for all templates and prompts across the CivicSpeed methodology, plus houses cross-cutting resources that don't belong to specific phases.

## Structure Strategy
- **Catalog/Index approach:** Point to actual prompts in their workflow contexts
- **Cross-phase resources:** Templates and checklists used across multiple phases
- **Reusable components:** Generic templates that can be customized for any project

---

## 📁 claude-prompts/ - Central Prompt Catalog

### README.md Content:
```markdown
# Claude Prompts - Central Catalog

This folder catalogs all Claude prompts across the CivicSpeed methodology. **Actual prompts live in their workflow contexts** - these are indexes for easy discovery.

## Phase 1: Research & Strategy Prompts

### Week 1 Discovery
- **Individual Interview Analyzer**
  - Location: `01_Phase1_Research_Strategy/week1-discovery/01_stakeholder-interviews/claude-prompts/stakeholder-analysis-prompt.md`
  - Purpose: Transforms raw interview transcripts into structured insights
  - Input: Interview transcript
  - Output: Structured stakeholder analysis

- **Cross-Stakeholder Synthesizer**  
  - Location: `01_Phase1_Research_Strategy/week1-discovery/01_stakeholder-interviews/claude-prompts/cross-stakeholder-synthesis-prompt.md`
  - Purpose: Synthesizes multiple stakeholder analyses into unified strategic insights
  - Input: Multiple individual analyses
  - Output: Stakeholder synthesis with conflict resolution

### Week 2 Strategy Development
- **Technical Requirements Generator**
  - Location: `01_Phase1_Research_Strategy/week2-strategy/01_technical-requirements/requirements-prompt.md`
  - Purpose: Transforms synthesis insights into comprehensive technical specifications
  - Input: Stakeholder synthesis
  - Output: Detailed technical requirements

- **Information Architecture Designer**
  - Location: `01_Phase1_Research_Strategy/week2-strategy/02_information-architecture/ia-development-prompt.md`
  - Purpose: Creates citizen-centered IA from technical requirements
  - Input: Technical requirements
  - Output: Complete information architecture

- **User Journey Mapper**
  - Location: `01_Phase1_Research_Strategy/week2-strategy/03_user-journeys/user-journey-prompt.md`
  - Purpose: Maps detailed user experiences for all user types
  - Input: IA + Technical requirements
  - Output: Comprehensive user journey maps

## Phase 2: Design & Prototyping Prompts

### Week 4 Design System
- **Government Design System Generator**
  - Location: `02_Phase2_Design/week4-design-system/v0-prompts/government-design-system-prompt.md`
  - Purpose: Creates government-compliant design systems
  - Input: User journeys + Brand requirements
  - Output: Complete design system with components

## Quick Reference Guide

### By Input Type
- **Interview Transcripts** → Individual Interview Analyzer
- **Multiple Analyses** → Cross-Stakeholder Synthesizer  
- **Synthesis Document** → Technical Requirements Generator
- **Technical Requirements** → Information Architecture Designer
- **IA + Requirements** → User Journey Mapper

### By Output Type
- **Need structured stakeholder insights** → Individual Interview Analyzer
- **Need unified strategic direction** → Cross-Stakeholder Synthesizer
- **Need implementable tech specs** → Technical Requirements Generator
- **Need citizen-centered site structure** → Information Architecture Designer
- **Need detailed user experience maps** → User Journey Mapper

### By Phase
- **Phase 1 Week 1** → Interview analysis prompts
- **Phase 1 Week 2** → Strategy development prompts  
- **Phase 2 Week 4** → Design system prompts
```

### Subfolders (Index approach):
- `stakeholder-analysis/README.md` → **Index pointing to actual prompts**
- `technical-requirements/README.md` → **Index pointing to actual prompt**
- `information-architecture/README.md` → **Index pointing to actual prompt**
- `user-journeys/README.md` → **Index pointing to actual prompt**
- `design-system/README.md` → **Index pointing to actual prompt**

---

## 📁 document-templates/ - Cross-Phase Document Templates

### Purpose: Reusable document templates used across multiple phases

### executive-summaries/
- `phase1-executive-summary-template.md` - Standard format for Phase 1 summaries
- `phase2-executive-summary-template.md` - Standard format for Phase 2 summaries
- `project-kickoff-summary-template.md` - Initial project overview format
- `stakeholder-presentation-template.md` - Template for stakeholder presentations

### technical-specifications/
- `government-compliance-template.md` - Standard compliance documentation format
- `accessibility-requirements-template.md` - Section 508/WCAG compliance template
- `security-requirements-template.md` - Government security specifications template
- `integration-specifications-template.md` - System integration documentation template

### stakeholder-reports/
- `weekly-status-report-template.md` - Standard weekly progress reports
- `stakeholder-feedback-summary-template.md` - Feedback compilation format
- `conflict-resolution-report-template.md` - Template for documenting conflict resolution
- `approval-request-template.md` - Format for requesting stakeholder approvals

### project-handoffs/
- `phase-completion-report-template.md` - Standard phase completion documentation
- `technical-handoff-template.md` - Developer handoff documentation
- `client-handoff-template.md` - Final project delivery documentation
- `knowledge-transfer-template.md` - Internal team knowledge transfer

---

## 📁 checklists/ - Quality Assurance & Validation

### Purpose: Cross-cutting quality gates and validation checklists

### phase-completion-checklists/
- `phase1-completion-checklist.md` - **Links to:** `01_Phase1_Research_Strategy/phase1-handoff-checklist.md`
- `phase2-completion-checklist.md` - **Links to:** `02_Phase2_Design/phase2-deliverables/README.md`
- `phase3-completion-checklist.md` - Development completion validation
- `phase4-completion-checklist.md` - Final delivery validation

### quality-gates/
- `stakeholder-satisfaction-validation.md` - Process for achieving 95% satisfaction standard
- `government-compliance-verification.md` - Compliance requirement validation process
- `accessibility-testing-checklist.md` - WCAG 2.1 AA validation process
- `performance-standards-checklist.md` - Technical performance validation

### compliance-verification/
- `section-508-compliance-checklist.md` - Federal accessibility compliance
- `state-compliance-requirements.md` - State-level compliance variations
- `local-government-requirements.md` - Municipal compliance considerations
- `privacy-security-compliance.md` - Data protection and security validation

---

## 📁 automation-scripts/ (New folder)

### Purpose: Reusable automation and utility scripts

### prompt-automation/
- `batch-analysis-guide.md` - How to run multiple interviews through analysis prompts
- `synthesis-automation-tips.md` - Tips for efficient cross-stakeholder synthesis
- `quality-check-automation.md` - Automated quality validation approaches

### documentation-generators/
- `deliverable-index-generator.md` - Script to create deliverable indexes
- `stakeholder-report-compiler.md` - Automated report compilation from multiple sources
- `compliance-documentation-generator.md` - Automated compliance documentation

### github-integration/
- `project-setup-automation.md` - Automated project repository setup
- `deliverable-organization-script.md` - Automated file organization
- `version-control-standards.md` - Git workflow for CivicSpeed projects

---

## Main 05_Templates_Prompts README.md Structure:

```markdown
# Templates & Prompts - Central Resource Hub

## 🎯 Purpose
Central catalog and cross-cutting resources for the CivicSpeed methodology. **Actual prompts live in their workflow contexts** - this folder provides discovery, reusable templates, and quality assurance resources.

## 📋 Quick Start Guide

### Finding Prompts
1. **Browse by Phase:** Use `claude-prompts/README.md` to find prompts by project phase
2. **Browse by Input:** Find the right prompt based on what input you have
3. **Browse by Output:** Find the right prompt based on what deliverable you need

### Using Templates
1. **Document Templates:** Standard formats for deliverables and reports
2. **Quality Checklists:** Validation processes for each phase
3. **Compliance Templates:** Government-specific requirement documentation

### Quality Assurance
1. **Phase Completion:** Checklists ensure deliverable quality before moving to next phase
2. **Stakeholder Satisfaction:** Processes to achieve 95% satisfaction standard
3. **Compliance Verification:** Government requirement validation

## 🗂️ Folder Structure

### claude-prompts/
**Central catalog** pointing to actual prompts in workflow contexts
- Phase 1 analysis prompts (interview → synthesis → requirements → IA → journeys)
- Phase 2 design prompts (design systems, components, testing)
- Quick reference guides by input/output type

### document-templates/
**Reusable templates** for consistent deliverable formatting
- Executive summaries and stakeholder presentations
- Technical specifications and compliance documentation
- Status reports and handoff documentation

### checklists/
**Quality gates** and validation processes
- Phase completion validation
- Government compliance verification
- Accessibility and performance standards

### automation-scripts/
**Efficiency tools** and automation guidance
- Prompt usage optimization
- Documentation generation
- Project setup automation

## 🎯 Usage Guidelines

### For New Projects
1. Start with `claude-prompts/README.md` to understand available analysis tools
2. Use `document-templates/` for consistent deliverable formatting
3. Follow `checklists/phase-completion-checklists/` for quality gates

### For Ongoing Projects
1. Reference `claude-prompts/` catalog to find specific analysis tools
2. Use `quality-gates/` checklists to validate deliverable quality
3. Apply `compliance-verification/` processes for government requirements

### For Template Customization
1. Copy templates from `document-templates/` 
2. Customize for agency-specific requirements
3. Maintain core structure for consistency across projects

## 📞 Support

### Documentation Location
- **Actual prompts:** Live in phase-specific folders where teams use them
- **Usage guidance:** Comprehensive instructions included with each prompt
- **Quality standards:** Built-in validation checklists prevent common issues

### Best Practices
- **Single source of truth:** Each prompt exists in only one location
- **Workflow integration:** Tools appear where teams naturally use them
- **Quality focus:** Validation processes ensure 95% stakeholder satisfaction

---

**Next Steps:** Navigate to `claude-prompts/README.md` to explore available analysis tools, or start with phase-specific folders for workflow-integrated prompts.
```

## Summary of Changes:

✅ **No prompt duplication** - `05_Templates_Prompts/` points to actual prompts in workflow contexts  
✅ **Central catalog function** - Easy discovery of all prompts across phases  
✅ **Cross-cutting resources** - Templates and checklists used across multiple phases  
✅ **Quality assurance focus** - Validation processes and compliance verification  
✅ **Automation support** - Scripts and tools for efficiency  
✅ **Clear navigation** - Teams can find tools by phase, input type, or output needed  

This structure gives you the best of both worlds: **workflow-integrated prompts** where teams actually use them, plus a **central hub** for discovery and cross-cutting resources.
