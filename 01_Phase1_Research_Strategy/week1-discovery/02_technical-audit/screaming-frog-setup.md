# Screaming Frog Setup Guide
## Quick Technical Audit for Government Sites

## 🎯 Purpose
Set up Screaming Frog SEO Spider to collect technical audit data for AI analysis. This guide gets you from installation to data export in 30 minutes.

## 📥 Installation

### 1. Download & Install
- Visit: https://www.screamingfrog.co.uk/seo-spider/
- Download for your operating system
- Install (requires 2GB+ RAM, 8GB+ recommended for large sites)

### 2. License Options
- **Free Version:** Up to 500 URLs (works for small government sites)
- **Paid License:** £149/year for unlimited crawling (recommended for most agencies)

---

## ⚙️ Essential Configuration

### Basic Setup
1. **Launch Screaming Frog**
2. **Set Memory:** Configuration > System > Performance
   - Set **Memory Usage** to 2GB minimum (4GB+ for large sites)

### Government-Friendly Settings
**Respectful Crawling** (protect government servers):
- **Configuration > Spider > Speed**
  - **Crawl Delay:** 1-2 seconds
  - **Max Threads:** 5
  - **Timeout:** 30 seconds

**Content Extraction** (for accessibility analysis):
- **Configuration > Spider > Extraction**
  - ✅ **Extract Images Alt Text**
  - ✅ **Extract Meta Keywords**
  - ✅ **Extract Meta Descriptions** 
  - ✅ **Extract H1 and H2**

---

## 🔍 Running the Audit

### Step 1: Coordinate with IT
- **Notify government IT team** before large crawls
- **Schedule during low-traffic periods** (evenings/weekends)
- **Provide crawler info** if needed for firewall allowlisting

### Step 2: Start Crawl
1. **Enter website URL** (e.g., https://cityname.gov)
2. **Test with small crawl first** (Configuration > Limits > 100 URLs)
3. **Run full crawl** after test succeeds
4. **Monitor progress** - pause if server issues occur

### Step 3: Essential Data Exports
**Required exports for AI analysis:**

1. **All Pages:** File > Export > All Pages > Excel
2. **Images:** File > Export > Images > Excel  
3. **Internal Links:** File > Export > Links > Internal > Excel
4. **Page Titles:** File > Export > Page Titles > Excel

---

## 📁 File Organization (Local Project Work)

> **Note:** This file organization is for your local project folder, not the GitHub template. Raw Screaming Frog data stays on your computer. Only AI-generated analysis results go into the template's `ai-outputs/` folder.

### Naming Convention (Local Files)
```
[Agency]-[Type]-[Date].xlsx

Examples:
Denver-Parks-AllPages-2024-03-15.xlsx
Denver-Parks-Images-2024-03-15.xlsx
Denver-Parks-Links-2024-03-15.xlsx
Denver-Parks-Titles-2024-03-15.xlsx
```

### Local Project Folder Structure
```
your-project-name/ (on your computer)
├── technical-audit-data/
│   ├── denver-parks-allpages-2024-03-15.xlsx
│   ├── denver-parks-images-2024-03-15.xlsx
│   ├── denver-parks-links-2024-03-15.xlsx
│   └── denver-parks-titles-2024-03-15.xlsx
└── project-deliverables/
    └── (AI-generated analysis results saved here)
```

---

## 🤖 Preparing Data for AI Analysis

### What Claude Needs
The **Technical Analysis Claude Prompt** will process your exported Excel files to generate:
- **Accessibility compliance assessment** (from Images export)
- **Performance issues identification** (from All Pages export)
- **Navigation and structure analysis** (from Internal Links export)
- **Content quality review** (from Page Titles export)

### Quick Workflow
1. **Run Screaming Frog audit** → Export 4 key files
2. **Upload files to Claude** → Use Technical Analysis prompt
3. **Get AI analysis** → Save outputs to `ai-outputs/` folder
4. **Review results** → Professional technical assessment ready

---

## 🚨 Quick Troubleshooting

**Slow Crawling:**
- Increase crawl delay to 2-3 seconds
- Reduce threads to 3-5
- Coordinate with IT team

**Access Issues:**
- Check with IT team about IP allowlisting
- Verify robots.txt allows crawling
- Try during different hours

**Large Sites:**
- Increase memory allocation
- Crawl in segments if needed
- Use paid version for sites >500 pages

---

## ✅ Success Checklist

**Setup Complete:**
- [ ] Screaming Frog installed and configured
- [ ] Government-friendly crawl settings applied
- [ ] Content extraction enabled for accessibility analysis

**Audit Complete:**
- [ ] Test crawl successful
- [ ] Full crawl completed without server issues
- [ ] All 4 required exports generated and saved

**Ready for AI Analysis:**
- [ ] Files organized with clear naming
- [ ] Data quality verified (no major gaps)
- [ ] Ready to use Technical Analysis Claude prompt

---

## 🎯 Next Step
**Use your exported data with the Technical Analysis Claude prompt** to generate comprehensive government website audit findings in minutes instead of hours.

**Time Investment:** 30 minutes setup + crawl time = Professional technical audit foundation
