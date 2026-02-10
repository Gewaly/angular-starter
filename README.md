# Angular Enterprise Starter

A clean and reusable **Angular project structure (skeleton)** built using **Standalone APIs** and **feature-based architecture**.

> This repository provides **project architecture and folder structure only**.  
> It is intended to be used as a **starting point** for building enterprise Angular applications.

---

## Purpose

This starter helps developers quickly bootstrap:

- ERP systems
- Admin dashboards
- Large-scale business applications

by providing a **clean, scalable, and opinionated folder structure** without enforcing any business logic or UI framework.

---

## Project Structure

```txt
src/
├── app/
│   ├── core/               # Global services, interceptors, guards
│   ├── environments/       # Environment configuration
│   ├── pages/              # Application pages (features)
│   ├── shared/             # Reusable UI components & utilities
│   ├── app.config.ts       # ApplicationConfig (global providers)
│   └── app.routes.ts       # Application routing (standalone)
│
├── assets/                 # Static assets
├── main.ts
└── styles.scss
```

Architecture Principles

Standalone First
Uses Angular Standalone Components & Providers (no NgModules).

Feature-Based Pages
Each page represents a business feature and is isolated.

Clear Separation of Concerns

core: application-wide logic

shared: pure reusable UI & helpers

pages: business features

How to Use
1️⃣ Clone or use as a template
git clone https://github.com/USERNAME/angular-enterprise-starter.git

Or click "Use this template" on GitHub.

2️⃣ Install dependencies
npm install

# or

yarn install

3️⃣ Start building your app
ng serve

Start by:

Creating pages inside pages/

Adding routes to app.routes.ts

Implementing global services inside core/

🧩 What This Template Does NOT Include

❌ No UI framework enforced

❌ No authentication logic

❌ No business services

❌ No predefined components

This is intentional to keep the starter lightweight, flexible, and reusable.
