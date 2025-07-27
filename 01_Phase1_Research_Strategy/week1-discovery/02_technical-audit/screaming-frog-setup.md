# Screaming Frog SEO Spider Setup Guide

## 🎯 Purpose
This guide provides step-by-step instructions for setting up Screaming Frog SEO Spider for government website technical audits. Screaming Frog is the primary tool for comprehensive website crawling and technical analysis in the CivicSpeed methodology.

## 📋 Overview
Screaming Frog SEO Spider is a website crawler that audits website technical elements including:
- Page response codes and redirects
- Page titles, meta descriptions, and headings
- Images and alt text compliance
- Internal and external links
- Website structure and navigation
- Technical SEO elements

---

## SOFTWARE INSTALLATION

### System Requirements
**Minimum Requirements:**
- **Operating System:** Windows 7+, macOS 10.10+, or Linux
- **RAM:** 2GB minimum (8GB+ recommended for large sites)
- **Disk Space:** 1GB free space
- **Java:** Java 8+ (automatically installed with application)

**Recommended for Government Sites:**
- **RAM:** 16GB+ (government sites often have large page counts)
- **CPU:** Multi-core processor for faster crawling
- **SSD Storage:** Faster data processing and export generation

### Download and Installation
1. **Download Screaming Frog:**
   - Visit: https://www.screamingfrog.co.uk/seo-spider/
   - Choose your operating system (Windows/Mac/Linux)
   - Download the installer

2. **Install the Application:**
   - **Windows:** Run the .exe installer as administrator
   - **Mac:** Drag the application to Applications folder
   - **Linux:** Extract and run the installation script

3. **License Considerations:**
   - **Free Version:** Crawls up to 500 URLs (suitable for small government sites)
   - **Paid License:** £149/year for unlimited crawling (recommended for most government sites)
   - **Government Procurement:** Check if your agency has existing license or procurement requirements

---

## BASIC CONFIGURATION

### Initial Setup
1. **Launch Screaming Frog SEO Spider**
2. **Accept License Agreement** and complete initial setup wizard
3. **Configure Basic Settings:**
   - Navigate to **Configuration > System > Performance**
   - Set **Memory Usage** to 2GB minimum (4GB+ for large sites)
   - Set **Max Threads** to 5-10 (government servers may have rate limiting)

### Government-Specific Configuration
**Respectful Crawling Settings:**
- **Configuration > Spider > Speed**
  - Set **Crawl Delay:** 1-2 seconds (be respectful of government servers)
  - **Limit:** Maximum 10 requests per second
  - **Timeout:** 30 seconds (government sites may load slowly)

**User Agent Configuration:**
- **Configuration > User-Agent**
- Select **"Screaming Frog SEO Spider"** (identifies crawler to government IT teams)
- Do not use deceptive user agents for government site auditing

---

## CRAWL CONFIGURATION FOR GOVERNMENT SITES

