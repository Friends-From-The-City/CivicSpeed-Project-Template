# Comprehensive Prototype Building Guide for CivicSpeed Workflow

Build a [type of application] that [main purpose/goal].

## Application Types & When to Use Them

### **React Components** - *Interactive Web Applications*
```javascript
// Use for: Dynamic dashboards, data visualization, complex user interfaces
// Example functionality: Real-time updates, user authentication, multi-step forms
// Specify like: "Build a React component that allows users to filter and sort civic data"
```
**Best for:** Complex user interactions, data manipulation, reusable components
**Technologies included:** JSX, React hooks (useState, useEffect), event handling

### **HTML Applications** - *Complete Web Experiences*
```html
<!-- Use for: Full websites, landing pages, marketing sites, portfolios -->
<!-- Example functionality: Interactive animations, responsive design, embedded media -->
<!-- Specify like: "Create an HTML app with smooth scrolling navigation and contact forms" -->
```
**Best for:** Complete websites, content-heavy applications, SEO-friendly pages
**Technologies included:** HTML5, CSS3, JavaScript, responsive design

### **Data Visualizations** - *Charts and Analytics*
```javascript
// Use for: Reporting dashboards, analytics, trend analysis, KPI monitoring
// Available libraries: Recharts, D3.js, Chart.js, Plotly
// Specify like: "Create a dashboard showing budget allocation with interactive pie charts"
```
**Best for:** Making data understandable, executive reporting, public transparency

---

## **Core Features:**
- [Feature 1: Specify user interaction - "Users can upload CSV files and see instant visualizations"]
- [Feature 2: Define data manipulation - "Filter data by date range, department, or budget category"] 
- [Feature 3: Describe output - "Export filtered results as PDF reports or share via unique URLs"]

## **Technology Stack Requirements:**

### **Frontend Frameworks** *(Choose One)*

#### **React** - *Most Powerful for Complex Apps*
```javascript
// When to use: Multi-step processes, user accounts, real-time updates
// Functionality examples:
// - useState for form data management
// - useEffect for API calls and data fetching
// - Event handlers for user interactions
// - Conditional rendering for different user states
```

#### **HTML/CSS/JavaScript** - *Best for Content & Marketing*
```html
<!-- When to use: Informational sites, landing pages, simple interactions -->
<!-- Functionality examples: -->
<!-- - CSS animations and transitions -->
<!-- - JavaScript for form validation -->
<!-- - Responsive grid layouts -->
<!-- - Interactive elements (modals, dropdowns) -->
```

### **Styling Approaches** *(Choose One)*

#### **Tailwind CSS** - *Rapid Prototyping* ⭐ *Recommended for Claude*
```css
/* Use for: Quick styling, consistent design systems, responsive design */
/* Examples: bg-blue-500 hover:bg-blue-700 transition-colors duration-300 */
/* Specify like: "Use a modern dark theme with blue accents and smooth animations" */
```

#### **Custom CSS** - *Unique Designs*
```css
/* Use for: Branded experiences, complex animations, specific design requirements */
/* Examples: Custom color schemes, unique layouts, advanced animations */
/* Specify like: "Create a civic-themed color palette with government blue and gold accents" */
```

### **Data Management** *(Choose Based on Data Source)*

#### **Static Data** - *Demos and Prototypes*
```javascript
// Use for: Sample data, demos, proof of concepts
// Example: const civicData = [{department: "Parks", budget: 2000000, projects: 15}]
// Specify like: "Use sample municipal budget data for 5 departments"
```

#### **File Upload Processing** - *User-Provided Data*
```javascript
// Use for: CSV uploads, Excel files, user-generated content
// Libraries: Papaparse (CSV), SheetJS (Excel), Mammoth (Word docs)
// Specify like: "Allow users to upload budget CSVs and automatically parse columns"
```

