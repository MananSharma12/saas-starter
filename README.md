# SaaS Starter

This is an ideal starter repo for all SaaS projects.

This Project uses the following tech stack:

1. Frontend: NextJS + ShadCN
2. Backend/DB: Convex
3. Auth/Payments: Clerk

Handy Commands for development:

```bash
npx convex dev
```

We would need the following env variables:

CONVEX_DEPLOYMENT (Auto generated)
NEXT_PUBLIC_CONVEX_URL (Auto generated)
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY (Auto generated)
CLERK_SECRET_KEY (Auto generated)

CLERK_FRONTEND_API_URL (Get the JWT URL from Clerk dashboard and add to the convex env variables as well)

Helpful Links:

Clerk with Convex: https://clerk.com/docs/integrations/databases/convex

Payments with Clerk: https://clerk.com/docs/nextjs/billing/b2c-saas
