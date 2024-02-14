
# ChatSync
This is a realtime chat application built using Pusher.js for socket features, NextAuth for GitHub authentication, Prisma for database management, and Supabase for PostgreSQL storage. The application is built on Next.js 13 (AppRouter).

## Setup
To set up the application locally, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Create a `.env` file based on the `.env.sample` file provided.
4. Fill in the necessary values in the `.env` file.
5. Run `npx prisma db push`.
5. Run `npm install`.
6. Run `npm run dev`.
7. Visit `http://localhost:3000` in your web browser to access the application.

## Environment Variables
* `DATABASE_URL`: The URL for your PostgreSQL database.
* `GITHUB_CLIENT_ID` and `GITHUB_SECRET_ID`: Your GitHub OAuth App client ID and secret.
* `PUSHER_APP_ID`, `PUSHER_SECRET`, and `NEXT_PUBLIC_PUSHER_KEY`: Pusher API credentials.
* `NEXTAUTH_SECRET`: A random string used for NextAuth.js token encryption.

## Technologies Used

* Next.js 13 (Experimental AppRouter)
* Pusher.js
* NextAuth.js
* Prisma
* Supabase

