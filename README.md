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

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## Authentication
For authentication we use clerk [DOCS](https://clerk.com/?utm_source=www.google.com&utm_medium=referral&utm_campaign=none)
Keys for clerk pkg need to be stored in env file.
For connecting authentication follow steps: [Next set up instraction](https://clerk.com/docs/quickstarts/nextjs)

## Forms:
Forms are tricky. They are one of the most common things you'll build in a web application, but also one of the most complex.

Well-designed HTML forms are:
Well-structured and semantically correct.
Easy to use and navigate (keyboard).
Accessible with ARIA attributes and proper labels.
Has support for client and server side validation.
Well-styled and consistent with the rest of the application.

Forms are build with:
react-hook-form - 
zod - used for form schema validation;

## DB
Prisma is used as DB:
npm install @prisma/client  
npx prisma init
npx prisma generate - to generate new db  
npx prisma db push 

npx prisma migrate reset - to reset db