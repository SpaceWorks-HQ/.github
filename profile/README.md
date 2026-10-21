<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.png">
  <img alt="Space Works: Less searching. More making. Free, open-source software for makerspaces and tool libraries." src="assets/banner-light.png">
</picture>

<p align="center">
  <a href="https://spaceworks-hq.github.io/SpaceWorks-Website/"><b>Website</b></a> ·
  <a href="https://spaceworks-hq.github.io/SpaceWorks-Docs/"><b>Docs</b></a> ·
  <a href="https://spaceworks-hq.github.io/SpaceWorks-Design/"><b>Design system</b></a> ·
  <a href="https://github.com/SpaceWorks-HQ/SpaceWorks#readme"><b>Get started</b></a> ·
  <a href="https://github.com/SpaceWorks-HQ/.github/blob/main/CONTRIBUTING.md"><b>Contribute</b></a> ·
  <a href="https://github.com/SpaceWorks-HQ/.github/blob/main/SUPPORT.md"><b>Get help</b></a>
</p>

---

### Hey there, maker 👋

**Space Works** is free, open-source software for running a makerspace, fab lab or hackerspace, along with the community, the events and the team around it. Everything is self-hosted, so your members' data stays on your own server.

Built in a makerspace, for makerspaces. 🔩

## 🧰 SpaceWorks runs the whole makerspace

