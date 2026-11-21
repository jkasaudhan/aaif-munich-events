# Agents Need Access. Why Are We Handing Them the Keys?

**Speaker:** Martin Riedel
**Event:** AAIF Community Munich #30

## About the talk

The talk introduces **ShellWatch**, an SSH broker for humans and AI agents that only works with passkeys. Each SSH challenge is signed by a passkey, so the private key never leaves your device. You approve each signing request in the browser or on your phone. Agents reach servers through MCP or through a local `shellwatch-agent` proxy that acts as an SSH agent. Every action goes into an audit log that shows if it has been tampered with.

The problem it addresses: agents need SSH access, but today that usually means giving them a private key.

## Demo recordings

The talk itself was not recorded. Martin re-recorded all six demos (about 24 minutes) and posted them on his blog:
**▶ [Passkey-Backed SSH in Six Demos](https://riedel-it.de/blog/aaif-munich-shellwatch-demos/)**

| Time  | Segment |
|-------|---------|
| 0:00  | Intro: ShellWatch and its three endpoints |
| 3:39  | Demo 1: Opening a session from a Mac or a phone |
| 6:40  | Demo 2: TVHeadend is down, fixed by voice |
| 10:48 | Demo 3: A countdown to GTA VI |
| 13:50 | Demo 4: `sudo`, with approval |
| 16:20 | Demo 5: Your own terminal, the same passkey |
| 18:52 | Demo 6: A link that works for one session only |
| 21:57 | Discussion: why agents could drive passkey adoption |

## Links

- Website: https://shellwatch.ai/
- Source code: https://github.com/rado0x54/ShellWatch (the README there explains how to install and run it)

## 💬 Martin is looking for feedback

The project is at an early stage, and Martin would really like more people to look at it. In particular:

1. **Is this a workable answer to an access problem you have day to day?** For example, giving coding agents or ops agents access to servers.
2. **What would you improve, or which features are missing?**

Please open an issue or a discussion on the [GitHub repo](https://github.com/rado0x54/ShellWatch), or contact Martin in the AAIF Munich Slack.
