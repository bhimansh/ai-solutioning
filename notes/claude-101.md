# Claude 101 — Notes

**Course:** Claude Academy | **Completed:** September 26, 2026 | **Track:** CCA-F prep (2 of 7)
**Verification:** https://academy.claude.com/verify/784fdfc319a66f57f49bee51da510bcc

## Why Projects matter
A single chat is ephemeral — context resets, and useful files or instructions have to be re-supplied every time. Projects solve this by giving a workstream a persistent environment: memory, knowledge, and behavior configuration that carry across every conversation inside it, rather than living and dying with one chat.

## Core concepts

### Projects as self-contained workspaces
Each Project has its own memory, chat history, knowledge base, and instructions — effectively a dedicated environment scoped to one piece of work, rather than one long undifferentiated chat history.

*My example:* [Describe a case where you'd want a dedicated workspace — e.g., a learning track like this one, a recurring type of task, or a specific topic you return to often.]

### Project knowledge
Documents uploaded to a Project are available to every chat within it automatically — no re-uploading the same reference material each time you start a new conversation.

*My example:* [What's something you currently re-explain or re-upload every time you start a new chat, that a Project would eliminate?]

### Project instructions
Custom instructions set at the Project level — tone, expertise level, response style — apply to every conversation inside that Project, rather than being repeated per chat.

*My example:* [If you set up a Project today, what instruction would you give it that you currently type out manually each time?]

### Automatic scaling
As a Project's knowledge base approaches context limits, Claude shifts from loading everything into context to *searching* the knowledge base and pulling in only what's relevant — expanding effective capacity up to 10x without losing response quality.

*Why this matters:* This means Projects don't degrade as you add more reference material over time — the retrieval approach is designed to scale with the knowledge base rather than being capped by it.

### Team collaboration (Claude for Work)
Projects can be shared with teammates, so everyone works from the same context, instructions, and accumulated knowledge rather than each person reconstructing it individually.

*Where this could apply:* [A team context where shared, consistent AI context would reduce duplicated effort or inconsistent outputs across people.]

## Open questions / things I want to test next
- [ ] How Project knowledge search behaves differently from having everything directly in context — does retrieval ever miss something I'd expect it to surface?
- [ ] What a well-scoped Project instruction set looks like in practice, versus one that's too vague to change behavior meaningfully.

## How this changes what I'll do differently
Set up a dedicated Project for recurring or ongoing work (like this learning track) instead of starting fresh chats — so knowledge and instructions accumulate instead of resetting each time.