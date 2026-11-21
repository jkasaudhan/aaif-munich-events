# AAIF Community Munich

Slides and links from the talks at **AAIF Community Munich** events, collected in one place for attendees.

## About the Agentic AI Foundation (AAIF)

The [Agentic AI Foundation](https://aaif.io/about) is a neutral, open foundation under the **Linux Foundation**. It hosts open protocols and open source projects for agentic AI, and it works on shared standards in a transparent, collaborative way. Its projects include:

- **Model Context Protocol (MCP)**
- **goose**
- **AGENTS.md**
- **Agent2Agent (A2A)**
- **agentgateway**

Learn more: [About](https://aaif.io/about) · [Members](https://aaif.io/members) · [GitHub](https://github.com/aaif)

## Stay connected

- 📅 **Meetups on Luma:** [luma.com/aaif-munich](https://luma.com/aaif-munich). Follow the calendar to hear about upcoming events. Past events are listed [here](https://luma.com/aaif-munich?period=past).
- 💬 **Slack:** join the [AAIF Community Slack](https://aaif-community.slack.com/) and the **`#munchen`** channel. That's where we announce meetups, share slides, and talk with the speakers.

## Events

| Event | Date | Talks |
|-------|------|-------|
| [#30](./events/2026-11-17-munich-30/) | 17 Nov 2026 | What makes a good task for a coding agent? (Evgenii Zakharchenko) · Agents Need Access: ShellWatch (Martin Riedel) |

## Repository layout

```
events/
  YYYY-MM-DD-munich-NN/          # one folder per meetup
    README.md                    # date, host, event link, list of talks
    talks/
      01-short-slug/
        README.md                # summary, speaker, links, speaker's ask
        slides.pdf               # if the speaker shared slides
templates/                       # copy these for a new event or talk
```

## Adding a new event

1. Copy `templates/event/README.md` to `events/YYYY-MM-DD-munich-NN/README.md`.
2. Create a folder for each talk under `talks/NN-short-slug/` and start from `templates/talk/README.md`.
3. Name slide files `slides.pdf`. If a speaker only shares links (repo, blog, video), the talk README links to them and nothing gets copied into this repo.
4. Add a row to the **Events** table above.
