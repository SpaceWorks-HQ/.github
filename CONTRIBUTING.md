# Contributing to Space Works

Thanks for helping build Space Works, the open-source ecosystem for makerspaces, fab labs, hackerspaces,
tool libraries and maker communities. This guide applies to every repository in
[SpaceWorks-HQ](https://github.com/SpaceWorks-HQ). When a repository has its own `CONTRIBUTING.md`, read
that too: it covers setup, tests and the architecture rules for that codebase.

## Ways to help

You don't need to write code to make a difference.

- **Use it and report what you find.** A clear bug report with steps to reproduce is gold.
- **Tell us how your space works.** Real workflows from real spaces shape what we build next.
  [Share your space's story](https://github.com/SpaceWorks-HQ/.github/issues/new?template=space_story.yml).
- **Improve the docs.** Fix a typo, clarify a step, or write the guide you wished existed in
  [SpaceWorks-Docs](https://github.com/SpaceWorks-HQ/SpaceWorks-Docs).
- **Design.** Feedback on screens, icons and flows belongs in
  [SpaceWorks-Design](https://github.com/SpaceWorks-HQ/SpaceWorks-Design).
- **Hardware.** A tested wiring diagram or IoT integration, with docs, helps the next space copy it.
- **Code.** Pick up an issue and send a pull request.

## Which repository?

| Your change is about… | Repository |
|---|---|
| Inventory, lending, machines, bookings, members, fees, the installer | [SpaceWorks](https://github.com/SpaceWorks-HQ/SpaceWorks) |
| Event pages, registration, tickets, check-in, badges, certificates | [SpaceWorks-Events](https://github.com/SpaceWorks-HQ/SpaceWorks-Events) |
| Membership plans, renewals, payments, GST receipts, member cards | [SpaceWorks-Organization](https://github.com/SpaceWorks-HQ/SpaceWorks-Organization) |
| The team workspace: projects, chat, docs, files, finance, assistant | [SpaceWorks-Workspace](https://github.com/SpaceWorks-HQ/SpaceWorks-Workspace) |
| The iPhone and iPad app | [SpaceWorks-iOS](https://github.com/SpaceWorks-HQ/SpaceWorks-iOS) |
| The Android app | [SpaceWorks-Android](https://github.com/SpaceWorks-HQ/SpaceWorks-Android) |
| Brand, tokens, icons, UX specs | [SpaceWorks-Design](https://github.com/SpaceWorks-HQ/SpaceWorks-Design) |
| Guides and API reference | [SpaceWorks-Docs](https://github.com/SpaceWorks-HQ/SpaceWorks-Docs) |
| The landing page | [SpaceWorks-Website](https://github.com/SpaceWorks-HQ/SpaceWorks-Website) |
| This organisation profile and these shared guides | [.github](https://github.com/SpaceWorks-HQ/.github) |

Not sure? Open the issue where you think it fits. We'll move it if needed.

## From idea to merged

1. **Find or open an issue.** Search first so we don't duplicate work. Newcomers can start with
   [`good first issue`](https://github.com/search?q=org%3ASpaceWorks-HQ+label%3A%22good+first+issue%22+state%3Aopen&type=issues)
   or [`help wanted`](https://github.com/search?q=org%3ASpaceWorks-HQ+label%3A%22help+wanted%22+state%3Aopen&type=issues).
2. **Call dibs.** Comment that you're working on it. For anything large, agree the approach in the issue
   before you write much code.
3. **Fork and branch off `dev`.**

   ```bash
   git checkout dev
   git pull --ff-only origin dev
   git checkout -b feature/<short-name>   # or fix/<short-name>, docs/<short-name>
   ```

   Never commit straight to `dev` or `main`. Maintainers promote tested changes from `dev` to `main`
   through each repository's release process.
4. **Make the change.** Keep it focused on one concern, follow the existing style, add or update tests for
   behaviour changes, and update docs alongside the code.
5. **Commit with clear, conventional subjects**, for example `feat(inventory): …`, `fix(checkin): …`,
   `docs: …` or `chore: …`. Keep the subject to one line.
6. **Open a pull request against `dev`.** Say what changed and why, link the issue (`Closes #123`), list how
   you tested it, and call out any migrations, environment variables or manual steps. The PR template walks
   you through it.
7. **Review.** We'll review with you. Please verify suggestions rather than applying them blindly, and push
   follow-up commits to the same branch.

## Ground rules

- **Privacy first.** Space Works holds members' personal data. Never log, expose or commit secrets or
  personal data, and keep every query scoped to the right space or organisation.
- **No trackers, no ads.** Don't add third-party analytics or tracking.
- **Accessible and themeable.** UI should work with a keyboard, in light and dark mode, and use the
  [design system](https://spaceworks-hq.github.io/SpaceWorks-Design/) tokens rather than hard-coded colours.
- **Be kind.** Everyone here follows our [Code of Conduct](CODE_OF_CONDUCT.md).

## Security issues

Please don't report vulnerabilities in public issues. Follow the [security policy](SECURITY.md).

## Licensing

Space Works is free software under the
[GNU Affero General Public License v3](LICENSE) (AGPL-3.0-or-later).

**No CLA is required.** By submitting a pull request you agree that your contribution is offered under the
same licence as the repository (inbound = outbound). You keep the copyright in your contribution.
