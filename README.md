## Getting Started

First, run `docker compose up` in a separate terminal to get the postgres db and Jaeger service started.

If this is your first time, run `npm run dev:full`. This will run `npm install && npx prisma migrate dev && npm run dev`.

Subsequently, you can just run `npm run dev`. This will run the basic `main` function.

Visit [http://localhost:16686](http://localhost:16686) to view the trace in Jaeger.
