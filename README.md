# ZanFood

ZanFood is a Zanzibar focused multi restaurant food delivery platform with a Flutter customer app, Flutter rider app, responsive restaurant dashboard, responsive administration dashboard, Fastify TypeScript API and PostgreSQL/PostGIS.

The repository contains a working security and transaction foundation for OTP authentication, restaurant discovery, tenant constrained restaurant operations, server calculated Cash on Delivery order creation, order state enforcement, rider availability and assignment, rider location submission, delivery OTP and cash collection confirmation, finance verification, admin approval and audit structures.

## Important production status

This repository is an implementation baseline, not a claim that all 27 requested production deliverables have passed release acceptance. The environment used to generate it does not contain Flutter, Dart, PostgreSQL or Docker, so a signed Android App Bundle and database backed end to end run could not be executed here. `docs/PRODUCTION_READINESS.md` explicitly lists the remaining integrations and verification gates. Do not release until every item is complete and the acceptance suite passes.

## Start here

Read `docs/ARCHITECTURE.md`, `docs/API_CONTRACTS.md`, `docs/PROJECT_STRUCTURE.md`, `docs/SETUP.md` and `docs/PRODUCTION_READINESS.md`.
