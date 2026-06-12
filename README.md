# TechNova Solutions — Corporate Website

A clean, modern multi-page corporate website designed for an IT services and consulting firm. This project demonstrates structured directory routing, semantic HTML5 layouts, and custom page modules to cleanly showcase corporate capabilities, technical services, and global client connection pathways.

## 🚀 Key Features

* **Semantic HTML5 Architecture:** Structured across individual dedicated files using meaningful elements like `<header>`, `<nav>`, `<main>`, `<section>`, `<address>`, and `<footer>`.
* **Cross-Directory Navigation:** Clean absolute-relative path links connecting the root landing page directly to nested sub-pages.
* **Multi-Column Service Grid:** A stylized horizontal service display matrix presenting core technical offerings—Cloud Solutions, Custom Software Development, and Cybersecurity.
* **Integrated Contacts Panel:** A dedicated `<address>` communication module utilizing functional electronic mailing (`mailto:`) and telephone (`tel:`) protocols.

---

## 📂 Project Architecture

The workspace is organized with a clean separation of concerns, keeping assets, styling modules, and deep HTML layouts in isolated system sub-folders:

```text
PROJECT 1/
│
├── ASSETS/
│   └── images/
│       ├── cloud-solution.png
│       ├── custom-software.png
│       ├── cybersecurity.png
│       └── hero-img.png
│
├── CSS/
│   ├── about.css
│   ├── contact.css
│   ├── services.css
│   └── style.css
│
├── HTML/
│   ├── about.html
│   ├── contact.html
│   └── services.html
│
└── index.html
