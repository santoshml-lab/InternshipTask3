Semantic HTML5 & Accessible Dashboard

An accessible enterprise dashboard structural foundation built using semantic HTML5 and WCAG 2.1 accessibility principles.

## 🎯 Project Objective

The objective of this project is to build a clean, structured, and accessible enterprise dashboard layout using semantic HTML5.

The project focuses on:

- Semantic HTML5 structure
- Accessible navigation
- Structured DOM hierarchy
- Keyboard accessibility
- Accessible forms and controls
- Accessible data tables
- Native modal dialogs
- WCAG 2.1 accessibility practices
- Valid HTML5 markup
- Responsive styling

## ✨ Features

### Semantic HTML5

The dashboard uses appropriate semantic elements including:

- `<header>`
- `<nav>`
- `<main>`
- `<section>`
- `<article>`
- `<aside>`
- `<footer>`

### ♿ Accessibility

Accessibility-focused features include:

- Skip-to-main-content link
- Descriptive navigation landmarks
- `aria-label` for navigation regions
- `aria-labelledby` for content relationships
- `aria-current="page"` for active navigation
- Keyboard-friendly interactive elements
- Visible focus indicators
- Native HTML validation

### 📊 Accessible Data Tables

The Reports page contains a structured data table using:

- `<caption>`
- `<thead>`
- `<tbody>`
- `<th>`
- `scope="col"`

This provides meaningful table relationships for assistive technologies.

### 📝 Accessible Forms

The Settings page includes:

- Explicit `<label>` elements
- Matching `for` and `id` attributes
- `<fieldset>` and `<legend>`
- Required fields
- Native HTML validation
- Appropriate input types
- `autocomplete` attributes
- Accessible form structure

### 🔔 Accessible Modal Dialog

The dashboard includes a native HTML `<dialog>` element with:

- Descriptive heading
- `aria-labelledby`
- Native dialog behavior
- Keyboard-accessible buttons
- `method="dialog"` for dialog controls

## 🎨 Styling

The project includes a dedicated CSS stylesheet providing:

- Responsive layout
- Dashboard header styling
- Sidebar navigation
- Content sections
- Accessible focus indicators
- Table styling
- Form styling
- Button styling
- Dialog styling
- Mobile-friendly layout

## 📄 Pages

### Overview

Provides the main enterprise dashboard overview with semantic landmarks and accessible navigation.

### Reports

Provides a structured business reports table with accessible table headers and captions.

### Settings

Provides an accessible account settings form with grouped controls and native validation.

## 📁 Project Structure

```text
semantic-dashboard/
│
├── components/
│   ├── header.html
│   ├── sidebar.html
│   ├── footer.html
│   ├── modal.html
│   └── form.html
│
├── pages/
│   ├── overview.html
│   ├── reports.html
│   └── settings.html
│
├── index.html
├── style.css
└── README.md
🧩 Component Structure
The components directory contains reusable structural examples for:
Header and navigation
Sidebar navigation
Footer
Modal dialog
Accessible form controls
These components demonstrate how common enterprise dashboard sections can be structured using semantic and accessible HTML.
🧪 HTML Validation
The HTML documents were validated using the W3C Markup Validation Service.
Final validation results:
index.html — 0 errors, 0 warnings
overview.html — 0 errors, 0 warnings
reports.html — 0 errors, 0 warnings
settings.html — 0 errors, 0 warnings
The documents were checked using the W3C HTML parser and completed successfully without syntax errors or warnings.
🛠️ Technologies Used
HTML5
CSS3
Semantic HTML
WCAG 2.1 accessibility principles
Native HTML form validation
Native HTML <dialog> element
W3C HTML Validator
📌 Implementation Notes
This project focuses on the structural and accessibility foundation of an enterprise dashboard.
The implementation prioritizes:
Semantic document structure
Clear DOM hierarchy
Accessible navigation
Accessible forms
Structured data tables
Accessible modal interaction
Keyboard accessibility
Valid HTML5 markup
Responsive presentation
The project is maintained as a public GitHub repository as required by the internship task.
🚀 Future Improvements
Possible future enhancements include:
JavaScript-based reusable component loading
Enhanced keyboard interaction
Dynamic dashboard data
Automated accessibility testing
Screen-reader testing
Accessibility testing with Lighthouse and axe
Integration with an enterprise dashboard backend
📚 Learning Outcomes
Through this project, the following concepts were practiced:
Semantic HTML5 architecture
Structured DOM hierarchy
WCAG-oriented development
Accessible navigation
Accessible forms
Accessible data tables
Modal dialog accessibility
Keyboard accessibility
Native HTML validation
Responsive CSS
Multi-page website structure
W3C HTML validation
📜 Internship Task
Task: Semantic HTML5 & Accessible Component Architecture
Objective: Build the structural foundation for an enterprise dashboard following strict HTML5 semantic standards and WCAG 2.1 accessibility guidelines.
Expected Proof: Public GitHub repository containing clean HTML5 pages and accessible component structures.
👨‍💻 Project Status
Status: Completed ✅
All required pages have been implemented and validated successfully using the W3C HTML Validator.
