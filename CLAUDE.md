## Skill routing

When the user's request matches an available skill, invoke it via the Skill tool. When in doubt, invoke the skill.

Key routing rules:
- Product ideas/brainstorming -> invoke /office-hours
- Strategy/scope -> invoke /plan-ceo-review
- Architecture -> invoke /plan-eng-review
- Design system/plan review -> invoke /design-consultation or /plan-design-review
- Full review pipeline -> invoke /autoplan
- Bugs/errors -> invoke /investigate
- QA/testing site behavior -> invoke /qa or /qa-only
- Code review/diff check -> invoke /review
- Visual polish -> invoke /design-review
- Ship/deploy/PR -> invoke /ship or /land-and-deploy
- Save progress -> invoke /context-save
- Resume context -> invoke /context-restore
- Author a backlog-ready spec/issue -> invoke /spec

## Team Brain and Company Log

Every agent that builds or edits code in this repo follows the Prom13us Team
Brain.

1. **Source of truth.** The Notion Team Brain (the shared team brain plus the
   weekly company log) is the source of truth for project context, rules, open
   loops and the company log. Before starting any work in this repo, read the
   Team Brain: this project's page (owner, status, open loops, decisions,
   links, next step), the rules page, and the current week's company log.
   Notion link:
   <https://app.notion.com/p/DRAFT-Team-brain-structure-for-Yohan-review-407d211d9d6e81b0a5c6c09f18c768ed?source=copy_link>
2. **When to write back.** After you complete a task or make a change, the
   agent responsible for that task appends one entry to the current week's
   company log. That agent is you if you did the work. Read-only work does not
   need an entry unless Yohan says otherwise. Also update the project page's
   open loops and decisions if they changed.
3. **Entry format.** Each entry has: date and time in Manila time
   (Asia/Manila, UTC+8), agent name, what changed, a link (PR, commit, file or
   Notion page), and why or the evidence.
4. **Append only.** Never edit or delete existing entries. Corrections go in
   as a new entry. Add new entries at the bottom of the current week's page.
5. **Who creates log pages.** Only Murphy creates the weekly log pages, on a
   routine at 12:00 AM every Monday Manila time. You and every other agent
   never create log pages. If the current week's page doesn't exist yet, do
   not create one: tell Murphy or Yohan, and keep a note to log the entry once
   it exists.
6. **Everyone has access.** Every agent can read the Team Brain and append to
   the log, including agents that are overloaded, stuck or having issues. If
   you can't write the entry, ask Murphy or Salmon to append it for you,
   marked `logged on behalf of <agent>`.
7. **Proof you read it.** When you report a finished task or change, open by
   naming two or three specific points from the Team Brain (the project owner,
   an open loop, a recent decision or log entry) to show you read it first.
8. **Do not publish or share.** Don't share the Notion Team Brain or the log
   outside the company, and don't send anything externally from this work.
