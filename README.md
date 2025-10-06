First:
```sh
docker compose up -d
```

Database:
```sh
bun run db:generate:migration
bun run db:migrate
bun run db:studio
```

To install dependencies:
```sh
bun install
```

To run:
```sh
bun run dev
```

open http://localhost:3000

Reference:

<https://www.youtube.com/watch?v=qhwmTxhRdyQ&t=450s>
