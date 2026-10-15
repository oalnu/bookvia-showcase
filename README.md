# Bookvia

**A branded booking page and workspace for independent service professionals.**

Bookvia brings a provider's services, availability and booking journey together in one shareable page. Behind it, the provider manages appointments, clients and payment-related work from a connected workspace.

The aim is to replace the handoff between a social profile, messages, a calendar and payment instructions with a clearer path from discovering a provider to arranging a session.

**Product showcase · Private-source application · Prelaunch development**

[Screenshot gallery](docs/gallery.md) · [Feature catalogue](docs/features.md) · [Demo profiles](docs/demo-profiles.md) · [Roadmap](docs/roadmap.md) · [Technical overview](docs/technical-overview.md)

![Amelia coaching demo: branded public profile](assets/screenshots/coaching-profile-desktop.jpg)

*Actual application capture with demo content. Profile experience, reviews, ratings, client counts and testimonials shown throughout this repository are illustrative, not evidence of customers or commercial traction.*

## The product in practice

| For the provider | For the client |
| --- | --- |
| Build a public page with a profile, services and supporting content | Understand the provider's offer before choosing a service |
| Define service prices, durations and delivery methods | Compare a free introduction with paid sessions |
| Configure availability and manage the appointment calendar | Choose an available date and time |
| Keep bookings and client information in one workspace | Enter booking details and continue through the booking journey |
| Connect payment and business settings | Receive booking and payment information where supported by the configured flow |

The current focus is solo providers and small practices, with coaching and personal training used as demonstration scenarios. These examples illustrate the product; they do not establish a validated customer segment.

## Two different businesses, one platform

**Amelia — career and leadership coaching.** A light, restrained page with a free discovery call, categorised sessions, benefits, FAQs and a booking widget.

**Northform Performance — strength coaching.** A darker, image-led page with in-person assessments, online check-ins and individual coaching offers.

![Northform fitness demo: a different brand treatment](assets/screenshots/fitness-profile-desktop.jpg)

[Explore both desktop and mobile profiles](docs/demo-profiles.md). Sample prices and service descriptions belong to the fictional providers, not Bookvia's subscription pricing.

## A booking journey inside the provider's page

The demonstrated client path is **service → date and time → details**. The application also contains payment, confirmation, cancellation and receipt flows; these require separate end-to-end validation in the target environment.

![Actual date and time selection in the coaching demo](assets/screenshots/booking-times-desktop.jpg)

Fresh captures in this showcase stop before submitting a booking or initiating payment. They demonstrate rendered interfaces and navigation, not a completed payment or production-readiness test.

## What is built, and what comes next

The private application includes provider onboarding, page editing, services, availability, bookings, clients, Stripe Connect/payment workflows, transactional email and account settings. The [feature catalogue](docs/features.md) distinguishes directly demonstrated screens from implementation that still needs deployment validation.

Calendar/video integrations, advanced analytics, packages, SEO tooling, session journals and AI-assisted workflows are broader development areas. They are **not presented as generally available launch features**. The [roadmap](docs/roadmap.md) prioritises a reliable booking and payment core before expanding that scope.

## Project and ownership

Bookvia is a product project by [Osamah Al-Nuaimi](https://github.com/oalnu), combining product scoping, business-workflow design and full-stack implementation. The private stack uses Next.js, React, TypeScript, Supabase/Postgres, Stripe Connect and supporting email/background-job services. AI tools assisted development and preparation of this showcase.

This repository contains documentation and selected product images only. Application source, database definitions, credentials, deployment configuration and customer records are not included. It is not a runnable distribution of Bookvia. [Rights and screenshot provenance](docs/rights-and-provenance.md).
