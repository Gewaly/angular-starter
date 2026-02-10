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
