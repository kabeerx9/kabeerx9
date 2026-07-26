# Kabeer Joshi

Full-stack developer in Dehradun, India. I build and ship production web and
mobile products — React, Next.js, React Native/Expo, Node.js, Django, Postgres.

Currently at **Goreeva**, working on an education platform across mobile, web,
and backend. B.Tech CSE, Thapar Institute of Engineering and Technology.

## What I work on

**Education platform — Goreeva.** School operations across four user roles
(student, teacher, parent, admin): attendance, report cards, assignments, fees,
messaging, calendars, notifications. Two React Native apps, an Expo app, a React
dashboard, and Django services behind them. My work spans offline-first caching,
localization, file and payment workflows, and the API contracts between them.

**Real-time mobile platform.** Took an Expo project from setup to iOS and
Android store releases. Live drafts, lineups, tournaments, brackets, chat, and
scoring — all backed by synchronized real-time state, which is where most of the
hard problems were: reconnection, ordering, and conflict resolution across
clients. Also handled payments, identity verification, geolocation restrictions,
push notifications, deep links, crash reporting, and EAS build/release pipelines.

## Projects

**[hints.city](https://github.com/kabeerx9/Hints-City)** — City discovery
product I'm actively building: an Expo app, a React web app, and a Fastify API
in one monorepo, with request and response shapes defined once as Zod contracts
and shared by all three. Places data comes from Google under a per-SKU usage
meter, so the expensive call tiers are tracked and capped rather than discovered
on the invoice, and place photos are served through a signed proxy instead of
exposing keys to the client. Prisma migrations run against a live Railway
database.

**[Cancer-Compass](https://github.com/kabeerx9/Cancer-Compass)** — A treatment
companion for people going through chemotherapy: medications, appointments,
document storage, and day templates that generate a patient's task list for each
day of a cycle. An Expo app and a Vite dashboard sit on an Express + Prisma API,
with entity and response types shared from one package so all three stay in
sync.

**[Project-Sessions](https://github.com/kabeerx9/Project-Sessions)** — A native
macOS app that restores a development workspace in one action: browser profile
and tabs, project folder, editor, and terminal commands. It tracks the processes
it spawns and reports them as running, exited, or failed, so a session can be
torn down as cleanly as it was started. Swift.

**[Tattvix](https://github.com/kabeerx9/Tattvix)** — A polyglot monorepo: React
and TanStack Router on the web, an Expo development build on native, and a
Django REST API behind both, sharing typed contracts and validated environment
config. Turborepo and pnpm drive the TypeScript side, uv the Python side.

**[fullstack-monorepo-starter](https://github.com/kabeerx9/fullstack-monorepo-starter)**
— The GitHub template I start projects from. React 19, Expo, and Fastify with
Clerk authentication wired across all three, Prisma and Postgres, a shared
shadcn/ui package, and an `init:project` codemod that rewrites the workspace
scope, Expo identifiers, and import specifiers in a single pass.

## Tools

TypeScript · React · Next.js · React Native · Expo · Node.js · Django ·
PostgreSQL · TanStack Query · Docker

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/kabeerjoshi) ·
[kabeer786joshi@gmail.com](mailto:kabeer786joshi@gmail.com)
