## Next.js Dashboard Application

This repository contains a dashboard application developed throughout the official Vercel **Next.js Learn** course. The project served as a practical foundation for consolidating advanced skills in frontend development and software engineering, culminating in the respective certification in this technology.

## Key Features

- **Resource Optimization:** Utilization of native components like `next/image` and `next/font` to ensure efficient loading of images and fonts, preventing Layout Shift.
- **Navigation and Routing:** Implementation of the App Router with static, dynamic, and nested routes, alongside shared layouts for visual state optimization.
- **Data Management and Fetching:** Execution of SQL queries directly in Server Components, response time control through Streaming strategies with Suspense, and Loading Skeletons.
- **Efficient Search and Pagination:** Integration of search filters and pagination synchronized directly with URL parameters (`URLSearchParams`), optimizing state sharing and user experience.
- **Secure Data Mutation:** Use of Server Actions for inserting, updating, and deleting data, with server-side schema validation using the Zod library.
- **Resilient Error Handling:** Centralized exception management with `error.tsx` files and handling of not-found resource states with `not-found.tsx`.
- **Security and Authentication:** Implementation of access control and route protection through NextAuth.js and Middleware.
- **Accessibility (A11y):** Application of accessibility best practices in forms, including ARIA validations and real-time user feedback.

## Technologies Used

- **Framework:** Next.js (App Router)
- **Frontend Library:** React
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **Authentication:** NextAuth.js
- **Validation:** Zod
- **Database:** PostgreSQL

## Prerequisites

Before starting the project, ensure you have the following installed:
- Node.js (stable version compatible with Next.js)
- pnpm (package manager used in the application)

## Available Scripts

- `pnpm dev`: Starts the local development server.
- `pnpm build`: Creates the optimized production build of the application.
- `pnpm start`: Starts the application in production mode after the build.
- `pnpm lint`: Runs static code analysis to detect formatting issues or TypeScript/ESLint errors.

## Test Credentials

To test the application, you can use the following credentials:
- **Email:** `user@nextmail.com`
- **Password:** `123456`
