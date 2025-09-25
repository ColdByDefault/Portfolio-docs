# Portfolio Documentation Site

[![Live Documentation](https://img.shields.io/badge/Live-docs.coldbydefault.com-blue?style=for-the-badge)](https://docs.coldbydefault.com)
[![Main Portfolio](https://img.shields.io/badge/Portfolio-coldbydefault.com-green?style=for-the-badge)](https://coldbydefault.com)

## Overview

This repository contains the technical documentation site for the **ColdByDefault Portfolio** project, served as a subdomain at `docs.coldbydefault.com`. It provides comprehensive API documentation, code references, and technical insights for the main portfolio website at `coldbydefault.com`.

## Purpose

The documentation site serves as:

- **API Reference**: Complete documentation of all portfolio API endpoints and services
- **Code Documentation**: TypeDoc-generated documentation for classes, interfaces, and functions
- **Technical Showcase**: Detailed technical specifications and implementation details
- **Developer Resource**: Reference material for the portfolio's architecture and components

## Main Portfolio Features Documented

The main portfolio (`coldbydefault.com`) is a modern, high-performance developer portfolio featuring:

- **Next.js 15.5.1** with App Router and Server Components
- **React 19.1.1** with TypeScript 5.x (strict mode)
- **Multi-language support** with next-intl 4.3.5
- **SEO optimized** (100/100 Google Lighthouse SEO score)
- **Secure API integrations** (GitHub, PageSpeed)
- **Accessibility-focused design** with shadcn/ui components
- **Production-grade security** and performance optimizations

## Documentation Structure

```
docs.coldbydefault.com/
├── classes/           # Service classes and utilities
├── functions/         # API routes and page components
├── interfaces/        # TypeScript interfaces
├── modules/          # Module documentation
├── types/            # Type definitions
└── variables/        # Configuration and constants
```

## Key Documentation Sections

- **Blog Administration**: Complete BlogAdminService, BlogQueryService, and validation services
- **Security Systems**: RateLimiter and security middleware documentation
- **API Routes**: All portfolio API endpoints including GitHub integration, PageSpeed monitoring, and chatbot functionality
- **Page Components**: Documentation for all portfolio pages and layouts
- **Utility Services**: Helper functions and utility classes

## Technology Stack

This documentation site is built with:

- **TypeDoc** for automated TypeScript documentation generation
- **HTML/CSS/JavaScript** for the documentation interface
- **GitHub Pages / Static Hosting** for deployment

## Links

- 🌐 **Live Documentation**: [docs.coldbydefault.com](https://docs.coldbydefault.com)
- 🎨 **Main Portfolio**: [coldbydefault.com](https://coldbydefault.com)
- 📦 **Portfolio Repository**: [GitHub](https://github.com/ColdByDefault/portfolio)

## Deployment

The documentation is automatically generated from the main portfolio codebase and deployed to the `docs.coldbydefault.com` subdomain, providing always up-to-date technical reference material.

---

_This documentation site complements the main portfolio by providing detailed technical insights and API references for developers and technical stakeholders._
