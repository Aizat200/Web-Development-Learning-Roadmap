# 🚀 Web Development Learning Roadmap

A hands-on learning project designed to improve my **Web Development and Full-Stack Development skills** by building real-world website features step by step.

The goal is not just to learn how to create a website, but to understand how modern web applications work — from basic UI to backend, databases, authentication, security, APIs, and AI.

---

## 🎯 Learning Goal

By completing this project, I want to improve my skills in:

* HTML
* CSS
* JavaScript
* Responsive Web Design
* UI/UX
* Frontend Development
* Backend Development
* Database Management
* REST API
* Authentication & Authorization
* Web Security
* Git & GitHub
* AI Integration
* Deployment

---

# 📚 Lessons

## 🟢 Level 1 — Website Fundamentals

### Lesson 01 — Website Structure

Learn how to create the basic structure of a website.

**Features:**

* Home
* About
* Services
* Contact
* Navigation Bar
* Footer

**Learn:**

* HTML5
* Semantic HTML
* Page structure
* Links
* Images

---

### Lesson 02 — Contact Us

Build a functional contact form.

**Features:**

* Name
* Email
* Subject
* Message
* Submit button
* Form validation

**Learn:**

* HTML Forms
* Input validation
* JavaScript
* Error messages
* Form UX

---

### Lesson 03 — FAQ

Create an interactive Frequently Asked Questions section.

**Features:**

* Expand/collapse questions
* Multiple questions
* Smooth interaction

**Learn:**

* JavaScript events
* DOM manipulation
* CSS animations

---

### Lesson 04 — Responsive Design

Make the website work on different screen sizes.

**Learn:**

* CSS Flexbox
* CSS Grid
* Media queries
* Mobile-first design
* Responsive navigation

**Test on:**

* 📱 Mobile
* 📱 Tablet
* 💻 Laptop
* 🖥️ Desktop

---

# 🟡 Level 2 — Interactive Web

## Lesson 05 — Search

Create a search feature.

**Features:**

* Search input
* Search results
* No-result message
* Real-time filtering

**Learn:**

* JavaScript
* Arrays
* Objects
* Filtering
* DOM updates

---

## Lesson 06 — Filter & Sort

Allow users to filter and sort information.

**Example:**

```text
Category
[ All ▼ ]

Sort By
[ Newest ▼ ]
```

**Learn:**

* Array filtering
* Sorting
* Event handling
* Dynamic UI

---

## Lesson 07 — Modal & Popup

Create reusable modal windows.

**Example:**

```text
[ View Details ]

        ↓

┌──────────────────────┐
│ Project Details      │
│                      │
│ Description...       │
│                      │
│       [ Close ]      │
└──────────────────────┘
```

**Learn:**

* DOM manipulation
* Events
* CSS positioning
* Component thinking

---

## Lesson 08 — Notifications

Create different types of notifications.

**Examples:**

```text
✓ Message sent successfully

⚠ Please complete all fields

✕ Something went wrong
```

**Learn:**

* JavaScript
* UI feedback
* Timers
* Reusable components

---

# 🟠 Level 3 — Backend

## Lesson 09 — Database

Connect the website to a database.

**Example database:**

```text
users
contacts
projects
messages
```

**Learn:**

* SQL
* Database design
* Tables
* Primary keys
* Foreign keys
* Relationships
* CRUD

---

## Lesson 10 — Contact Management

Upgrade the Contact Us feature.

Instead of simply displaying:

```text
Message Sent!
```

Store the message inside the database.

### User

```text
Name
Email
Subject
Message
        ↓
Submit
        ↓
Database
```

### Admin

```text
Admin Dashboard

Messages
--------------------------------
Name       Subject       Status
Amir       Question      Unread
Ali        Support       Read
```

**Learn:**

* Backend processing
* Database queries
* CRUD
* Admin systems

---

# 🔵 Level 4 — Authentication

## Lesson 11 — Registration

Create a user registration system.

**Features:**

* Name
* Email
* Password
* Confirm password

**Learn:**

* Backend validation
* Password hashing
* Database storage

---

## Lesson 12 — Login

Create a secure login system.

**Features:**

* Email
* Password
* Remember session
* Logout

**Learn:**

* Sessions
* Authentication
* Password verification
* Cookies

---

## Lesson 13 — User Profile

Allow users to manage their profile.

**Features:**

* Profile picture
* Name
* Email
* Password
* Account settings

---

# 🔴 Level 5 — Authorization

## Lesson 14 — Role-Based Access Control

Create different user roles.

```text
Admin
   ↓
Full Access

Staff
   ↓
Limited Management

User
   ↓
Normal Features
```

**Learn:**

* Authorization
* Permissions
* Middleware
* Access control

---

# 🟣 Level 6 — Admin Dashboard

## Lesson 15 — Dashboard

Create an administration dashboard.

**Dashboard should show:**

```text
Users          1,250
Projects         128
Messages          52
Active Users     342
```

Add:

* Statistics
* Tables
* Charts
* Recent activities
* User management
* Message management

**Learn:**

* Dashboard UI
* Data visualization
* Database queries
* Admin architecture

---

# 🟤 Level 7 — API

## Lesson 16 — REST API

Create an API for the application.

Example:

```http
GET    /api/users
GET    /api/users/1
POST   /api/users
PUT    /api/users/1
DELETE /api/users/1
```

**Learn:**

* REST API
* HTTP methods
* JSON
* HTTP status codes
* API architecture

---

## Lesson 17 — API Integration

