# Using the skills

## Start without integrations

Open a skill's `SKILL.md`, copy its instructions into your assistant, and attach or paste your selected notes. State the reporting date or window. Ask the assistant to use only those sources and mark missing information.

With a file-capable assistant, ask it to read the skill and the specific context files directly. You can download this repository with GitHub's **Code → Download ZIP** option, or clone it with Git.

The YAML header identifies each skill. For manual use, pasting the whole file is fine. Native discovery, folder locations, and tool permissions vary by assistant; this release does not claim verified native installation support.

## Use one private context file

Copy the [shared context template](shared-context.md) into a separate private workspace. Populate current priorities and selected records. Start with one or two sources rather than a full company history.

Use the leadership brief to prepare, meeting follow-through to draft changes, and weekly review to reconcile progress. Review changes before adding them to the private context file.

## Example requests

- “Use leadership-brief with these notes. Prepare me for September 14, 2026. Focus on decisions that affect our current priorities.”
- “Use meeting-follow-through on meeting M1. Compare it with our existing commitments. Draft updates only.”
- “Use weekly-review for September 14–18, 2026, ending at 5 p.m. America/New_York. Distinguish confirmed completion from missing updates.”

## Add connections later

Connecting Slack, Gmail, calendars, or project tools requires separate access and configuration. Scheduled execution requires an automation system. These skills supply reasoning instructions, not those connections or scheduling infrastructure.

Use approved data sources and keep actual company records out of this public repository. Never put credentials in a prompt, example, issue, or pull request. AI provider data handling depends on the product and account settings you choose.
