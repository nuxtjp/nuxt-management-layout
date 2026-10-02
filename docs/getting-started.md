# Using @nuxtjp/management-layout

Build an administration-screen shell with navigation, breadcrumbs and status summaries.

## Before you start

The layer consumes the declared UI module. APIs, authorization and business decisions remain with the application.

## First steps

Make the exact declared dependency artifacts available before installation. Local archives are excluded from Git; registry publication remains pending.

Run from the repository root:

```sh
pnpm install --frozen-lockfile
pnpm compliance:verify
pnpm typecheck
pnpm test
pnpm build
```

## How to assess the result

- Compose common management-screen structure.
- Supply application-owned routes and business labels.

A passing source-level check establishes only what that check observes. Keep missing configuration, unavailable services and unverified deployment paths visible.

## Continue reading

[Repository overview](../README.md)
