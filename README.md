# Chirpg

> A text based RPG game with a reference to [chirp][1] from [Theo][2].

## Concept

The main idea is to have a text chat based, multiplayer RPG game which a UI that
fits in the screen inspired by [onestreamrpg][3].

## Tech Stack

- [Bun][4]
  - Trying to move away from npm and bun is a faster alternative.
  - Also considering [Deno][5] but bun seems to have less friction for now.
- [Hono][6]
  - A great option for deploying with cloudflare workers.
- [Drizzle][7]
  - A great TypeScript focused ORM.
- [Turso][8]
  - An option for working with SQLite with great replication features.
- [Cloudflare][9]
  - For deploy and infrastructure.

## License

[FSL-1.1-MIT][10]

[1]: https://github.com/t3dotgg/chirp
[2]: https://t3.gg
[3]: https://onestreamrpg.com
[4]: https://bun.sh
[5]: https://deno.com
[6]: https://hono.dev
[7]: https://orm.drizzle.team/
[8]: https://turso.tech
[9]: https://cloudflare.com
[10]: ./LICENSE