#### **API Integration** - *Live Data Sources*
```javascript
// Use for: Government APIs, real-time data, third-party services
// Example: fetch('https://api.data.gov/civic/budgets')
// Specify like: "Connect to city's open data API for real-time budget information"
```

### **Interactive Features** *(Mix and Match)*

#### **Data Visualization**
```javascript
// Libraries: Recharts (simple), D3 (advanced), Plotly (scientific)
// Use cases:
// - LineChart: Budget trends over time
// - BarChart: Department comparisons  
// - PieChart: Budget allocation breakdown
// - Heatmap: Geographic data visualization
// Specify like: "Show budget trends with interactive line charts that highlight on hover"
```

#### **User Interface Components**
```javascript
// Common components:
// - Forms: Multi-step wizards, validation, file uploads
// - Navigation: Tabs, breadcrumbs, sidebar menus
// - Feedback: Toast notifications, progress bars, loading states
// - Data Tables: Sorting, filtering, pagination, search
// Specify like: "Include a searchable data table with export functionality"
```

#### **Advanced Interactions**
```javascript
// Map Integration: Interactive maps with data overlays
// Real-time Updates: Live data feeds, websocket connections  
// Drag & Drop: File uploads, reorderable lists, dashboard widgets
// Animation: Page transitions, loading animations, micro-interactions
// Specify like: "Add an interactive map showing project locations with budget overlays"
```

---

## **Design Style Guidelines:**

### **Modern Civic Design**
- Clean, professional layouts with plenty of white space
- Accessible color contrasts (WCAG compliant)
- Clear typography hierarchy
- Mobile-first responsive design

### **Visual Styles** *(Choose One)*
```css
/* Minimal: Clean lines, lots of white space, simple color palette */
/* Professional: Corporate-friendly, blue/gray themes, standard layouts */
/* Vibrant: Colorful, engaging, modern gradients and animations */
/* Accessible: High contrast, large fonts, keyboard navigation support */
```

---

## **Requirements Template:**

**Technology preference:** 
```
- React (for complex interactions) OR HTML (for content-focused)
- Tailwind CSS (for rapid styling)
- [Specific libraries: Recharts for charts, D3 for advanced visualizations]
```

**Design style:** 
```
- Modern civic design with [color scheme]
- Responsive layout optimized for [desktop/mobile/both]
- Accessibility features: [screen reader support, keyboard navigation, high contrast]
```

**Specific functionality:**
```javascript
// Data Processing: "Parse uploaded CSV files and validate required columns"
// User Interface: "Provide filtering by date, department, and amount ranges"  
// Visualizations: "Generate interactive charts that update based on filters"
// Export Features: "Allow download of filtered data as CSV or PDF reports"
// Responsive Design: "Ensure full functionality on mobile devices"
```

**Performance Requirements:**
```javascript
// Speed: "Load initial data within 2 seconds"
// Scalability: "Handle datasets up to 10,000 rows smoothly"  
// Browser Support: "Work in Chrome, Firefox, Safari, Edge"
// Offline Features: "Cache data for offline viewing"
```

---

## **User Flow:**
[Brief description of how users should interact with it]

**Example User Flows:**
1. **Data Upload Flow:** "User uploads CSV → System validates data → Shows preview → User confirms → Redirects to dashboard"
2. **Analysis Flow:** "User selects filters → Charts update in real-time → User explores data → Exports results"
3. **Reporting Flow:** "User generates report → Customizes layout → Downloads or shares via URL"

---

## **Data/Content:**

### **Sample Data Types:**
```javascript
// Municipal Budget Data:
// {department: "Parks", budget: 2000000, spent: 1200000, projects: ["Park Renovation", "Trail Maintenance"]}

// Civic Engagement Data:
// {meeting_id: "city_council_2024_01", attendees: 45, topics: ["Budget", "Zoning"], feedback_scores: [4.2, 3.8]}

// Performance Metrics:
// {service: "Waste Collection", response_time: "24hrs", satisfaction: 4.1, cost_per_service: 25.50}
```

