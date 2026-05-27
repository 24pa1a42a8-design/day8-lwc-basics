# Day 8 – Lightning Web Components Basics

## Topics Covered
- Lightning Web Components (LWC)
- Component-Based Architecture
- Frontend vs Backend Thinking
- Reusable UI Design
- Enterprise UI Development
- Salesforce Security Basics

---

# What is LWC?

Lightning Web Components (LWC) is Salesforce’s modern UI framework used to build fast, reusable, and efficient user interfaces.

LWC is based on:
- HTML
- JavaScript
- CSS
- Web Standards

Each component contains:
- HTML template
- JavaScript controller
- Metadata configuration

LWC helps developers create modular and maintainable applications.

---

# Why Salesforce Uses LWC

Salesforce moved toward LWC because it:
- Improves performance
- Uses modern web standards
- Supports reusable UI architecture
- Simplifies development
- Enhances maintainability
- Provides better user experience

Compared to older Aura components, LWC is:
- Faster
- Lightweight
- Easier to develop
- More aligned with modern JavaScript development

---

# UI Screens for College Management System

## 1. Student Registration Screen
Allows students to register and submit details.

## 2. Course Dashboard
Displays available courses and enrollment details.

## 3. Attendance Management Screen
Tracks attendance records for students.

## 4. Faculty Panel
Allows faculty to manage classes and student data.

## 5. Notifications Widget
Displays announcements and important updates.

---

# Component Breakdown

## Selected Screen: Student Dashboard

### Reusable Components

### 1. Header Component
Displays application title and navigation.

### 2. Student Information Component
Displays student profile details.

### 3. Attendance Component
Shows attendance percentage and status.

### 4. Notifications Component
Displays latest alerts and announcements.

### 5. Course Summary Component
Displays enrolled courses and progress.

---

# Why Reusable Components Are Useful

Reusable components:
- Reduce duplicate code
- Improve maintainability
- Increase development speed
- Ensure UI consistency
- Simplify debugging
- Support scalability in enterprise applications

---

# Frontend vs Backend Logic

## Frontend (UI Layer)
Handles:
- Button clicks
- Form input
- UI rendering
- Notification display
- Client-side validation

Examples:
- Showing success messages
- Opening forms
- User interactions

## Backend (Apex/Server Layer)
Handles:
- Database operations
- Complex business logic
- Fee calculation
- Security validation
- Record processing

Examples:
- Saving student records
- Calculating fees
- Updating attendance records

---

# Reflection

Modern enterprise systems use component-based UI architecture because it:
- Supports modular development
- Improves scalability
- Simplifies maintenance
- Encourages code reuse
- Enhances team collaboration
- Improves application performance

Separating frontend and backend logic creates cleaner and more manageable systems.
