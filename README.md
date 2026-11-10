# A Folder That Knows What It Knows

An interactive explainer of the Open Knowledge Format (OKF), told through a made-up bike shop called Halfway Cycles.

The whole page is one file, `index.html`. Open it in a browser. There is no build step and nothing to install. The only thing it loads from the network is its fonts.

## Sections

1. **Why write it down this way.** Six reasons, each linked to the section that shows it.
2. **Start with one page.** One OKF file, line by line.
3. **What goes in the folder.** Pages, plus four housekeeping files: `index.md`, `log.md`, `README.md` and `AGENTS.md`.
4. **A folder an agent can navigate.** Index files, links, and reading only what a question needs.
5. **Who wrote it, who checked it, and is it still true.** The `generated`, `verified`, and `stale_after` lines.
6. **Letting an agent write the first draft.** The explore-and-draft pattern, generalized beyond one database.
7. **Then someone has to keep it current.** One change followed through git: the agent's commit, then the owner's sign-off.
8. **A number that can show its work.** Attested Computations.
9. **What OKF leaves out on purpose.** Non-goals, and the house rules teams add on top.
10. **Point an agent at what you have.** A copyable brief for drafting a bundle from your own source.

## Changing the example

The bike shop is data, not prose baked into the layout. In the script at the bottom of `index.html`:

- `DIRS` and `C` hold the bundle's folders and its nine pages (titles, descriptions, word counts, links).
- `HOUSE` holds the four housekeeping files (the root index, the log, the README and the AGENTS file).
- Each exhibit keeps its own small data block next to its code: `NOTES` (the annotated file), `QS` (the three questions), `P` (who wrote and checked each page), `S` (the four sources), `U` (the e-bike change and its two commits), `M` (the monthly numbers).

Swapping the shop for another setting means rewriting those blocks and the sentences around the exhibits.

## Sources

- [Open Knowledge Format specification, version 0.2](https://github.com/GoogleCloudPlatform/open-knowledge-format/blob/main/SPEC.md) (read 2026-11-10)
- [The OKF repository](https://github.com/GoogleCloudPlatform/open-knowledge-format), Apache 2.0 license

Halfway Cycles, its staff, and its numbers are invented. This is an independent explainer and is not affiliated with Google. The page was written by an AI model directed by a person. A second AI model has reviewed it line by line against the specification. A person then edited it for clarity; no person has checked it against the specification.