### **Data Specifications:**
- **Format:** CSV, JSON, Excel, or API endpoints
- **Size:** Specify expected data volume (100 rows vs 10,000 rows)
- **Update Frequency:** Static, daily, real-time
- **Required Fields:** List essential columns/properties
- **Sample Data:** "Generate realistic sample data for [specific civic domain]"

---

## **Advanced Prototype Features:**

### **AI Integration**
```javascript
// Use Claude for: Content generation, data analysis, user assistance
// Example: "Include a chat interface where users can ask questions about the budget data"
```

### **Collaboration Features**
```javascript
// Comments: "Allow users to add notes to specific data points"
// Sharing: "Generate shareable links with specific filters applied"  
// Version Control: "Track changes to data over time"
```

### **Automation**
```javascript
// Scheduled Reports: "Automatically generate monthly budget summaries"
// Data Alerts: "Notify users when spending exceeds thresholds"
// Workflow Integration: "Export data to external systems via API"
```

---

## **Example Complete Specifications:**

### **Civic Budget Dashboard**
```
Build a React component that provides interactive budget analysis for municipal departments.

Core Features:
- Upload and parse municipal budget CSV files with data validation
- Interactive filtering by department, date range, and expense category
- Real-time chart updates showing spending trends and budget vs actual comparisons
- Export functionality for filtered data and generated reports

Technology: React with Tailwind CSS, Recharts for visualizations, Papaparse for CSV processing
Design: Professional civic theme with blue/gray color scheme, fully responsive
User Flow: File upload → data validation → filter selection → chart interaction → export results
Data: Municipal budget data with columns: department, category, budgeted_amount, actual_spend, date
```

### **Public Meeting Dashboard**
```
Build an HTML application that displays public meeting information and engagement metrics.

Core Features:
- Calendar view of upcoming civic meetings with filtering by department/topic
- Real-time attendance tracking and participant engagement scores  
- Public comment submission form with moderation queue
- Meeting archive with searchable transcripts and voting records

Technology: HTML/CSS/JavaScript with Chart.js, responsive design, local storage for user preferences
Design: Accessible design with high contrast, large fonts, keyboard navigation support
User Flow: View calendar → select meeting → read agenda → submit comments → view results
Data: Meeting schedules, attendance records, public comments, voting data from city API
```

---

---

# 🚀 **MASTER PROMPT TEMPLATE**
*Copy and customize this comprehensive prompt for high-performance prototypes*

## **Master High-Performance Website Prompt**

```
Build a [APPLICATION_TYPE] that [PRIMARY_GOAL] with enterprise-grade performance and modern web standards.

**CORE TECHNOLOGY STACK:**

Frontend Framework: [React/HTML] with modern JavaScript (ES2024+)
Styling: Tailwind CSS with custom design system and CSS Grid/Flexbox
Performance: Optimized for Core Web Vitals (LCP <2.5s, FID <100ms, CLS <0.1)
Responsiveness: Mobile-first design with breakpoints for tablet/desktop/4K
Accessibility: WCAG 2.1 AA compliance with screen reader support

**PERFORMANCE OPTIMIZATIONS:**
- Lazy loading for images and components
- Code splitting for faster initial load
- Optimized asset delivery (WebP images, minified CSS/JS)
- Efficient state management with minimal re-renders
- Progressive enhancement for offline functionality

**MODERN WEB FEATURES:**
- CSS Custom Properties (variables) for consistent theming
- CSS Grid and Flexbox for advanced layouts
- Intersection Observer API for scroll-triggered animations
- Web Components architecture for reusability
- Service Worker for caching and offline support
- Progressive Web App (PWA) capabilities

**USER EXPERIENCE:**
- Smooth 60fps animations and micro-interactions
- Intuitive navigation with breadcrumbs and search
- Loading states and error handling for all user actions
- Keyboard navigation and focus management
- Dark/light mode toggle with system preference detection

**DATA ARCHITECTURE:**
[Choose and customize from sections below]

**SPECIALIZED FEATURES:**
[Choose and customize from modules below]

[SPECIFIC_REQUIREMENTS]
[USER_FLOW_DESCRIPTION]
[DATA_SPECIFICATIONS]
```

