<sub>English · <a href="README.ko.md">한국어</a></sub>

# Hi, I'm RYU-TOMI

Computer engineering undergrad in Seoul. I build **data pipelines and tools around real machines and real users**: a telemetry engine for a Formula Student EV, and a flight-deal map that has been crawling prices twice a day since July 2026.

- **Now:** DAQ (data acquisition) for [LightOn](https://github.com/LightOn-LEF-27), a Formula Student electric team, aiming at FSK E-Formula 2027
- **Heading toward:** vehicle software, especially the data and tooling side
- **How I work:** I build with Claude Code and say so. I own the scope, the structure, and the verification, and I write down what the AI got wrong.

## Selected work

| Project | What it is | My part |
|---|---|---|
| [**LightOnWeb**](https://github.com/LightOn-LEF-27/LightOnWeb) | Formula Student EV telemetry: an engine that normalizes 7 logger formats into one schema and aligns device clocks, plus a data viewer and a live trackside screen. MIT. | Engine and site, sole committer on a 2-person DAQ team. Python · FastAPI · React · uPlot |
| [**galmal**](https://galmal.kr) | "Where could I go?" A discovery map of flight deals departing Korea. Live, crawled twice a day. [backend](https://github.com/RYU-TOMI/galmal-backend) · [frontend](https://github.com/RYU-TOMI/galmal-frontend) · [plan](https://github.com/RYU-TOMI/galmal-plan) | Solo. Product direction, architecture, operations |
| [**resay**](https://github.com/likelion-demoday/be) | Turns a recorded conversation into speaker-separated text and a report on conversation habits. Team project for a startup competition. | Backend (1 of 3): auth, users, deployment, payments and credits. Spring Boot |
| [**DuckSpace**](https://github.com/418teapot-sh/DuckSpace) | A platform for fans to exhibit and trade merchandise. 🏆 Best Potential Award, LIKELION Univ. 14th central hackathon (2026). | Backend (1 of 3): exhibitions, image pipeline, 1:1 chat. Spring Boot |
| [**resume-tree**](https://github.com/RYU-TOMI/resume-tree) | Find and resume old Claude Code sessions from a folder tree and a 3D graph. MIT. | Solo |

## What I care about

- **Data you can trust.** Two loggers whose clocks run at slightly different speeds can flip a conclusion. I check alignment with a second physical signal before comparing anything.
- **Keeping private data out of public code.** Tests in the public repo carry units and tolerances; measured values live in a private expected-values file.
- **One contract between parts.** The engine computes, the site only displays, and a single versioned document defines what passes between them.

## Stack

**Daily:** Python · Java / Spring Boot · TypeScript / React · MySQL · Docker · AWS · GitHub Actions
**Learning:** C on STM32 · CAN
