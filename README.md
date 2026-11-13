### Matthew Alberto

Software engineer and legal engineer from Sydney, Australia. I build agents that run on their own and do real work, and the guardrails that keep them safe. Co-founder of [Legaseek](https://legaseek.ai), legal AI for donor-restricted gifts and endowments at US colleges and universities.

- **Now:** almost everything I build, I build with Claude Code. My private agent workspace has more than 3,500 commits co-authored with Claude Code since May 2026: scheduled headless agents, 100+ reusable skills, git-tracked memory and hooks that block repeat mistakes.
- **Before:** founding software engineering team at Fluent Forever ($0 to $2.5M ARR, Series A), and 15 years engineering the software systems Australian charities and foundations use to receive and receipt gifts online.
- **Law:** Master of Laws, UCL Faculty of Laws. I build the software legal and finance teams use.
- **Stack:** Python, TypeScript, React, Node, Astro, Tailwind, Flutter and Dart.
- **Cloud:** Google Cloud and Firebase (Firestore, Cloud Functions, BigQuery, Secret Manager), Cloudflare (Workers, Pages).

#### Public tools

| Repo | What it does |
|---|---|
| [eval-tasks](https://github.com/matthewalberto/eval-tasks) | Evaluation tasks for AI coding agents in the Harbor format, built from real changes, with graders that check behaviour and score shortcuts 0 |
| [claude-code-guardrails](https://github.com/matthewalberto/claude-code-guardrails) | Claude Code hooks that stop an agent repeating a known mistake, each with a self-test |
| [agent-worktree-merge-drivers](https://github.com/matthewalberto/agent-worktree-merge-drivers) | Git merge drivers so parallel agents can append to the same logs and tables without conflicts |
| [agent-os-starter](https://github.com/matthewalberto/agent-os-starter) | A template for organising a Claude Code workspace: pointer files, one-fact memory, skills, closed loops |
| [claim-lint](https://github.com/matthewalberto/claim-lint) | Stops a retracted claim reaching a website, post or grant application again |
| [a11y-gate](https://github.com/matthewalberto/a11y-gate) | WCAG 2.2 checks that fail a release on any violation |
| [email-auth-audit](https://github.com/matthewalberto/email-auth-audit) | SPF, DKIM and DMARC checks for offices that send donor or student email |
| [windows-ocr-cli](https://github.com/matthewalberto/windows-ocr-cli) | OCR for scanned PDFs on Windows, with nothing uploaded |
| [media-prep](https://github.com/matthewalberto/media-prep) | Normalise audio and fit videos under upload limits |
| [transcript-fetch](https://github.com/matthewalberto/transcript-fetch) | Transcripts from captions, with a local Whisper fallback |

#### Gists

| Gist | What it does |
|---|---|
| [pdf-sign-locally](https://gist.github.com/matthewalberto/812261b1d9337e376fdfc1becd400233) | Sign a PDF with your finger in the browser, then place the signature on the form's signature line, with nothing uploaded |

#### Open-source contributions

| Project | What the fix does | Status |
|---|---|---|
| [Anki](https://github.com/ankitects/anki) [#5913](https://github.com/ankitects/anki/pull/5913) | Images copied from apps like Discord now paste as the real image instead of a broken link. | Open |
| [Anki](https://github.com/ankitects/anki) [#5957](https://github.com/ankitects/anki/pull/5957) | Regex searches keep their quotes when Anki tidies the search bar, so they no longer need re-typing. | Open |
| [Blockly](https://github.com/RaspberryPiFoundation/blockly) [#10682](https://github.com/RaspberryPiFoundation/blockly/pull/10682) | Duplicating a block nested inside another now places the copy beside it, instead of pushing the original stack away. | Open |
| [MIT App Inventor](https://github.com/mit-cml/appinventor-sources) [#4235](https://github.com/mit-cml/appinventor-sources/pull/4235) | Dictionary blocks now refuse list position 0 instead of returning, or overwriting, a hidden list marker. | Open |
| [TextArena](https://github.com/TextArena/TextArena) [#218](https://github.com/TextArena/TextArena/pull/218) | The SpellingBee word game now gives players the full set of distinct letters it promises, favouring common letters, instead of as few as 4 of 7. | Open |
| [Flame](https://github.com/flame-engine/flame) [#4214](https://github.com/flame-engine/flame/pull/4214) | Text boxes in the Flutter game engine can now limit how many lines they show, with the box size and typing effect following the limit. | Merged Nov 2026 |
| [Flame](https://github.com/flame-engine/flame) [#4230](https://github.com/flame-engine/flame/pull/4230) | Combining two text styles now keeps everything the second one leaves unset, instead of resetting it to the defaults. | Open |
| [FSRS](https://github.com/open-spaced-repetition/py-fsrs) [#159](https://github.com/open-spaced-repetition/py-fsrs/pull/159) | Randomly spread review intervals now always stay inside their intended range of days. | Open |
| [FSRS](https://github.com/open-spaced-repetition/fsrs-rs) [#482](https://github.com/open-spaced-repetition/fsrs-rs/pull/482) | Upgrades the spaced-repetition scheduler's random number libraries and checks that its seeded simulations and training still give the same results. | Merged Nov 2026 |
| [Harbor](https://github.com/harbor-framework/harbor) [#3751](https://github.com/harbor-framework/harbor/pull/3751) | The terminus-2 agent now says tmux is missing instead of "Error: None" in an offline task. Found while running my own eval task; issue [#3750](https://github.com/harbor-framework/harbor/issues/3750) | Open |
| [Juriscraper](https://github.com/freelawproject/juriscraper) [#2319](https://github.com/freelawproject/juriscraper/pull/2319) | Two court scrapers no longer return empty values from `extract_from_text`, with a new test that checks every scraper that has test data | Open |
| [Juriscraper](https://github.com/freelawproject/juriscraper) [#2320](https://github.com/freelawproject/juriscraper/pull/2320) | The Tennessee workers' compensation backscraper works again, so the archive back to 1996 can be collected | Open |

Most of my work is in private repos; I'm happy to walk through it on a call.

Need a tool like these for your team or institution? Get in touch on [LinkedIn](https://www.linkedin.com/in/matthewalberto) or at [matthewalberto.com](https://matthewalberto.com).
