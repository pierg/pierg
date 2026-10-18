## Piergiuseppe (Pier) Mallozzi

I build agent systems and bring research ideas into production. I design systems the way formal methods taught me: in contracts, what each part assumes, what it guarantees, and how the parts compose.

### Building now

Three tools for working with coding agents. Each puts a check the agent cannot talk past between its work and what counts as done.

- **[folio](https://github.com/pierg/folio)**: a knowledge library an agent writes and keeps, with no fixed template: each page takes the form that explains it best, from interactive HTML with figures, controls and math to a LaTeX paper, and on every save code checks each link and that no recorded entry was edited. `uv tool install folio-kb`
- **[lab-kit](https://github.com/pierg/lab-kit)**: a research lab run by agents, on folio. Each hypothesis, with the predictions that could refute it and the rules that decide them, is frozen before the first run, every reported number is recomputed from sealed run output on each check, and a reviewer agent with a fresh context checks that the analysis supports the report. `uv tool install lab-kit-cli`
- **[giro](https://github.com/pierg/giro)**: a loop around a coding agent. Each issue of a spec goes to a fresh agent, your tests and blind reviewers judge every attempt within a fixed budget, and the loop, the budget and the exits are code, so they hold whichever agent does the work. `uv tool install giro`

### Earlier research

- **[Pacti](https://github.com/pacti-org/pacti)**: compositional system analysis with assume-guarantee contracts, used in a NASA JPL Mars entry, descent and landing case study.
- **[CROME](https://github.com/pierg/crome-cgg)**: correct-by-construction robotic missions, from contracts over temporal logic to synthesized controllers.
- **[Fact Fortress](https://github.com/pierg/fact-fortress-dapp)**: zero-knowledge proofs for private fact-checking. First place, UC Berkeley ZKP Hackathon.
- **[Cloud Guardian](https://github.com/pierg/cloud-guardian)**: graph analysis of AWS IAM policies for privilege escalation. Part of CloudShieldAI, Craft Ventures HackAIthon grand prize.

PhD in formal methods at Chalmers, postdoc at UC Berkeley, with work funded by NASA and DARPA.

[pierg.dev](https://pierg.dev) · [Google Scholar](https://scholar.google.com/citations?user=lrDnPyoAAAAJ&hl=en) · [LinkedIn](https://www.linkedin.com/in/piergiuseppe/)

<!-- Generated from content/ by build_github.py — edit content, not this file. -->
