---
layout: default
title: "Dynamic Email Generator"
permalink: /projects/dynamic-email-generator/
---

# Dynamic Email Generator

## Project Overview

This project showcases a Python-based tool designed to automatically generate personalized marketing emails using structured customer data. The email generator applies dynamic string formatting and conditional logic to produce scalable, customized messages — an essential automation task in modern marketing operations.

---

## Objective

The assignment focused on building a solution that:
- Loops through a list of customers
- Dynamically formats personalized emails
- Applies fallbacks for missing names (e.g., "Valued Customer")
- Uses conditionals to insert product category and promotion hooks

The challenge was to adhere to formatting rules, apply proper logic, and scale output generation without altering the original data source.

---

## Tools and Technologies

- **Python 3**
  - String formatting
  - Control flow (if/else)
  - Lists and loops
- **Jupyter Notebook**
  - Interactive coding and markdown documentation
- **Markdown** for final report formatting

---

## ⚙Methodology

### 1. Data Setup  
The project uses pre-defined lists representing customer data, including name, category interest, marketing hooks, and promotion codes.

### 2. Email Generation Logic  
A custom Python function was developed that:
- Iterates through the customer list
- Checks for missing names and replaces them with “Valued Customer”
- Dynamically inserts category-specific messages and unique promotion codes
- Uses clear formatting (line breaks, signature block)

### 3. Output  
The final script prints a fully formatted set of emails, ready to be copy-pasted or integrated into an automated campaign tool.

---

## Results

-  Generated 20+ personalized emails with 100% accuracy.
-  Successfully applied fallback logic and string personalization.
-  Built reusable code structure for future marketing automation tasks.

---

## Key Learning Outcomes

- Applied Python fundamentals in a real-world context (email marketing)
- Practiced clean and readable string construction
- Gained experience balancing logic flow and design formatting
- Reinforced the value of automating repetitive communication tasks

---

## Repository

View the full Jupyter Notebook and source code in my GitHub repository:  
🔗 [Dynamic Email Generator – GitHub Project](https://github.com/TrustMadade/Projects/blob/main/email-generator/Dynamic-Email-Generator.ipynb)

---

## Next Steps

To scale this prototype further:
- Integrate with a CSV-based customer database
- Use HTML email formatting for responsive layout
- Add tracking parameters (e.g., UTM links) for performance measurement

---

*This project was developed as part of Introduction to Python course fulfillment at Hult International Business School.*


