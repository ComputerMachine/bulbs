# Bulbs

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)]()
[![Python Version](https://img.shields.io/badge/python-3.4%2B-blue.svg)]()
[![License](https://img.shields.io/badge/license-MIT-green.svg)]()
[![Framework](https://img.shields.io/badge/framework-Pyramid-0a9edc.svg)]()

**Bulbs** is an open-source **message board / forum platform** built with **Python** and the **Pyramid** web framework.  
It is designed to be lightweight, easy to deploy, and highly extendable—providing a clean foundation for custom forums, community boards, or embedded discussion systems.

---

## 📘 What Is Bulbs?

Bulbs is a minimal and developer-friendly discussion board system.  
It focuses on **clarity**, **customizability**, and **performance**, offering:

- Threaded topics and post handling  
- Clean routing via Pyramid  
- Integration with PostgreSQL  
- A structure that makes it easy to extend features such as:
  - user permissions  
  - moderation tools  
  - custom themes  
  - rich text editors  
  - API endpoints  

The goal of Bulbs is to provide a **simple but powerful base** for any forum-style application.

---

## 🧰 Requirements

- **Python 3.4+**  
- **Pyramid**  
- **PostgreSQL**

---

## 🛠 Installation

1. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
Install the Bulbs package

```
python setup.py develop
```
Start the development server

```
pserve development.ini --reload
```
Configure the database

Open your browser and navigate to `/install`

Complete the setup screen to initialize and configure your database.

## 🗺️ Roadmap
Planned features and future improvements:
- Remove special characters from slug generation
- Fix the issue where forward slashes in usernames break the profile page
- Webhook support
- Plugin system for adding new modules
- REST API for external applications

## 🔧 Core Enhancements
- Improved authentication system (password resets, email verification)
- Extended slug generation rules and localization support

## 🎨 User Experience
- Optional Markdown or rich-text editor for posts
- Customizable themes / CSS templates
- Better mobile responsiveness

## 🛡 Moderation & Admin Tools
- User roles and permissions
- Post reporting & moderation queue
- Thread locking / pinning

---

## 🤝 Contributing
Contributions are welcome!
To contribute:

- Fork the repository
- Create a feature branch
- Make your changes
- Submit a pull request with a clear explanation

Bug reports, ideas, and feature requests are also appreciated.

## 📝 License

See the LICENSE file for full details.
