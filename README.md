# Next.js Full Web Application Course - Finished Course Code

## Introduction

This repository contains the final result of the Next.js full web application course using the template starter provided on the website. The purpose of this project was for me to familiarize myself with Nextjs along with other technologies used to create a full stack web applications for future reference.

Click [here](https://nextjs-dashboard-lime-tau-41.vercel.app/) to view the live demo.

## Getting Started

If you would like to run this project locally, you can do so by following these steps:

1.  Create a Next.js app, open your terminal, cd
    into the folder you'd like to keep your project, and run the following command:

    `npx create-next-app@latest nextjs-dashboard --example "https://github.com/arod1104/nextjs-dashboard" --use-pnpm`

    This command uses create-next-app, a Command Line Interface (CLI) tool that sets up a Next.js application for you. In the command above, you're also using the --example flag with the starter example for this course.

2.  Install Node.js if you haven't already using your preferred method
3.  Run `pnpm i` in the project directory command line to install the necessary dependencies
4.  Run `pnpm dev` to start the development server

_Note: You will need to include your own .env file with the following variables:_

```# Copy from .env.local on the Vercel dashboard
# https://nextjs.org/learn/dashboard-app/setting-up-your-database#create-a-postgres-database
POSTGRES_URL=
POSTGRES_PRISMA_URL=
POSTGRES_URL_NON_POOLING=
POSTGRES_USER=
POSTGRES_HOST=
POSTGRES_PASSWORD=
POSTGRES_DATABASE=

# `openssl rand -base64 32`
AUTH_SECRET=
AUTH_URL=http://localhost:3000/api/auth`
```

## Linting

This project uses ESLint to ensure code quality and consistency. To run the linter, follow these steps:

1. Run `pnpm i` if you haven't already installed the necessary dependencies.
2. Run `pnpm lint` in the project directory to check for linting errors.

The linter is configured to follow best practices and recommended settings for Next.js projects. If you encounter any linting errors, please refer to the ESLint documentation for guidance on resolving them.

## Testing

There course did not go into testing and therefore testing is not included.

## Technologies Used

- [Next.js](https://nextjs.org/)
- [React](https://react.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [PostgresSQL](https://nextjs.org/learn/dashboard-app/setting-up-your-database) [(provided by Vercel)](https://www.postgresql.org/)
- [Zod](https://zod.dev/) (for validation)
- [ESLint](https://eslint.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [JavaScript](https://www.javascript.com/)

Although [Prisma](https://www.prisma.io/) and [Drizzle](https://orm.drizzle.team/) where mentioned during the course as a solution to creating safe data types based on the database schema, it was not used for this project.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.
