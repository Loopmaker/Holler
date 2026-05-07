# Holler

A simple, modern demo ecommerce application with a TypeScript backend and a React + Vite frontend. Holler demonstrates a small production-like stack for building a storefront: product catalog, cart + checkout flow, admin product management, order handling, image uploads, and streaming integrations.

## Features

- Browse product catalog with images
- Add to cart and persistent cart state in the client
- Checkout flow with webhook-ready server endpoints
- Admin product management (create / update / delete)
- Order listing and order detail pages
- Image upload and URL handling (ImageKit integration)
- Lightweight streaming / video support endpoints
- Auth and user sync hooks (integrations for Clerk)
- Error monitoring and tracing hooks (Sentry integration)
- Dockerfile for containerized runs

## Tech Stack

- Backend: Node.js + TypeScript
- API: Organized controllers & routes 
- ORM / DB: Drizzle with PostgreSQL 
- Frontend: React + Vite 
- Image handling: ImageKit (upload + URL helpers)
- Auth: Clerk (hooks and webhooks integrated)
- Monitoring: Sentry integration
- Other: Webhook handlers, streaming utilities, and convenience scripts



## Future Improvements

- Add a clear environment / secrets example and `.env.example`
- Automated tests (unit + integration) and CI pipeline
- Full deployment guide (Heroku/Vercel/Docker Compose / Kubernetes)
- Payment provider examples and sandbox configuration
- Improve PWA support, accessibility, and i18n
- Performance tuning and caching for product lists

---


