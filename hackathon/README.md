# Hackathon · 16–20 November 2026

One week, one product: a model → an API → an app → a demo. Every deadline is **the start of the next class, 10:00**.

⚠️ **Do only today's step.** Each day builds on the day before and must work before the next starts. Do not let an AI agent build the whole week at once: you must be able to explain every part.
Your team repository grows one folder per day: `01_autoencoder/` → `02_model_server/` → `03_app/` → `04_final/`.
The full brief, folders and checklists: [`submissions/README.md`](submissions/README.md).

| Day | Topic | Slides | Notebook | Example code | You hand in (folder · deadline) |
|---|---|---|---|---|---|
| **Mon 16** | Autoencoders | [01](docs/slides/01_autoencoders_applied_stories.pptx) | [`01_autoencoders.ipynb`](docs/01_autoencoders.ipynb) · [DATASETS](docs/DATASETS.md) | — | `01_autoencoder/` · Tue 10:00 |
| **Tue 17** | Bring your model online (Render) | [02](docs/slides/02_bring_your_model_online.pptx) | [`02_deployment.ipynb`](docs/02_deployment.ipynb) §2 · [guides](docs/guides/README.md) | [`model_app/`](docs/model_app) | `02_model_server/` · Wed 10:00 |
| **Wed 18** | From model to app (Cloudflare, data, users) | [03](docs/slides/03_from_model_to_app.pptx) | [`02_deployment.ipynb`](docs/02_deployment.ipynb) §3 | [`cloudflare_app/`](docs/cloudflare_app) | `03_app/` · **Thu 10:00** · [what exactly](submissions/README.md#6-wednesday-the-app) |
| **Thu 19** | Users, data, money, the live demo | [04](docs/slides/04_users_data_money.pptx) | — | — | `04_final/` · **Fri 10:00 (freeze)** · [what exactly](submissions/README.md#7-thursday-the-final-app-and-the-explanation) |
| **Fri 20** | Live demo, 5–8 min per team | — | — | — | [how](submissions/README.md#8-friday-the-live-demo) |

**Wednesday in one line:** on Miro, 2 user stories, 1 system diagram and 2–3 sequence diagrams; then an app on Cloudflare with a password that calls your Render API and saves results in D1. Copy [`cloudflare_app/`](docs/cloudflare_app) into `03_app/` of your team repo, next to `02_model_server/`.

**Thursday in one line:** finish the app in `04_final/`: three diagrams (system, user flow, sequence), the three statements, and `PROOFS.md` (database, locked on the server, connected to Render, no secrets in git). Optional: one item from class (user accounts, privacy page, analytics), only if it works. Prepare the 5–8 min live demo.

Impulse talks: [`docs/IMPULSE_TALKS.md`](docs/IMPULSE_TALKS.md).