---

# 📊 **SPECIALIZED MODULES**
*Add these sections to your master prompt as needed*

## **DATA VISUALIZATION MODULE**
```
**ADVANCED DATA VISUALIZATION STACK:**

Chart Libraries:
- Recharts: For standard business charts (bar, line, pie, area)
- D3.js: For custom visualizations and geographic data
- Plotly: For scientific/statistical visualizations
- Chart.js: For simple, animated charts

Visualization Types:
- Time Series: Interactive line charts with zoom/pan functionality
- Comparative: Multi-axis charts with drill-down capabilities  
- Geographic: Interactive maps with data overlays using D3 + TopoJSON
- Network: Node-link diagrams for relationship data
- Statistical: Box plots, violin plots, regression analysis
- Real-time: Live updating dashboards with WebSocket connections

Interactive Features:
- Hover tooltips with detailed information
- Click-through navigation to detailed views
- Brush selection for data filtering
- Animated transitions between chart states
- Export capabilities (PNG, SVG, PDF, CSV)

Performance for Large Datasets:
- Virtual scrolling for 10,000+ data points
- Data aggregation and sampling strategies
- Canvas rendering for complex visualizations
- Web Workers for heavy data processing
```

## **ADVANCED DATA PROCESSING MODULE**
```
**ENTERPRISE DATA HANDLING:**

File Processing:
- CSV/Excel: Papaparse + SheetJS with data validation
- JSON: Schema validation with error reporting
- Real-time APIs: Fetch with retry logic and caching
- Streaming: Large file processing with progress indicators

Data Transformation:
- Lodash for complex data operations (groupBy, filtering, aggregation)
- Date handling with proper timezone support
- Currency and number formatting with internationalization
- Data cleaning: null handling, type conversion, validation

State Management:
- React: useState/useReducer for local state
- Global state: Context API for shared data
- Caching: Intelligent data caching with expiration
- Persistence: Local storage with data versioning

Performance Optimization:
- Memoization for expensive calculations
- Debounced search and filtering
- Pagination for large datasets
- Background data prefetching
```

## **MODERN UI/UX MODULE**
```
**CUTTING-EDGE USER INTERFACE:**

Design System:
- Consistent spacing scale (4px, 8px, 16px, 32px)
- Typography hierarchy with optimal line heights
- Color palette with semantic naming (primary, secondary, success, warning)
- Component library with consistent props and behavior

Advanced Interactions:
- Gesture support for mobile (swipe, pinch, long-press)
- Drag and drop with visual feedback
- Multi-select with keyboard shortcuts
- Undo/redo functionality for user actions
- Auto-save with conflict resolution

Micro-Animations:
- Page transitions with meaningful motion
- Loading skeletons for content placeholders
- Hover effects that provide visual feedback
- Form validation with smooth error states
- Success animations for completed actions

Responsive Excellence:
- Container queries for component-based responsive design
- Fluid typography that scales with viewport
- Touch-friendly tap targets (44px minimum)
- Optimal layouts for all screen sizes
- Print-friendly styles for reports
```

## **ENTERPRISE FEATURES MODULE**
```
**PRODUCTION-READY CAPABILITIES:**

Security:
- Input sanitization and XSS prevention
- CSRF protection for form submissions
- Content Security Policy (CSP) headers
- Secure authentication flows

Performance Monitoring:
- Core Web Vitals tracking
- Error boundary implementation with logging
- Performance metrics collection
- User analytics and behavior tracking

Scalability:
- Component-based architecture for maintainability
- Modular CSS with utility-first approach
- Efficient bundle splitting and tree shaking
- Database query optimization patterns

Developer Experience:
- TypeScript support for type safety
- Comprehensive error handling with user-friendly messages
- Debugging tools and development mode features
- Automated testing capabilities
```

