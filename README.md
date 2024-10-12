# Chirpg

> A text based RPG game with a reference to [chirp](https://github.com/t3dotgg/chirp) from [Theo](https://t3.gg).

## Concept

The main idea is to have a text chat based, multiplayer RPG game which map fits
in the screen inspired by [onestreamrpg](https://onestreamrpg.com)

## Tech Stack

- [Bun](https://bun.sh)
  - Trying to move away from npm and bun is a faster alternative.
  - Also considering [Deno](https://deno.com) but bun seems to have less friction for now.
- [Hono](https://hono.dev)
  - A great option for deploying with cloudflare workers.
- [Drizzle](https://drizzle.dev)
  - A great TypeScript focused ORM.
- [Turso](https://turso.tech)
  - An option for working with SQLite with great replication features.
- [Cloudflare](https://cloudflare.com)
  - For deploy and infrastructure.

## License

[FSL-1.1-MIT](./LICENSE)
