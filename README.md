# Description

## Run in dev

1. Clone the repository.
2. Create a copy of the ```.env.template``` and rename it to ```.env``` and change the environment variables.
3. Install dependencies ```npm install```
4. Upload the database ```docker compose up -d```
5. Run Primsa migrations ```npx prisma migrate dev```
6. Run seed ```npm run seed```
7. Run the project ```npm run dev```
8. Clean the browser's localStorage.