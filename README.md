# 📊 Sales Dashboard

A modern and responsive **Sales Dashboard UI** built with **HTML, CSS, and JavaScript**. The dashboard provides a clean interface for viewing sales performance, analytics, visits, and other business metrics.

## ✨ Features

- 📈 Sales performance overview
- 💰 Revenue and sales metrics
- 📊 Analytics chart
- 🎯 Sales performance score
- 🗓️ Visit-by-time heatmap
- 👥 Mobile vs Website visitor statistics
- 🔔 Notification indicator
- 👤 User profile section
- 📱 Responsive layout for desktop, tablet, and mobile
- 📂 Mobile sidebar navigation
- 🖱️ Click-outside behavior for closing the mobile sidebar
- 🎨 Modern card-based dashboard design
- ⭐ Font Awesome icons

## 🛠️ Technologies Used

- **HTML5** — Structure and content
- **CSS3** — Styling, layout, responsive design, animations
- **JavaScript** — Mobile sidebar interaction
- **Font Awesome 6.4.0** — Icons
- **SVG** — Charts and visual elements

## 📁 Project Structure

```text
sales-dashboard/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

### `index.html`

Contains the main dashboard structure, including:

- Sidebar navigation
- Top navigation bar
- Search bar
- User profile
- Sales metric cards
- Sales performance section
- Analytics section
- Visit heatmap
- Total visitor section

### `style.css`

Contains the complete visual styling for the dashboard, including:

- Layout
- Colors
- Cards
- Sidebar
- Navigation
- Charts
- Buttons
- Responsive breakpoints
- Mobile navigation behavior

### `script.js`

Handles the mobile sidebar functionality.

The JavaScript allows users to:

- Open and close the sidebar
- Close the sidebar when clicking outside it on smaller screens

## 📱 Responsive Design

The dashboard is designed to adapt to different screen sizes.

### Desktop

The dashboard displays:

- Fixed sidebar
- Full top navigation
- Search bar
- Profile information
- Multi-column dashboard cards

### Tablet

At smaller desktop/tablet widths, the layout adjusts by:

- Reducing available column sizes
- Stacking larger content sections
- Adjusting the search bar
- Making dashboard cards more flexible

### Mobile

On mobile devices:

- The sidebar is hidden by default
- A hamburger menu is displayed
- The sidebar slides into view when opened
- The search bar is hidden
- Profile information is simplified
- Dashboard cards become single-column
- Charts and content adjust to the smaller screen

## 🚀 Getting Started

### 1. Download or clone the project

```bash
git clone YOUR_REPOSITORY_URL
```

### 2. Open the project

Open the project folder in your code editor.

### 3. Run the dashboard

Open:

```text
index.html
```

in your web browser.

No backend or installation is required.

## 📊 Dashboard Sections

### Sales Metrics

The dashboard displays metrics such as:

- Active Sales
- Product Revenue
- Product Sold
- Percentage performance

Each metric includes a comparison with the previous month.

### Sales Performance

The sales performance section includes:

- Performance score
- Score indicator
- Team performance message
- Improvement link

### Analytics

The analytics section contains a monthly bar chart showing revenue information.

Users can also see:

- Filter button
- Year selection
- Expand button
- Monthly performance bars

### Visit by Time

The heatmap displays visitor activity across different periods of the day and days of the week.

### Total Visits

The total visits section shows:

- Total visitors
- Monthly percentage change
- Mobile visitors
- Website visitors
- Donut chart showing the distribution

## 📱 Mobile Sidebar

The mobile menu uses JavaScript to toggle the `active` class on the sidebar.

Example:

```javascript
function toggleSidebar() {
    const sidebar = document.getElementById("sidebar");

    if (sidebar) {
        sidebar.classList.toggle("active");
    }
}
```

When the sidebar has the `active` class, CSS displays it on smaller screens.

The sidebar can also close when the user clicks outside it.

## 🎨 Design

The dashboard uses a clean business-oriented design with:

- White cards
- Light gray background
- Rounded corners
- Orange accent colors
- Minimal shadows
- Simple typography
- Data visualization elements

## 🔧 Future Improvements

Possible improvements include:

- Connect the dashboard to a real database
- Add real-time sales data
- Add interactive charts
- Add dark mode
- Add authentication
- Add working navigation pages
- Add filter functionality
- Add date-range selection
- Improve tablet and mobile layouts
- Add animations and transitions
- Make dashboard statistics dynamic

## 📄 License

This project is available for personal and educational use. You may modify and improve the code for your own projects.

## 👨‍💻 Author

**Onwere Benjamin**

UI/UX & Graphic Designer

Built with HTML, CSS, and JavaScript.
```

This README is ready to save as **`README.md`** in the root of your project. I can also create a simple image/diagram showing how the dashboard's HTML, CSS, and JavaScript work together.