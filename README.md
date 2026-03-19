# ☕ Café Profit & Loss — Waste Awareness Tracker

A lightweight, interactive web tool designed for café owners and managers to visualize how unsold inventory (waste) directly impacts their weekly bottom line.

## 🚀 Overview
Most trackers focus only on sales. This tool emphasizes the **cost of waste**. By inputting unit prices, production costs, and actual quantities sold vs. wasted, users get a real-time calculation of their net profit and a clear look at "lost" potential.

### Key Features
* **Real-time Calculations:** See profit margins and waste impact update instantly as you type.
* **Waste Impact Visualization:** Highlights exactly how much money is lost to the cost of unsold goods.
* **Efficiency Insights:** Automatically calculates how much profit would increase if waste was reduced by 20%.
* **Mobile-First Design:** Clean, responsive interface that works perfectly on tablets and phones in a kitchen or shop environment.

---

## 🛠️ How It Works
The app uses a simple formula to determine the health of each product line:

1.  **Net Profit Contribution:** $Units\ Sold \times (Price - Cost)$
2.  **Waste Impact:** $Units\ Wasted \times Cost$
3.  **Weekly Overview:** Sum of all profit contributions minus the total cost of wasted items.

---

## 🗺️ Roadmap
I am actively working on improving this tracker. Planned updates include:

- [ ] **Dynamic Product Management:** Add the ability to add new product cards and delete old ones directly from the UI.
- [ ] **Local Storage:** Save your data so it persists even after refreshing the browser.
- [ ] **Export to CSV:** Download your weekly summary for use in Excel or Google Sheets.
- [ ] **Dark Mode:** A toggle for better visibility in different lighting conditions.

---

## 💻 Tech Stack
* **HTML5/CSS3:** Using modern CSS variables and Flexbox/Grid for a sleek, "app-like" feel.
* **Vanilla JavaScript:** Lightweight and fast with no external dependencies or frameworks required.

## 📥 Installation
1.  Clone this repository:
    ```bash
    git clone [https://github.com/your-username/cafe-waste-tracker.git](https://github.com/your-username/cafe-waste-tracker.git)
    ```
2.  Open `index.html` in any modern web browser.
3.  That's it! No build process required.

---

### 💡 Why I built this
I wanted a tool that didn't just show "sales," but showed the **cost of inefficiency**. This helps small business owners make better decisions about production volume to maximize their weekly take-home pay.
