<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.png">
  <img alt="Space Works: Less searching. More making. Free, open-source software for makerspaces and tool libraries." src="assets/banner-light.png">
</picture>

<p align="center">
  <a href="https://spaceworks-hq.github.io/SpaceWorks-Website/"><b>Website</b></a> ·
  <a href="https://spaceworks-hq.github.io/SpaceWorks-Docs/"><b>Docs</b></a> ·
  <a href="https://spaceworks-hq.github.io/SpaceWorks-Design/"><b>Design system</b></a> ·
  <a href="https://github.com/SpaceWorks-HQ/SpaceWorks#readme"><b>Get started</b></a> ·
  <a href="https://github.com/SpaceWorks-HQ/SpaceWorks/releases/latest"><b>Latest release</b></a> ·
  <a href="https://github.com/SpaceWorks-HQ/SpaceWorks/issues"><b>Say hello</b></a>
</p>

---

### Hey there, maker 👋

**Space Works** is free, open-source software for the people who keep makerspaces humming. It looks after everything from a member's phone to the front desk, and from the parts bin to the machine that needs fixing. Your space keeps running without losing the plot (or the hex keys).

Built in a makerspace, for makerspaces. 🔩

## 🧵 Where it all started

Space Works started at **TinkerSpace**, where I was looking after the hardware and inventory behind day-to-day making. When you're the one checking tools, finding parts and keeping things working, you quickly learn that a makerspace is more than a room full of cool machines.

It's people, access, consumables, bookings, maintenance, and a hundred small details that turn a workshop into a community.

Along the way I set up a fork for TinkerSpace. That was the lightbulb moment 💡: lots of makerspaces need the same things, but not every space has the time, infrastructure or team to build a mobile app, an admin dashboard and all the systems behind them from scratch.

So why should every makerspace have to reinvent the control panel?

Today Space Works runs at **TinkerHub Kochi** and **TinkerHub Calicut**, with **1,000+ members** using it.

## 📦 What's in the box

One install, and you switch on only the parts your space needs. Whatever you leave out simply isn't there.

| Area | What you get |
|---|---|
| 🧰 **Inventory and lending** | A public catalogue, requests, front-desk handovers and returns, QR labels and stocktake. Every handover is scanned, photographed and noted. |
| 🔧 **Machines** | A machine registry, certifications, service and 3D-print queues, and maintenance schedules. |
| 📅 **Events and bookings** | Free, invite-only or paid events with QR check-in, plus rooms and resources with recurring slots. |
| 👥 **Members** | One personal account per person, a member area for their loans and fees, and optional membership plans and renewals. |
| 💸 **Money** | Fees, deposits and receipts are always tracked. Stripe or Razorpay checkout is optional. |
| 📊 **Reports and alerts** | A report for every module, plus notifications, email and chat alerts in Telegram, Slack, Discord or Mattermost. |
| 🔐 **Running it** | Many spaces on one server, roles you define, an append-only audit log, encrypted backups, bundled Silo object storage and safe updates from GitHub releases. |

**Apps 📱:** native member apps for iOS (SwiftUI) and Android (Kotlin and Compose, phones and tablets) are in active development. Both are white-label: point them at your own server, and they draw their colours and logos from the shared design system.

**Still on the workbench 🧪:** finishing and publishing those apps, and more IoT integrations for tool status, access hardware and sensors. Every hardware integration will get its own docs so other spaces can copy it, change it and make it better.

We'd rather build the right tools alongside real makerspaces than ship a shiny black box.

## 🗂️ Find your way around