Connect your application to an external API.

Examples:

* Weather API
* Maps API
* Payment API
* AI API

**Learn:**

* Fetch
* API requests
* JSON
* Authentication
* Error handling

---

# 🔐 Level 8 — Web Security

## Lesson 18 — SQL Injection

Learn how SQL Injection works and how to prevent it.

**Learn:**

* Prepared statements
* Parameterized queries
* Input validation

---

## Lesson 19 — XSS Protection

Learn how Cross-Site Scripting works.

**Learn:**

* Output escaping
* Input sanitization
* Content Security Policy

---

## Lesson 20 — CSRF Protection

Protect forms and sensitive requests from CSRF attacks.

**Learn:**

* CSRF tokens
* Secure sessions
* SameSite cookies

---

## Lesson 21 — Login Security

Improve authentication security.

**Features:**

* Login attempt limitation
* Account lockout
* Password reset
* Email verification
* Two-factor authentication

---

# ⚡ Level 9 — Advanced Features

## Lesson 22 — File Upload

Allow users to upload files.

**Learn:**

* File validation
* File size limits
* File types
* Secure file storage

---

## Lesson 23 — Email System

Send emails automatically.

**Examples:**

```text
Registration
     ↓
Verification Email

Contact Form
     ↓
Admin Notification

Password Reset
     ↓
Reset Email
```

---

## Lesson 24 — Notifications

Create a notification system.

**Examples:**

```text
🔔 New message
🔔 Project updated
🔔 Task assigned
🔔 Password changed
```

---

## Lesson 25 — Activity Log

Record important user actions.

```text
User logged in
User updated profile
Admin deleted account
User created project
```

**Learn:**

* Audit trails
* Database logging
* Security monitoring

---

# 🤖 Level 10 — AI Integration

## Lesson 26 — AI Chatbot

Add an AI assistant to the website.

**Example:**

```text
User:
How do I create a project?

AI:
Go to Projects → Create Project...
```

**Learn:**

* AI API
* Prompt engineering
* Chat interface
* Conversation history

---

## Lesson 27 — AI Assistant

Make the AI perform useful tasks.

Examples:

* Generate project descriptions
* Summarize messages
* Generate reports
* Create tasks
* Analyze data

---

# 🚀 Level 11 — Deployment

## Lesson 28 — Git & GitHub

Learn proper version control.

```bash
git init
git add .
git commit
git push
```

Learn:

* Branches
* Commits
* Pull requests
* Issues
* README documentation

---

## Lesson 29 — Deployment

Deploy the application to the internet.

Learn:

* Environment variables
* Production database
* Domain
* HTTPS
* Server configuration
* Deployment

---

# 🏆 Final Project

After completing all lessons, combine everything into one complete application.

## Example — DevHub

A full-stack platform containing:

### Public Website

* Home
* About
* Services
* Portfolio
* Blog
* FAQ
* Contact

### User System

* Registration
* Login
* Profile
* Password reset
* Email verification

### Project Management

* Create project
* Update project
* Delete project
* Tasks
* Comments
* File uploads
* Progress tracking

### Admin

* Dashboard
* User management
* Project management
* Contact messages
* Activity logs
* Reports

### Advanced

* Search
* Filter
* Notifications
* REST API
* Email
* Charts
* AI assistant

### Security

* Password hashing
* SQL injection protection
* XSS protection
* CSRF protection
* Role-based access
* Audit logs
* Login protection

---

# 📈 Learning Progress

Track my progress:

* [ ] Lesson 01 — Website Structure
* [ ] Lesson 02 — Contact Us
* [ ] Lesson 03 — FAQ
* [ ] Lesson 04 — Responsive Design
* [ ] Lesson 05 — Search
* [ ] Lesson 06 — Filter & Sort
* [ ] Lesson 07 — Modal & Popup
* [ ] Lesson 08 — Notifications
* [ ] Lesson 09 — Database
* [ ] Lesson 10 — Contact Management
* [ ] Lesson 11 — Registration
* [ ] Lesson 12 — Login
* [ ] Lesson 13 — User Profile
* [ ] Lesson 14 — Role-Based Access
* [ ] Lesson 15 — Admin Dashboard
* [ ] Lesson 16 — REST API
* [ ] Lesson 17 — API Integration
* [ ] Lesson 18 — SQL Injection Protection
* [ ] Lesson 19 — XSS Protection
* [ ] Lesson 20 — CSRF Protection
* [ ] Lesson 21 — Login Security
* [ ] Lesson 22 — File Upload
* [ ] Lesson 23 — Email System
* [ ] Lesson 24 — Notifications
* [ ] Lesson 25 — Activity Log
* [ ] Lesson 26 — AI Chatbot
* [ ] Lesson 27 — AI Assistant
* [ ] Lesson 28 — Git & GitHub
* [ ] Lesson 29 — Deployment

---

# 🎓 Final Goal

> **Don't just learn web development. Build something that forces me to understand it.**

The objective is to progress from:

**Static Website**

↓

**Interactive Website**

↓

**Database Application**

↓

**Full-Stack Application**

↓

**Secure Web Application**

↓

**AI-Powered Application**

↓

**Production-Ready Application**

---

## 🛠️ My Rule

For every lesson:

1. Understand the concept.
2. Build the feature myself.
3. Test it.
4. Break it intentionally.
5. Fix the problem.
6. Document what I learned.
7. Commit the changes to Git.
8. Move to the next lesson.

This project is my personal **Web Development Skill Upgrade Roadmap**.
