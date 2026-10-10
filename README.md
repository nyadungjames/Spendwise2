# SpendWise - Budget Tracker (Week 2)

**What I built:** A simple expense tracking web page that lists expenses in a table and has a form to add new expenses.

**What each part does:**
- **index.html:** Contains header with logo (img tag), expense table using <table>, <thead>, <tbody>, <tr>, <th>, <td>, a form with <select> for categories (Food, Transport, Rent, Entertainment, Other), a <details> section for instructions, and an <iframe> YouTube video.
- **styles.css:** Styles the table with border-collapse, padding, colored header, alternating rows using tr:nth-child(even). Uses advanced selectors: descendant (.expenses-section td), direct child (.add-expense-section > form > input), negation (input:not), focus (input:focus), and hover (tr:hover).
- **script.js:** Will be used in Week 6/7 for interactivity.

**Rubric Covered:** Table Structure (25%), Form Upgrade (30%), Multimedia (15%), Advanced Selectors (30%)