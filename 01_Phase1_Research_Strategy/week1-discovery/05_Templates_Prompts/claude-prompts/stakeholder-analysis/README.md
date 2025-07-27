# Claude Prompts for Stakeholder Analysis

## 🎯 Purpose
Standardized Claude prompts for analyzing government stakeholder interviews and extracting insights for digital transformation projects.

## 📋 Prompt Collection

### Individual Stakeholder Analysis
**File:** `individual-stakeholder-analysis-prompt.md`  
**Use:** After each stakeholder interview  
**Input:** Clean interview transcript + stakeholder context  
**Output:** 9-section government-specific analysis

### Cross-Stakeholder Synthesis
**File:** `cross-stakeholder-synthesis-prompt.md`  
**Use:** After all individual analyses complete  
**Input:** All individual stakeholder analyses  
**Output:** Unified priority framework and conflict resolution

### Technical Requirements Generation
**File:** `technical-requirements-prompt.md`  
**Use:** Week 2, Day 1-2  
**Input:** Stakeholder synthesis + technical audit results  
**Output:** Comprehensive technical requirements document

## 🔧 How to Use These Prompts

### 1. Copy Exact Prompt Text
Each prompt file contains the complete prompt with placeholder sections marked as `[PLACEHOLDER_TEXT]`.

### 2. Replace Placeholders
- `[AGENCY_NAME]` → Actual government agency name
- `[STAKEHOLDER_ROLE]` → Specific stakeholder title
- `[PROJECT_CONTEXT]` → Brief project description
- `[PASTE_TRANSCRIPT_HERE]` → Clean interview transcript

### 3. Execute in Claude Pro
Paste the completed prompt into a new Claude Pro conversation for best results.

### 4. Save Results
Save Claude's output in the appropriate deliverables folder with consistent naming:
- `[StakeholderTitle]_Analysis.md`
- `Cross_Stakeholder_Synthesis.md`
- `Technical_Requirements_Document.md`

## ✅ Quality Standards
Each prompt is designed to produce:
- Government-specific insights
- Compliance requirement identification
- Stakeholder conflict resolution
- Actionable technical requirements
- Measurable success criteria

## 🔄 Prompt Evolution
These prompts improve over time based on project results. Document any needed modifications and update the template repository.
