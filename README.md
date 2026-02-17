# 🏠 Odoo Real Estate Management Module

A complete custom Real Estate Management System built using the Odoo Framework.  
This project demonstrates backend development skills, ORM usage, and business logic implementation in Odoo.

---

## 🚀 Features

- Property management system
- Property types & tags
- Offers management
- Best offer computation
- Property states (New, Offer Received, Accepted, Sold, Cancelled)
- Salesperson and buyer assignment
- Kanban, List & Form views
- Security access control
- SQL constraints & Python constraints
- Onchange & computed fields

---

## 🧠 Technical Concepts Used

### Odoo Backend
- models.Model
- fields (Char, Float, Many2one, Many2many, One2many)
- @api.depends
- @api.onchange
- @api.constrains
- @api.ondelete

### Business Logic
- Prevent deleting sold properties
- Minimum selling price validation (90% rule)
- Automatic deadline calculation
- Best offer calculation

### Views
- List View (editable)
- Form View
- Kanban View with QWeb templates


## ⚙️ Installation

1. Copy the module into your custom addons folder
2. Update app list in Odoo
3. Install the module "Real Estate"

---

## 🎯 Purpose of this Project

This project is created for:

- Learning Odoo development
- Demonstrating backend engineering skills
- Portfolio for internship/job applications

---

## 👨‍💻 Author

Bappa Saha  
BCSE Student | Machine Learning & Odoo Developer  

---

## ⭐ Future Improvements

- REST API integration
- Payment system
- Report generation (PDF)
- Dashboard analytics
- AI-based property price prediction

---

## 📌 License

This project is open-source and free to use for learning purposes.
