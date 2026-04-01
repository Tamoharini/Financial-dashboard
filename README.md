# Financial-dashboard
💸 FinFlow — Finance Dashboard
A clean and interactive finance dashboard built with pure HTML, CSS, and JavaScript — no frameworks, no build tools, no dependencies except Chart.js for visualizations.

✨ Features
📊 Dashboard Overview
Summary cards — Total Balance, Total Income, Total Expenses, Savings Rate
Balance trend chart (line) — last 6 months
Spending breakdown chart (donut) — by category
Income vs Expenses chart (bar) — monthly comparison
Transaction volume chart (line) — by day of week
💳 Transactions
Full transaction list with Date, Description, Category, Type, and Amount
Search by keyword or category
Filter by type (income/expense), category, and month
Sortable columns — click any header to sort ascending or descending
Pagination — 8 transactions per page
🔑 Role-Based UI
Role	Capabilities
Viewer	Read-only — can view all data, charts, and insights
Admin	Full access — can add, edit, and delete transactions
Switch roles using the dropdown in the top bar. Role is persisted across refreshes.

💡 Insights
Highest spending category
Average monthly expense
Total savings and savings rate
Month-over-month spending change
Largest single expense
Total transaction count breakdown
⚙️ Additional Features
🌙 Dark / Light mode toggle
💾 Data persistence via localStorage
⬇ Export transactions as CSV or JSON
📱 Fully responsive — desktop, tablet, and mobile
🔔 Toast notifications for all actions
40 pre-seeded mock transactions across 4 months
🛠 Tech Stack
Layer	Choice
Markup	HTML5
Styling	Vanilla CSS with CSS Custom Properties
Logic	Vanilla JavaScript (ES6+)
Charts	Chart.js 4.4 (CDN)
Persistence	localStorage
Build Tool	None
🎭 Role Switching
Locate the role dropdown in the top right of the screen
Select Admin to unlock add, edit, and delete capabilities
Select Viewer to return to read-only mode
The selected role persists on page refresh
📤 Exporting Data
Click the Export button in the top bar
Choose CSV or JSON
The file downloads instantly to your device
🌙 Dark Mode
Click the moon/sun icon (🌙 / ☀️) in the top right corner to toggle between light and dark themes. The preference is saved automatically.

📱 Responsive Behavior
Screen Size	Layout
Desktop (>900px)	Sidebar navigation + full layout
Tablet / Mobile (≤900px)	Bottom tab navigation + stacked layout
💡 Assumptions Made
Data is mock/static — no real backend or API
Role-based access is a UI simulation only, not a security implementation
All amounts are in USD ($)
localStorage is available in the browser (standard in all modern browsers)
