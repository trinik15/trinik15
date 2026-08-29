# trinik15

I build tools that turn messy source data into something a person can actually
use — biomedical literature into variant datasets, pitch-level MLB data into
scouting reports, live campaign data into strategic dashboards.

## Selected work

### [prnp-variant-analyzer](https://github.com/trinik15/prnp-variant-analyzer) · TypeScript
Turns PubMed abstracts on the PRNP gene into a structured variant/evidence
dataset: deterministic variant extraction (codon window 40–243, cross-gene
lookalike guard, codon-129 shorthand folding), evidence tiers from a curated
knowledge base, frequency reports and CSV/Markdown export — plus a standalone
Biopython pipeline that mirrors the TypeScript engine 1:1.

- [Live demo](https://prnp-variant-analyzer.space-z.ai/) · CI · MIT
- Research software: it describes the literature, it makes no clinical claims.

### [pitchiq](https://github.com/trinik15/pitchiq) · Python
MLB pitcher scouting dashboard built on free Statcast data — pitch mix,
movement, velocity trends, zone heatmaps and sequencing patterns computed live
for any pitcher. [Live demo](https://pitchiq-aqx.streamlit.app/)

### [warfare-tracker](https://github.com/trinik15/warfare-tracker) · TypeScript
Allied Watch — real-time strategic intelligence dashboard for the WWII Online
campaign: briefings, war reports and an assistant chat over live campaign
state (Next.js + Prisma + a dedicated push service).

### [LambatRegistryBot](https://github.com/trinik15/LambatRegistryBot) · Python
Discord registry bot for the CivMC community.

## Stack
TypeScript · Next.js · React · Python · Prisma/SQLite · Tailwind CSS · GitHub Actions CI
