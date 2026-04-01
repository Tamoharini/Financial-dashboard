💸 FinFlow — Finance Dashboard

A clean, responsive, and interactive finance dashboard built using pure HTML, CSS, and JavaScript — no frameworks, no build tools.

📊 Visualized with Chart.js | 💾 Powered by localStorage | ⚡ Zero dependencies

✨ Features
📊 Dashboard Overview
Summary cards:
Total Balance
Total Income
Total Expenses
Savings Rate
📈 Balance trend chart (last 6 months)
🍩 Spending breakdown (donut chart by category)
📊 Income vs Expenses (monthly bar chart)
📉 Transaction volume (by day of week)
💳 Transactions
Full transaction table:
Date, Description, Category, Type, Amount
🔍 Search by keyword or category
🎯 Filters:
Type (Income / Expense)
Category
Month
⬍ Sortable columns (ascending / descending)
📄 Pagination (8 transactions per page)
🔑 Role-Based UI
Role	Capabilities
Viewer	Read-only access
Admin	Add, edit, delete transactions
Switch roles via dropdown (top-right)
Role persists after refresh
💡 Insights
Highest spending category
Average monthly expense
Total savings & savings rate
Month-over-month spending change
Largest single expense
Transaction count breakdown
⚙️ Additional Features
🌙 Dark / Light mode toggle
💾 Data persistence using localStorage
📤 Export data:
CSV
JSON
📱 Fully responsive design
🔔 Toast notifications for user actions
📦 40 pre-seeded mock transactions (4 months)
🛠 Tech Stack
Layer	Technology
Markup	HTML5
Styling	Vanilla CSS (CSS Variables)
Logic	JavaScript (ES6+)
Charts	Chart.js (CDN)
Storage	localStorage
Build Tool	None
🎭 Role Switching
Locate the role dropdown (top-right)
Select:
Admin → Full access
Viewer → Read-only mode
Role is saved automatically
📤 Exporting Data
Click Export (top bar)
Choose:
CSV
JSON
File downloads instantly
🌙 Dark Mode
Toggle using 🌙 / ☀️ icon (top-right)
Preference is saved automatically
📱 Responsive Design
Screen Size	Layout
Desktop (>900px)	Sidebar + full layout
Tablet/Mobile	Bottom navigation + stacked layout
💡 Assumptions
Uses mock/static data (no backend)
Role-based access is UI-only (not secure)
Currency is fixed to USD ($)
Requires browser support for localStorage
