# Holler

A simple, modern demo ecommerce application with a TypeScript backend and a React + Vite frontend. Holler demonstrates a small production-like stack for building a storefront: product catalog, cart + checkout flow, admin product management, order handling, image uploads, and streaming integrations.

## Features

- Browse product catalog with images, variants, and prices.
- Add to cart with persistent client-side cart state and cart store.
- Checkout flow with server endpoints and webhook-ready handlers for order processing.
- Sandbox payment integration via Polar (client + server) for testing payments.
- Admin product management: create, update, delete products and images.
- Order listing, order detail pages, order preview, and order summary.
- Order chat and order video pages for rich post-purchase interactions.
- Image uploads + URL handling via ImageKit (upload helper + URL builder).
- Lightweight streaming / video support endpoints and stream controllers.
- Auth and user sync hooks (Clerk integration + Clerk webhook handler).
- Error monitoring and tracing with Sentry integration and Sentry sync hooks.
- Webhook handlers for external services (e.g., Clerk, Polar).
- Background tasks / cron utilities for scheduled jobs.
- DB seed script to populate demo data.
- Dockerfile for containerized runs and straightforward deployment.

## Links

- Demo / Deployment: [https://holler-uqto.onrender.com/]

## Tech Stack

- Backend: Node.js + TypeScript
- API: Organized controllers & routes 
- ORM / DB: Drizzle with PostgreSQL 
- Frontend: React + Vite 
- Image handling: ImageKit (upload + URL helpers)
- Auth: Clerk (hooks and webhooks integrated)
- Monitoring: Sentry integration
- Payments: Polar sandbox integration (checkout + webhook handling)
- Streaming / Video: custom streaming endpoints and Polar integration utilities
- Containerization: Dockerfile included for building an image



## Future Improvements

- Add a clear environment / secrets example and `.env.example`
- Automated tests (unit + integration) and CI pipeline
- Full deployment guide (Heroku/Vercel/Docker Compose / Kubernetes)
- Improve PWA support, accessibility, and i18n
- Performance tuning and caching for product lists

---


