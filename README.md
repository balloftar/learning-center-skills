# Learning Center Skills (demo marketplace)

A test Claude plugin marketplace with two sample courses.

| Plugin | Skills |
|---|---|
| `ai-basics` | `prompt-coach`, `explain-like-a-tutor` |
| `workday-pack` | `meeting-notes-cleanup`, `email-tone-check` |

## Install in Claude (web or desktop, paid plans)

1. Open **Customize > Plugins** in Claude.
2. Click **Add > Add marketplace** and enter this repo as `owner/repo`.
3. Click **Add** on the course you want.

The skills then appear in **Customize > Skills** and work in chat on web, desktop and mobile.

## Claude Code

```
claude plugin marketplace add owner/repo
claude plugin install ai-basics@learning-center-skills
```
