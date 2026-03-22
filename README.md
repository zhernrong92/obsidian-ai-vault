# Obsidian Work Vault Starter

A ready-to-use Obsidian vault for software developers, designed to work with **Claude Code** as your AI assistant.

## Setup

1. Clone this repo (or download as zip)
2. Open Obsidian → **Open folder as vault** → select this folder
3. Install community plugins:
   - Go to **Settings** → **Community plugins** → **Turn on community plugins**
   - Install and enable **Templater**
   - Install and enable **Dataview**
4. Configure Templater:
   - **Settings** → **Templater** → Set **Template folder location** to `Templates`
5. Open `Home.md` as your starting page

## Folder Structure

```
├── Home.md              ← Dashboard with Dataview queries
├── Daily/               ← Daily notes (one per day)
├── Meetings/            ← Meeting notes
├── People/              ← People profiles & 1:1 logs
├── Projects/            ← Project docs
├── Inbox/               ← Quick captures, ideas, explore lists
├── Resources/           ← Reference material
└── Templates/           ← Note templates (used by Templater)
```

## Templates Included

| Template | Use For |
|----------|---------|
| Daily Note | Start-of-day task list, notes, blockers |
| Meeting Note | Agenda, notes, action items, decisions |
| Project | Project overview, goals, links, open questions |
| Person | Role, contact info, notes, 1:1 log |
| Idea | Quick capture for raw ideas |

## Slash Commands

Type `/` in Claude Code to use these shortcuts:

| Command | What it does |
|---------|-------------|
| `/meeting` | Create a meeting note — asks for name, attendees |
| `/daily` | Create or review today's daily note |
| `/idea` | Quick capture an idea to Inbox |
| `/add-explore` | Append to your AI Tech to Explore list |
| `/person` | Create a new person page |
| `/project` | Create a new project page |
| `/review` | Scan vault for overdue/upcoming items and summarise |

## Using with Claude Code

Open a terminal in your vault directory and start Claude Code. Just talk naturally:

| You say | Claude does |
|---------|------------|
| "Had a standup, discussed X with Alice" | Creates a meeting note with details, links to Alice |
| "New project called DataPipeline using Kafka" | Creates a project page in Projects/ |
| "Met Bob, he's a backend engineer" | Creates a person page in People/ |
| "Add MCP servers to my AI explore list" | Appends to your explore list |
| "I have an idea about automating deploys" | Creates an idea note in Inbox/ |
| "What did I discuss with Alice last week?" | Searches your vault and summarizes |

## Tips

- **Use `[[backlinks]]`** — linking `[[Alice]]` in a meeting note means Alice's page shows all meetings she appeared in
- **Search with `Ctrl+Shift+F`** — full-text search across all notes
- **Don't over-organize** — flat folders + links + tags beats deep hierarchies
- **Weekly review** — spend 15 min on Fridays scanning the week's daily notes
- **Zero friction** — dump ideas in Inbox, promote to Projects later when they mature
