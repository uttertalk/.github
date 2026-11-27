<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/uttertalk/brand/main/logos/utter-logo-light.svg">
  <img src="https://raw.githubusercontent.com/uttertalk/brand/main/logos/utter-logo-color.svg" alt="Utter" height="40">
</picture>

**Your users ask. Your app changes.**

Add Utter to your SaaS once. Your users ask for what they want, out loud or typed, and your app changes for them. They can change how it looks, just for themselves: dark mode, bigger text, a hidden column, on every device they use. And they can ask for work, which Utter does inside your app, as them, with only the actions you allow, and then tells them what it did.

[utter.talk](https://www.utter.talk) runs on Utter itself: press "Try Utter" and change how the site looks for you.

- **[Website](https://www.utter.talk)**: free on your own Claude or Gemini key. AI included, where Utter supplies the AI, is coming soon
- **[SDK](https://github.com/uttertalk/sdk)**: `npx utter-sdk init` connects your product, and your AI coding agent writes the action list. Open source under MIT
- **[Brain](https://github.com/uttertalk/brain)**: the brain behind Utter, with every prompt its AI is told and the safety checks, exactly as they run on our servers. Run its tests without a key. On npm as `utter-brain`
- **[Docs](https://github.com/uttertalk/docs)**: from an empty project to Utter working in your app
- **[Example app](https://github.com/uttertalk/example-app)**: a sample CRM with Utter built in, a complete working example
- **[Brand](https://github.com/uttertalk/brand)**: logo, mark and colors
- **[Live demo](https://demo.utter.talk/try)**: a sample CRM with Utter in it, one click, no sign-up
- **[Status](https://www.utter.talk/status)**: whether the service, database and demo are up right now
- **[X](https://x.com/utterdottalk)**: news and updates, @utterdottalk

### How it's kept safe

The rules live on Utter's servers, not in a prompt someone can talk their way around. They're all public in [brain](https://github.com/uttertalk/brain).

- **Only your actions.** Utter can only call the actions you list, and never one you switched off.
- **As the person asking.** Every call runs as the signed-in user, inside their own company. Your permission checks still apply.
- **A yes before any change.** Reading runs right away. Anything that changes data becomes a plan the user confirms first. A plan expires after 5 minutes and runs once.
- **Every request logged.** What was asked, which actions ran, what changed and whether it worked, in your dashboard.
- **Signed calls.** Every call between Utter and your app is signed with your project secret.
- **Their own look, nothing more.** People can change how your app looks for themselves. It's styling only, checked before it reaches anyone's browser.
- **Your team, your call.** Invite your team to the dashboard by email. Only the project's owner can delete it or change who's on the team.

### Roadmap

Planned, not built yet:

- **Instant voice-to-voice.** Utter hears, acts and answers in under half a second, with a natural voice that can be interrupted mid-sentence like a person.
- **Our own speech model.** Trained on how people actually talk to software, so it understands names, numbers and jargon from your app that general models get wrong.
- **On-device mode.** Speech and planning run in the browser or on the phone, so nothing leaves the device until an action runs.
- **Every language.** Talk to any app in 50+ languages and accents, and get answers back in the same one.
- **Learns your app on its own.** Point Utter at your product and it maps every screen and action itself. No action list to write.
- **Sees the screen.** Utter understands what the user is looking at, so "move this one to next week" just works.
- **Call your app.** Every product gets a phone number. Users call in, say what they want, and Utter does it while they're on the line.
- **Native mobile.** SDKs for iOS and Android, with the same Utter button inside your mobile app.
- **Every backend.** Server packages for Python, Ruby, Go, Java and PHP, next to Node.
- **Self-hosted Utter.** The whole service running inside your own cloud, on your own models, for companies that can't send data out.
- **SOC 2 and HIPAA.** Audited security so banks, hospitals and big companies can use it.

### Support Utter

All of these features take serious money to build: training models, running voice at scale, and paying for audits. If you want to see them happen, donate here:

| | |
|---|---|
| Bitcoin | `bc1qy9ftrswva8r8nplll69dhsujhlqqqnx6d2sp6l` |
| Ethereum | `0x2CbE1A2448f2f1F749872F8962fA4faB73Df74B6` |
| Solana | `9GakVxzMhWf9hfDPoDgExR7JLraZGkPpT1pWfsDof5A8` |

The Ethereum address also takes USDC and USDT, and the Solana address also takes USDC on Solana.

Utter is run by Utter LLC.

Questions: hello@utter.talk · [X](https://x.com/utterdottalk) · [Trustpilot](https://www.trustpilot.com/review/utter.talk) · [open an issue](https://github.com/uttertalk/sdk/issues/new/choose)
