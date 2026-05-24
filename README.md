# EduTech: Multi-Tiered E-Learning Platform

A performance-driven, responsive multi-tiered E-Learning platform designed to deliver granular learning paths and structural productivity spaces. Built using **Vue 3** and **Vite**, this application leverages a modular frontend architecture to separate student dashboard tracking, content curation channels, subscription management gates, and interaction surfaces cleanly.

**Enterprise Frontend Implementation | Developed During AITech Internship**

> This system was engineered and deployed as part of my full-stack software development focus during my **3rd year of undergraduate studies**, demonstrating production-grade user interface scaling, secure state scoping, and reusable layout mechanics.

## Overview
Traditional learning systems frequently struggle with monolithic styling or loose interface logic that impacts client load speeds. This project introduces **EduTech**, a platform that answers these constraints by breaking deep user journeys down into 8+ specialized modular views.

The application leverages the **Vue 3 Composition API** along with custom scoped styles to minimize rendering footprint while preserving fluid transition animations. Student authentication spaces feature centralized configuration structures, matching explicit inputs with template-driven binding handlers. Dynamic system components process cross-view tasks including productivity workflows, active article archiving, free trial loops, and virtual semester scheduling pipelines.

## Features
- **Composition API Integration:** Drives lightweight reactivity loops, reactive validation tracking, and clear lifecycle separation using modern `script setup` conventions.
- **8+ Specialized Domain Views:** Implements structural routes for Home, Features, Platforms, Articles, Subscriptions, About, Login, and Signup journeys.
- **Granular Component Splitting:** Prevents DOM clogging by decoupling views into layout sub-layers (e.g., `HomeIntro`, `HomeStatistics`, `HomeProductivity`).
- **Secure Authentication Interfaces:** Features template-driven data modeling (`v-model`) with submission event-guards (`@submit.prevent`) for seamless data handling.
- **Production UI/UX Polish:** Deploys fluid linear gradients, hardware-accelerated transform states on interactive buttons, and auto-scoping CSS boundary caps.

## How It Works
- **Structural Routing Setup:** The core router targets isolated views, passing structural traffic straight into layout components.
- **Reactive Model Binding:** Forms bind user data directly inside `ref` object definitions, handling real-time view updates concurrently.
- **Event Interception Guards:** Authentication forms block page refreshes using intercepting submission handlers to prepare payloads cleanly.
- **Dynamic Feature Composition:** Views mix layout fragments (like statistics tracks or subscription grids) to match the logged-in student's authorization layer.
- **Scoped Layout Separation:** Separate component directories keep functional elements cleanly isolated from corporate views like contact paths or team layouts.

## Directory Architecture
```text
├── src/
│   ├── assets/              # High-definition visual assets and interface backgrounds
│   ├── components/          # Reusable component libraries split by domain context
│   │   ├── About/           # Modular company overview sub-layouts
│   │   ├── Articles/        # Structural columns for editorial content archives
│   │   ├── ContactUs/       # Form processors and team information modules
│   │   ├── Features/        # Feature tables for learning management tracks
│   │   ├── home/            # Core home view fragments (statistics, subscription, intro)
│   │   ├── Platforms/       # Deployment choices and tool matrix views
│   │   └── Subscription/    # Tier configurations and payment processing layers
│   └── views/               # Root view managers driving the application architecture
│       ├── AboutView.vue    # Coordinates about overview segments
│       ├── Articles.vue     # Assembles the resource documentation layout
│       ├── Contactus.vue    # Drives help desks and query capture states
│       ├── Features.vue     # Sets up core LMS component groups
│       ├── home.vue         # Builds the multi-tiered user dashboard entry
│       ├── login.vue        # Manages standard email credentials and entry states
│       ├── Platforms.vue    # Organizes platform compatibility metrics
│       ├── signup.vue       # Captures registration entries with policy checks
│       └── Subscription.vue # Manages subscription and billing paths
├── package.json             # Build commands, compilers, and project dependencies
└── vite.config.js           # Asset bundling configurations
