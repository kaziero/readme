```markdown
# Next.js Full-Stack Portfolio (TypeScript + Tailwind + Prisma)

Quick start:
1. Copy .env.example to .env and set values (especially DATABASE_URL and ADMIN_PASSWORD).
2. Install deps:
   - npm install
3. Generate Prisma client & run migration:
   - npx prisma migrate dev --name init
4. Run dev:
   - npm run dev
5. Open http://localhost:3000

Admin:
- Go to /admin to create projects and view contact messages.
- Use the ADMIN_PASSWORD environment variable to authenticate (sent in request body from the admin UI).

Notes:
- For production use PostgreSQL and set DATABASE_URL accordingly.
- Replace the simple admin-password flow with NextAuth/Clerk/other identity provider for secure auth in production.
--
```
