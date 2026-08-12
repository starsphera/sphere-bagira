# Bagira — Personal AI Assistant by Sphere

Bagira is a personal AI assistant built by [Sphere](https://starsphera.com) —
a distributed multi-agent AI ecosystem. Bagira helps with everyday
things: answering questions, finding information, creating documents
and images, working with voice messages, and remembering context
across conversations.

## Try it now

**Telegram:** [@sphere_bagira_bot](https://t.me/sphere_bagira_bot)

Just open the link and start talking — no signup form, no waiting list.

## Honest status (as of August 2026)

**Bagira is the one that is genuinely in daily use.** Web search,
weather, routes, place search, document and image handling, reminders,
voice, and a morning digest all work against real data sources, not
mock-ups.

Alongside Bagira there is a family of specialised assistants. Since
July they have moved from "planned" to "built and running", but they
are at different stages and we would rather say exactly where:

| Assistant | State |
|---|---|
| **PetFriend** | Most complete. Pet cards, health history, vaccination schedules, breed reference (dogs and cats), nearby vet search, a Word summary for the vet, photo timeline. |
| **FoodFriend** | Calorie counting and a daily food diary, calories from a meal photo, local Central Asian dishes, profile with BMI and a weight chart, configurable meal reminders. |
| **FitFriend** | Weight and workout logging, progress history, exercise reference. |
| **MindFriend** | Mood logging, goals, journal, simple techniques. |
| **TechFriend** | Documentation lookup, code execution. |

**What "built and running" does not yet mean:** these assistants have
barely been used by real people. PetFriend has two pet cards in the
database; FoodFriend has two diary entries. The code paths are
verified end to end, but they have not met the volume and messiness of
actual users, and that is where things usually break. Treat them as
working software awaiting its first real load, not as proven products.

Every assistant refuses to give medical or veterinary diagnoses and
says so plainly rather than guessing — that boundary is enforced in
code, not just described in a prompt.

## We want your honest feedback

Bagira is under active development. If something is broken, confusing,
slow, or just doesn't feel right — tell us. Open an
[issue](https://github.com/dtajitdinov-aris/sphere-bagira/issues) on
this repo, or just say so directly in the chat with Bagira — complaints
sent that way are routed to a human for review.

## Related

- **Sphere Marketplace** — a working agent-to-agent marketplace with
  escrowed contracts: [sphere-marketplace](https://github.com/dtajitdinov-aris/sphere-marketplace)
- **Sphere Connect** — a bridge between a human and their own AI:
  [sphere-connect](https://github.com/dtajitdinov-aris/sphere-connect)
