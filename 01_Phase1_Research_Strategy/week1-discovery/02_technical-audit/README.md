# Technical Audit - Week 1

## 🎯 Purpose
Complete technical assessment of government website and systems using AI-accelerated analysis. Provides objective technical data to complement stakeholder perspectives and validate technical concerns.

## 📋 Simple Workflow

### Day 1-2: Setup & Coordinate
1. **Follow `screaming-frog-setup.md`** for tool installation
2. **Configure government-friendly settings** (respectful crawling)
3. **Coordinate with IT team** for large site access

### Day 3-4: Data Collection
1. **Run Screaming Frog crawl** of government website
2. **Export key data:** All Pages, Images, Links, Titles
3. **Organize files** in local project folder (not template)

### Day 5: AI Analysis
1. **Use Technical Analysis Claude prompt** with exported data
2. **Claude generates comprehensive analysis** with all sections
3. **Copy/paste sections into modular files:**
   - Copy "Technical Architecture" → `integration-inventory.md`
   - Copy "Performance Benchmarks" → `performance-baseline.md`  
   - Copy "Compliance & Security" → `security-assessment.md`
   - Copy "Critical Issues + Recommendations" → `technical-findings-summary.md`

## 🎯 Your AI-Accelerated Workflow:
```
Setup Screaming Frog → Crawl website → Export audit data
↓
Feed data to Claude prompt → Get comprehensive technical analysis
↓
Copy/paste sections → 4 modular files in ai-outputs/
↓
Combine for client → Complete technical analysis deliverable
```

## 🔗 Connects To:
- **Stakeholder Interviews:** Validates technical concerns with objective data
- **Week 1 Synthesis:** Technical findings inform unified requirements
- **Week 2 Strategy:** Technical constraints guide requirements and architecture

## ✅ Success Criteria:
- [ ] Screaming Frog configured and website crawl completed
- [ ] All required data exports generated (Pages, Images, Links, Titles)
- [ ] Claude comprehensive technical analysis completed 
- [ ] Analysis sections organized into 4 modular files in `ai-outputs/`
- [ ] Combined technical analysis ready for client deliverable

**Timeline:** Days 1-5 of Week 1 (parallel to interviews)  
**Output:** Modular technical assessment + comprehensive client deliverable