[**SpaceWorks**](https://github.com/SpaceWorks-HQ/SpaceWorks) is the heart of it: one install that runs a makerspace from end to end. You switch on only the modules your space needs, and whatever you leave out simply isn't there.

- **Inventory and lending:** a public catalogue, borrow requests, front-desk handovers and returns that are QR-scanned and photographed, stocktake, transfers and purchasing.
- **Machines:** a machine registry, 3D-print and service queues, maintenance schedules and warranties.
- **Events:** one-off and recurring events, registration with approvals and waitlists, QR check-in at the door, badges, feedback and certificates.
- **Bookings:** rooms and resources, including public self-booking.
- **Membership:** join requests, membership plans, waivers, referrals, maker profiles and presence.
- **Payments:** fees, deposits and receipts, with optional Stripe or Razorpay checkout.
- **Reports and alerts:** a report for every module, plus alerts by email and in Telegram, Slack, Discord or Mattermost.
- **Running it:** many spaces on one server, roles you define, an append-only audit log, encrypted backups and safe updates from GitHub releases.

Today it runs at **TinkerHub Kochi** and **TinkerHub Calicut**, with **1,000+ members** using it.

## 🧩 Going deeper

SpaceWorks already covers events and memberships for a makerspace. When one job needs more, these apps focus on it. Each one runs on its own or alongside SpaceWorks.

🎟️ [**SpaceWorks Events**](https://github.com/SpaceWorks-HQ/SpaceWorks-Events) is for managing events: event pages, registration forms, live QR tickets, offline check-in at the door, ID cards and badges, member IDs and certificates. Use it for meetups, workshops, hackathons and demo days.

🪪 [**SpaceWorks Organization**](https://github.com/SpaceWorks-HQ/SpaceWorks-Organization) is fully for membership management: plans, join forms and approvals, renewals and reminders, payments by Razorpay, Stripe, UPI or cash, GST receipts and member ID cards anyone can verify with a scan. It's built for clubs, associations, chapter networks and alumni bodies. *In active development.*

🚀 [**SpaceWorks Workspace**](https://github.com/SpaceWorks-HQ/SpaceWorks-Workspace) runs internal team ops: projects and kanban, chat, docs, files, finance and an AI assistant, for the core team behind a space or an early-stage startup. *Early build.*

Use one, or run them all together for a complete ecosystem.

## 📱 Apps and foundations

- [**SpaceWorks-iOS**](https://github.com/SpaceWorks-HQ/SpaceWorks-iOS) and [**SpaceWorks-Android**](https://github.com/SpaceWorks-HQ/SpaceWorks-Android) are native member apps for browsing and borrowing tools, scanning QR codes and tracking loans. Both are white-label: point them at your own server. *In development.*
- [**SpaceWorks-Design**](https://github.com/SpaceWorks-HQ/SpaceWorks-Design) holds the shared brand, logos, icons, fonts, design tokens and UX specs ([browse it](https://spaceworks-hq.github.io/SpaceWorks-Design/)).
- [**SpaceWorks-Docs**](https://github.com/SpaceWorks-HQ/SpaceWorks-Docs) covers installing, self-hosting, staff guides and the API ([read them](https://spaceworks-hq.github.io/SpaceWorks-Docs/)).
- [**SpaceWorks-Website**](https://github.com/SpaceWorks-HQ/SpaceWorks-Website) is the public landing page ([visit it](https://spaceworks-hq.github.io/SpaceWorks-Website/)).

Everything is licensed under **AGPL-3.0**: no paid tier, no trackers and no lock-in.

## 🚀 Try it on your own server

On a Linux server, as a user with `sudo`:

```bash
curl -fsSL https://raw.githubusercontent.com/SpaceWorks-HQ/SpaceWorks/main/install.sh | bash
```

The installer asks every question first and changes nothing until you confirm. Running a fork? The same command works: its first question asks which repository to install and update from. Want to look before you leap? [Read `install.sh`](https://github.com/SpaceWorks-HQ/SpaceWorks/blob/main/install.sh).

Events, Organization and Workspace each have their own quick start in their READMEs.

## 🧵 Where it all started

Space Works started at **TinkerSpace**, where I was looking after the hardware and inventory behind day-to-day making. When you're the one checking tools, finding parts and keeping things working, you quickly learn that a makerspace is more than a room full of cool machines.

It's people, access, consumables, bookings, maintenance, events, memberships and a hundred small details that turn a workshop into a community.

Along the way I set up a fork for TinkerSpace. That was the lightbulb moment 💡: lots of makerspaces need the same things, but not every space has the time, infrastructure or team to build a mobile app, an admin dashboard and all the systems behind them from scratch.

So why should every makerspace have to reinvent the control panel?

## 🌱 Where this is going

The goal is to give every makerspace, fab lab and maker community a solid starting point, so nobody has to build a whole digital ecosystem before they can get back to making.

On the workbench 🧪: publishing the iOS and Android apps, finishing Organization and Workspace, and more IoT integrations for tool status, access hardware and sensors. Every hardware integration gets its own docs so other spaces can copy it, change it and make it better.

We'd rather build the right tools alongside real makerspaces than ship a shiny black box.

## 🤝 Pull up a chair

The best contributions come from people who actually use Space Works:

1. **🛠️ Use it.** Install it, or run it locally with demo data. Lend a drill, book a room, break things on purpose.
2. **🔍 Find something.** Open an issue in the right repository, or pick up a [`good first issue`](https://github.com/search?q=org%3ASpaceWorks-HQ+label%3A%22good+first+issue%22+state%3Aopen&type=issues).
3. **🙋 Call dibs.** Comment on the issue so nobody else builds the same thing.
4. **🔧 Fix it.** Fork the repo, branch off `dev`, make your change and run the tests.
5. **📬 Open a pull request against `dev`.** Say what changed and why, and link the issue.
6. **🎉 Get merged.** We'll review it with you, and it ships in the next release.

The [contributing guide](https://github.com/SpaceWorks-HQ/.github/blob/main/CONTRIBUTING.md) has the house rules. No CLA, no gatekeeping: contributions are shared under AGPL-3.0, and you keep the copyright.

**Not a coder?** Docs, translations, design feedback, a tested wiring diagram and a clear bug report all help. **Run a makerspace?** [Tell us how your space works](https://github.com/SpaceWorks-HQ/.github/issues/new?template=space_story.yml).

> 🔒 Found a security issue? Please don't post it publicly. Follow the [security policy](https://github.com/SpaceWorks-HQ/.github/blob/main/SECURITY.md) to report it privately.

---

<p align="center">
  <img src="assets/symbol.svg" alt="" width="40"><br>
  <sub>Made with ❤️, care and probably a little filament dust, by the makers of the <b>TinkerSpace community</b>.</sub>
</p>