## **API INTEGRATION MODULE**
```
**MODERN API ARCHITECTURE:**

REST API Integration:
- Fetch with automatic retry and timeout handling
- Response caching with TTL (time-to-live)
- Error handling with user-friendly messages
- Loading states for all async operations

Real-time Features:
- WebSocket connections for live updates
- Server-Sent Events for notifications
- Optimistic UI updates with rollback capability
- Conflict resolution for concurrent edits

Data Synchronization:
- Offline-first architecture with sync on reconnect
- Background data fetching and caching
- Delta updates for efficient bandwidth usage
- Version control for data conflicts

Authentication:
- JWT token management with automatic refresh
- Role-based access control (RBAC)
- Single sign-on (SSO) integration
- Secure logout with token cleanup
```

---

# 🎯 **QUICK-START TEMPLATES**
*Ready-to-use prompts for common scenarios*

## **Civic Dashboard Template**
```
Build a React component that creates a high-performance civic transparency dashboard.

[INSERT MASTER PROMPT ABOVE]

**SPECIALIZED FEATURES:**
[DATA VISUALIZATION MODULE]
[ADVANCED DATA PROCESSING MODULE]
[MODERN UI/UX MODULE]

**CIVIC-SPECIFIC REQUIREMENTS:**
- Government accessibility compliance (Section 508)
- Multi-language support for diverse communities
- Public data API integration with automatic updates
- Citizen feedback collection and moderation
- Budget data visualization with drill-down capabilities
- Meeting schedule integration with calendar exports
- Document search with full-text indexing
- Mobile-optimized for citizen access on any device

User Flow: Landing page → department selection → data filtering → visualization interaction → report generation → sharing/export
Data: Municipal budget, meeting records, public documents, citizen feedback via city open data APIs
```

## **Analytics Dashboard Template**
```
Build an HTML application that provides enterprise-level analytics and reporting.

[INSERT MASTER PROMPT ABOVE]

**SPECIALIZED FEATURES:**
[DATA VISUALIZATION MODULE - Focus on D3.js and Plotly]
[ENTERPRISE FEATURES MODULE]
[API INTEGRATION MODULE]

**ANALYTICS-SPECIFIC REQUIREMENTS:**
- Real-time data streaming with automatic refresh
- Advanced filtering with saved filter sets
- Custom report builder with drag-drop interface
- Scheduled report generation and email delivery
- Data export in multiple formats (CSV, Excel, PDF, JSON)
- Role-based dashboard customization
- Performance metrics and KPI tracking
- A/B testing framework for feature rollouts

User Flow: Login → dashboard overview → metric deep-dive → custom report creation → scheduling/sharing
Data: Time-series analytics, user behavior data, performance metrics via REST APIs and WebSocket streams
```

## **Content Management Template**
```
Build a React component that provides modern content creation and management capabilities.

[INSERT MASTER PROMPT ABOVE]

**SPECIALIZED FEATURES:**
[MODERN UI/UX MODULE]
[ENTERPRISE FEATURES MODULE]
[ADVANCED DATA PROCESSING MODULE - Focus on file handling]

**CMS-SPECIFIC REQUIREMENTS:**
- Rich text editor with markdown support
- Media library with drag-drop upload and optimization
- Version control for all content with diff viewing
- Collaborative editing with real-time presence indicators
- SEO optimization tools with preview functionality
- Content scheduling and workflow management
- Multi-site management from single interface
- Advanced search with faceted filtering

User Flow: Content overview → create/edit → preview → collaboration → approval workflow → publishing
Data: Content records, media files, user permissions, workflow states via headless CMS API
```

---

*This comprehensive guide provides everything needed to specify enterprise-grade prototypes with modern web technologies, optimized for performance and user experience.*
