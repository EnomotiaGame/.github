# ENOMOTIA

We build [ENOMOTIA](https://enomotia.net), a strategy game set in ancient Greece that you play in the browser and on your phone. You found a city, grow it, trade with your neighbours and defend it in battle.

Building a game for the web and for phones keeps putting us in front of problems that are not really about games: requests that arrive twice over a bad connection, push notifications on every platform, colour palettes that colour-blind players can read, one guide in five languages that never falls out of step. When one of our solutions turns out to be general, we clean it up, test it on its own and publish it here, so nobody else has to solve it again.

## Projects

| Project | What it does |
|---|---|
| [idempotency](https://github.com/EnomotiaGame/idempotency) | `Idempotency-Key` middleware for Go's `net/http`: a retried request gets the first answer back instead of running twice. Zero-dependency core, PostgreSQL store. |
| [lockstep-md](https://github.com/EnomotiaGame/lockstep-md) | Multilingual Markdown docs that stay in lockstep: the build fails when a translation drops a paragraph, a row or a section. CLI, Vite plugin, no runtime dependencies. On [npm](https://www.npmjs.com/package/lockstep-md). |
| [push](https://github.com/EnomotiaGame/push) | Web Push (RFC 8291/8292) and Firebase Cloud Messaging senders for Go, with no dependencies. Every send tells you whether to keep, retry or delete the subscription. |

More will follow as we pull them out of the game.

## Join in

Everything here is open to you. Report a bug, suggest an idea, send a pull request. A new store, a new platform, or a fix for a case we never met all make the projects better for everyone, including us. Start with [CONTRIBUTING](https://github.com/EnomotiaGame/.github/blob/main/CONTRIBUTING.md).

If you want to see where all this came from, [play ENOMOTIA](https://enomotia.net). It is free.
