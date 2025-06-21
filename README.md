# 🖥️📰 Nest.js Fórum API 📰🖥️

Forum API refactored using Nest.js. Reuses domain layer of <a href="https://github.com/AneWeber/Forum-API-DDD">ForumAPI</a>, with added features like authorization and cryptography with JWT, caching with Redis, messaging system, and database integration using Prisma ORM and PostgreSQL. Also includes file uploads using Cloudflare R2 via AWS SDK (S3 compatible).

## Technologies Used
- Node.js
- Nest.js
- TypeScript
- Vitest and SWC
- Prisma
- Multer
- Zod
- Docker
- Postgres
- Redis
- CloudFlare R2 - AWS SDK S3

## Requirements and Functionalities
- Create, edit and delete questions
- Create, edit and delete answers
- Comment on both questions and answers
- Select best answer for a question
- Send and receive notifications
- Upload and attach files to posts
- Search questions and answers
- Fetch recent questions
- Cache frequently accessed data using Redis
- Secure routes with JWT-based authentication
- Validate input data with Zod
- Full test coverage with unit and e2e tests

## Running DEMO
https://github.com/user-attachments/assets/1ab2b7ba-b7e7-482e-8098-f56a267e7a94
  