| Repository | What lives there |
|---|---|
| [**SpaceWorks**](https://github.com/SpaceWorks-HQ/SpaceWorks) | The main app: server, staff console, member area and installer ([latest release](https://github.com/SpaceWorks-HQ/SpaceWorks/releases/latest)) |
| [**SpaceWorks-Docs**](https://github.com/SpaceWorks-HQ/SpaceWorks-Docs) | Guides for setting up, running and extending Space Works ([read them](https://spaceworks-hq.github.io/SpaceWorks-Docs/)) |
| [**SpaceWorks-Design**](https://github.com/SpaceWorks-HQ/SpaceWorks-Design) | The design system: logos, colours, fonts, design tokens and UI specs ([browse it](https://spaceworks-hq.github.io/SpaceWorks-Design/)) |
| [**SpaceWorks-Website**](https://github.com/SpaceWorks-HQ/SpaceWorks-Website) | The public landing page ([visit it](https://spaceworks-hq.github.io/SpaceWorks-Website/)) |
| [**SpaceWorks-iOS**](https://github.com/SpaceWorks-HQ/SpaceWorks-iOS) | Native iOS 17+ app in SwiftUI, in development 📱 |
| [**SpaceWorks-Android**](https://github.com/SpaceWorks-HQ/SpaceWorks-Android) | Native Android 8+ app in Kotlin and Compose, for phones and tablets, in development 📱 |

### 🌐 Hosted sites

| Site | Address |
|---|---|
| 🏠 Website | [spaceworks-hq.github.io/SpaceWorks-Website](https://spaceworks-hq.github.io/SpaceWorks-Website/) |
| 📖 Docs | [spaceworks-hq.github.io/SpaceWorks-Docs](https://spaceworks-hq.github.io/SpaceWorks-Docs/) |
| 🎨 Design system | [spaceworks-hq.github.io/SpaceWorks-Design](https://spaceworks-hq.github.io/SpaceWorks-Design/) |

## 🚀 Try it on your own server

On a Linux server, as a user with `sudo`:

```bash
curl -fsSL https://raw.githubusercontent.com/SpaceWorks-HQ/SpaceWorks/main/install.sh | bash
```

The installer asks every question first and changes nothing until you confirm. Running a fork? The same command works: its first question asks which repository to install and update from. Want to look before you leap? [Read `install.sh`](https://github.com/SpaceWorks-HQ/SpaceWorks/blob/main/install.sh).

## 🌱 Where this is going

This isn't software for just one space. The goal is to give every makerspace a solid starting point, so nobody has to build a whole digital ecosystem before they can get back to making.

We're growing this organisation with the people and makerspaces who want to join in. The opportunities that came our way should reach others too. Everything here is open source: inspect it, self-host it, bend it to fit your weird and wonderful workflow, and send your improvements back upstream.

## 👋 The people behind it

| | Who | What they did | Reach them for |
|---|---|---|---|
| 🛠️ | **Shaan Shoukath** ([@Shaan-Shoukath](https://github.com/Shaan-Shoukath)) | Created and built Space Works end to end: the server, staff console, member area, installer and the iOS and Android mobile apps. Maintains it today. | Bugs, features, installs, code reviews and anything else |
| 🎨 | **Suraj Sunil** ([@thisisonebit](https://github.com/thisisonebit)) | Designed the look and feel: the brand, logos, colours and the [design system](https://spaceworks-hq.github.io/SpaceWorks-Design/) the web console and mobile apps are built from. | Design, branding and UI feedback |

Not sure who to ask? [Open an issue](https://github.com/SpaceWorks-HQ/SpaceWorks/issues/new/choose) and mention whichever of us fits. It always reaches the right person, and the answer helps the next person with the same question.

And a big thank you 🙏 to everyone who has reported a bug, tested a release, suggested a feature or sent a pull request. Space Works is better because of you, and every merged contribution is credited in [CONTRIBUTORS.md](https://github.com/SpaceWorks-HQ/SpaceWorks/blob/main/.github/CONTRIBUTORS.md).

## 🤝 Pull up a chair

The best contributions come from people who actually use Space Works. Here's the path from "huh, that's odd" to your name in the credits:

**1. 🛠️ Use it.** Install it on a server, or run it locally with demo data by following [DEVELOPMENT.md](https://github.com/SpaceWorks-HQ/SpaceWorks/blob/main/.github/DEVELOPMENT.md). Lend a drill, book a room, break things on purpose.

**2. 🔍 Find something.** Spotted a bug, a confusing screen or a missing feature? [Open an issue](https://github.com/SpaceWorks-HQ/SpaceWorks/issues/new/choose) using the bug or feature template. Looking for somewhere to start? Browse [`good first issue`](https://github.com/SpaceWorks-HQ/SpaceWorks/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) and [`help wanted`](https://github.com/SpaceWorks-HQ/SpaceWorks/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22).

**3. 🙋 Call dibs.** Comment on the issue to say you're on it, so nobody else builds the same thing.

**4. 🔧 Fix it.** Fork the repo, branch off `dev` (`fix/<short-name>` or `feature/<short-name>`), make your change and run the tests. The [contributing guide](https://github.com/SpaceWorks-HQ/SpaceWorks/blob/main/.github/CONTRIBUTING.md) has the house rules.

**5. 📬 Open a pull request against `dev`.** Say what changed and why, and link the issue. The PR template walks you through the rest.

**6. 🎉 Get merged.** We'll review it with you. Once it's merged it ships in the next release, and you're credited in [CONTRIBUTORS.md](https://github.com/SpaceWorks-HQ/SpaceWorks/blob/main/.github/CONTRIBUTORS.md).

No CLA, no gatekeeping. Contributions are shared under the project's AGPL-3.0 licence, and you keep the copyright.

**Not a coder?** You're still very welcome. Docs, translations, a fixed typo, a tested wiring diagram, design feedback and a clear bug report all help the next makerspace. **Run a makerspace?** Open an issue and tell us how your space works. We'd love to hear it.

> 🔒 Found a security issue? Please don't post it publicly. Follow the [security policy](https://github.com/SpaceWorks-HQ/SpaceWorks/blob/main/.github/SECURITY.md) to report it privately.

---

<p align="center">
  <img src="assets/symbol.svg" alt="" width="40"><br>
  <sub>Made with ❤️, care and probably a little filament dust, for <b>community makerspaces</b> everywhere, and for anyone who has ever had to ask <i>"who has the drill?"</i></sub>
</p>
