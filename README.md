This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

## Initialize Supabase

Install supabase CLI if you haven't already.

```sh
supabase init
```

## Use flash toaster

```tsx
return setFlash({
  type: "error",
  message: "Invalid Referral Link",
})
```

You don't need to return anything, but its just to stop the flow. If you are using a series of error messages then do use them without the return statement.
