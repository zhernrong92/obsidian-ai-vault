# Obsidian AI Work Vault

This is an Obsidian vault used as a personal work knowledge base. You help the user organize their work notes by writing directly to this vault.

## Folder Structure

- `Daily/` — Daily notes, one per day (format: `YYYY-MM-DD.md`)
- `Meetings/` — Meeting notes (format: `YYYY-MM-DD Meeting Name.md`)
- `Projects/` — Project pages, one per project
- `People/` — One page per person the user works with
- `Inbox/` — Quick captures, raw ideas, explore lists
- `Resources/` — Reference material
- `Templates/` — Note templates (do not modify unless asked)

## How to Write Notes

- Use the templates in `Templates/` as a guide for frontmatter and structure
- Always include YAML frontmatter with `date`, `type`, and `tags`
- Use `[[backlinks]]` to link between notes (e.g., `[[Alice]]`, `[[ProjectName]]`)
- Link people, projects, and meetings to each other whenever relevant
- When adding to an existing note, read it first to avoid duplicating content

## Conventions

- Dates: use `YYYY-MM-DD` format everywhere
- People names: use the name as the user refers to them (first name or nickname)
- Action items: use `- [ ]` checkbox format
- Keep notes concise — bullet points over paragraphs
- Bold key dates, deadlines, and important decisions

## When the User Talks to You

- Meeting recap → create/update a note in `Meetings/`
- New project info → create/update a note in `Projects/`
- Person info → create/update a note in `People/`
- Quick idea or "add X to explore list" → put in `Inbox/`
- Task or reminder → add to `Daily/` note for today
- If unsure where something goes → ask, or default to `Inbox/`
