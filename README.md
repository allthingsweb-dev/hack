# at/hack

The starting point for a project at an all things hackathon. all things runs free evenings for people who build software in San Francisco; at/hack is the hackathon kind. Teams build something in a set time, show it, and judges pick the winners. Most are lightning hackathons, with about 90 to 120 minutes of hacking. The event page has the schedule.

Template version: **v1.0.0** (see [CHANGELOG.md](CHANGELOG.md))

## Start

1. Click **Use this template** on GitHub (or fork this repository) and create a **public** repository on your own account.
2. Fill in [SUBMISSION.md](SUBMISSION.md) as you go. [LICENSE](LICENSE) credits "the authors of this project"; put your names there if you like.
3. Replace this README with your own, or add to it. Keep the template version line so we know what you started from.

Build with whatever you like, agents included.

## The rule

**Projects must be open source to be judged: a public repository under an OSI-approved license.**

This repository is MIT-licensed. Any [OSI-approved license](https://opensource.org/licenses) is fine: swap the LICENSE file for the one you want.

## Submitting

When submissions close, hand in:

- your public repository's URL
- your team: everyone's name
- one line on what it does

[SUBMISSION.md](SUBMISSION.md) holds the same, plus how to run it. The kickoff says where to hand it in.

## Judging

Judges check that a project is real: they run it, run its tests, read CodeRabbit's review and read the code. Then:

- **It works.** A small thing that works beats a flashy demo that doesn't.
- **It's useful.** Someone would want it.
- **It's creative.** It's an idea worth having.

So say how to run it, and make sure that works from a fresh clone.

[.coderabbit.yaml](.coderabbit.yaml) sets up CodeRabbit's review. CodeRabbit is free for public repositories: install the [CodeRabbit app](https://github.com/apps/coderabbitai) on yours and open a pull request to get a review while you build.

## What's here

| File | What it's for |
| --- | --- |
| README.md | This page. Make it yours. |
| LICENSE | MIT. Swap for any OSI-approved license. |
| SUBMISSION.md | What you hand in, filled in. |
| AGENTS.md | Your project, described for coding agents. CLAUDE.md points to it. |
| .agents/ | Room for agent skills and config. |
| .coderabbit.yaml | CodeRabbit's review settings. |
| .gitignore | The usual things not to commit. |
| CHANGELOG.md | What changed in this template, version by version. |

## For maintainers

This repository is the source of truth every at/hack starts from. The rule above is copied word for word from `core/src/formats.ts` in [allthingsweb-dev/allthingsweb](https://github.com/allthingsweb-dev/allthingsweb); when it changes there, it changes here.

Versions follow [semver](https://semver.org):

- **major**: a rule, submission requirement or judging criterion changes.
- **minor**: something is added that teams may use, such as a new file.
- **patch**: wording and fixes that change nothing a team has to do.

To release: update the version line above and CHANGELOG.md, commit, tag `vX.Y.Z` and publish a GitHub release with the changelog entry as its notes.

CodeRabbit is moving toward a TypeScript config file. When it is stable and documented, it may replace `.coderabbit.yaml` here, as a minor release.