### Basic Crawl Settings
**Website URL Setup:**
1. Enter the full government website URL (e.g., https://cityname.gov)
2. **Configuration > Include**
   - Check **"Include external links"** for comprehensive link analysis
   - Set **"Max depth"** to 10 levels (captures most government site structure)

**Content Type Configuration:**
- **Configuration > Spider > Extraction**
  - Check **"Extract Images Alt Text"** (critical for accessibility compliance)
  - Check **"Extract Meta Keywords"** and **"Meta Descriptions"**
  - Check **"Extract H1 and H2"** for content structure analysis

### Government Compliance-Focused Settings
**Accessibility Audit Setup:**
- **Configuration > Spider > Extraction**
  - Enable **"Alt Text"** extraction
  - Enable **"Image"** analysis
  - Enable **"Meta Description"** for content quality review

**SEO and Content Analysis:**
- **Configuration > Spider > Content**
  - Set **"Max file size"** to 10MB (government documents can be large)
  - Enable **"Near Duplicates"** detection
  - Enable **"Exact Duplicates"** detection

**Security and Performance:**
- **Configuration > Spider > Advanced**
  - Enable **"Response Times"** monitoring
  - Enable **"Robots.txt"** compliance checking
  - Check **"Respect Canonical"** for proper URL handling

---

## GOVERNMENT SITE CRAWLING BEST PRACTICES

### Pre-Crawl Coordination
**IT Department Coordination:**
1. **Notify government IT team** before conducting comprehensive crawls
2. **Provide crawler IP address** if firewall whitelisting needed
3. **Schedule crawling** during low-traffic periods (evenings, weekends)
4. **Agree on crawl limitations** to avoid overwhelming government servers

**Scope Definition:**
- **Crawl primary domain only** initially (e.g., cityname.gov)
- **Include subdomains** if comprehensive audit needed
- **Exclude admin areas** and login pages (/admin, /wp-admin, etc.)
- **Respect robots.txt** unless specifically authorized to override

### During Crawl Monitoring
**Performance Monitoring:**
- Monitor **crawl speed** and adjust if government site performance degrades
- Watch for **error rates** indicating server stress
- **Pause crawl** if contacted by government IT team
- **Resume during appropriate hours** if crawl needs to be stopped

**Data Quality Checks:**
- Monitor **response codes** for unusual patterns
- Check **redirect chains** for potential site structure issues
- Validate **content extraction** is working properly
- Ensure **image analysis** is capturing alt text data

---

## CRAWL EXECUTION WORKFLOW

### Step 1: Initial Small Crawl
1. **Test crawl with 100 URL limit** first
2. **Verify crawler access** and server response
3. **Check data quality** in initial results
4. **Adjust settings** based on initial findings

### Step 2: Comprehensive Crawl
1. **Remove URL limit** (or set to site-appropriate limit)
2. **Start full crawl** during agreed timeframe
3. **Monitor progress** and server response
4. **Document any issues** or interruptions

### Step 3: Data Export and Backup
1. **Export data immediately** after crawl completion
2. **Save Screaming Frog configuration** for future audits
3. **Backup raw data files** to secure government-approved storage
4. **Document crawl parameters** for audit trail

---

## DATA EXPORT AND ANALYSIS

### Essential Data Exports
**Required Exports for Government Audit:**
1. **All Pages Export** (File > Export > All Pages)
   - Complete page inventory with response codes
   - Essential for comprehensive site analysis

2. **Images Export** (File > Export > Images)
   - Critical for accessibility compliance analysis
   - Alt text evaluation for Section 508 compliance

3. **Internal Links Export** (File > Export > Links > Internal)
   - Site structure and navigation analysis
   - User journey optimization planning

4. **Page Titles Export** (File > Export > Page Titles)
   - Content quality and SEO analysis
   - Government content standards compliance

**Export Format Recommendations:**
- **Use Excel format (.xlsx)** for government stakeholder review
- **CSV format** for technical analysis and processing
- **Include all columns** for comprehensive analysis

### Export Organization
**File Naming Convention:**
```
[Agency]-[Crawl-Type]-[Date]-[Version].[extension]

Examples:
Denver-Parks-Complete-Crawl-2024-03-15-v1.xlsx
Denver-Parks-Images-Audit-2024-03-15-v1.xlsx
Denver-Parks-Internal-Links-2024-03-15-v1.xlsx
```

**Folder Structure:**
```
screaming-frog-audit-[agency]/
├── raw-exports/
│   ├── complete-crawl-export.xlsx
│   ├── images-export.xlsx
│   ├── links-export.xlsx
│   └── page-titles-export.xlsx
├── configuration/
│   └── crawl-configuration.screamingfrogconfig
└── documentation/
    ├── crawl-log.txt
    └── audit-parameters.md
```

---

## GOVERNMENT-SPECIFIC ANALYSIS FOCUS

### Accessibility Compliance Analysis
**Image Alt Text Review:**
- Export all images with missing alt text
- Identify decorative vs. functional images
- Document accessibility compliance gaps
- Prioritize fixes for citizen-facing content

**Content Structure Analysis:**
- Review heading structure (H1, H2, H3) for logical hierarchy
- Identify pages with missing or duplicate titles
- Document content organization issues
- Plan information architecture improvements

### Performance and Technical Issues
**Response Code Analysis:**
- Document all 404 (Not Found) errors for citizen impact
- Identify redirect chains affecting user experience
- Flag server errors (500 series) requiring IT attention
- Map broken internal links for navigation improvements

**Content Quality Issues:**
- Identify duplicate content across government services
- Document missing meta descriptions for public pages
- Flag thin content that doesn't serve citizen needs
- Review content freshness and accuracy

---

## TROUBLESHOOTING COMMON ISSUES

### Crawl Performance Issues
**Slow Crawling:**
- Reduce **crawl speed** (increase delay between requests)
- Decrease **number of threads** to reduce server load
- Check **government network** for bandwidth limitations
- **Coordinate with IT** team if persistent issues

**Memory Issues:**
- Increase **JVM memory allocation** in system settings
- **Exclude large file types** if not needed for audit
- **Crawl in segments** for very large government sites
- **Use 64-bit version** for large site crawls

### Access and Permission Issues
**403 Forbidden Errors:**
- **Verify IP allowlisting** with government IT team
- **Check robots.txt** for crawler restrictions
- **Confirm crawl authorization** with appropriate government staff
- **Adjust user agent** if required by government security

**Rate Limiting:**
- **Increase crawl delay** to respect server limits
- **Reduce concurrent threads** to lower request rate
- **Schedule crawling** during low-traffic periods
- **Work with IT team** to adjust rate limits if necessary

### Data Quality Issues
**Missing Content Extraction:**
- **Verify extraction settings** are enabled
- **Check content type configuration** for government site structure
- **Test extraction** on sample pages manually
- **Adjust timeout settings** for slow-loading government content

---

## SECURITY AND PRIVACY CONSIDERATIONS

### Data Protection
**Sensitive Information Handling:**
- **Do not crawl** password-protected or admin areas
- **Exclude personal information** from crawl scope
- **Secure storage** of crawl data on government-approved systems
- **Data retention** following government records retention policies

**Government Security Requirements:**
- **Coordinate with security team** before crawling
- **Use approved networks** for accessing government sites
- **Document security measures** in audit methodology
- **Report security issues** discovered during crawl to appropriate teams

### Compliance Documentation
**Audit Trail Requirements:**
- **Document crawl parameters** and configuration
- **Log crawl dates and times** for government records
- **Maintain crawler configuration files** for audit purposes
- **Record any issues or anomalies** during crawling process

---

## ADVANCED CONFIGURATION

### Large Government Site Optimization
**Enterprise Site Settings:**
- **Increase memory allocation** to 8GB+ for large sites
- **Use multiple crawl sessions** for sites with >100,000 pages
- **Configure selective crawling** by directory or content type
- **Set up automated crawling** for regular audits

**Multi-Site Government Crawling:**
- **Configure subdomain inclusion** for comprehensive agency audit
- **Set up separate crawls** for different agency divisions
- **Coordinate crawling schedules** across multiple government sites
- **Standardize configuration** across all agency sites

### Integration with Analysis Tools
**Data Export for Analysis:**
- **Configure custom exports** for specific government compliance needs
- **Set up automated exports** for regular government reporting
- **Integrate with accessibility testing** tools and workflows
- **Prepare data formats** for Claude analysis prompts

---

## SUCCESS CHECKLIST

### Pre-Crawl Setup
- [ ] Screaming Frog installed and configured appropriately
- [ ] Government IT team notified and coordination completed
- [ ] Crawl scope and limitations agreed upon
- [ ] Security and access requirements addressed
- [ ] Initial test crawl completed successfully

### During Crawl
- [ ] Crawl proceeding at appropriate speed without server stress
- [ ] Data extraction working correctly for government compliance needs
- [ ] No security or access issues encountered
- [ ] Progress monitoring and documentation maintained

### Post-Crawl
- [ ] Complete data export completed and verified
- [ ] Raw data backed up to secure government-approved storage
- [ ] Crawl configuration saved for future reference
- [ ] Initial data quality review completed
- [ ] Ready for technical analysis using Claude prompts

---

## SUPPORT AND RESOURCES

### Technical Support
- **Screaming Frog Documentation:** https://www.screamingfrog.co.uk/seo-spider/user-guide/
- **Government IT Coordination:** Work with agency IT team for site-specific issues
- **CivicSpeed Methodology:** Reference technical audit documentation for analysis

### Training Resources
- **Basic Training:** Screaming Frog online tutorials and documentation
- **Government-Specific Training:** Agency-specific training on government compliance requirements
- **Advanced Features:** Screaming Frog advanced configuration documentation

---

**Remember:** Screaming Frog is a powerful tool that can provide comprehensive technical insights, but it must be used respectfully and in coordination with government IT teams to ensure both effective auditing and responsible use of government resources.

**Next Step:** After completing Screaming Frog setup and crawling, use the exported data with the Website Audit Analysis Prompt to generate actionable insights for government digital transformation.
