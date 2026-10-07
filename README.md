# Cogenity AI

A small agent team that finds local businesses with no website (or a broken one), sends them a preview of what a site could look like, and builds the full site for those who reply.

## Agents (`.claude/agents/`)
- **boss**: lead and owner's point of contact. Picks businesses, approves work, handles outreach email.
- **frontend-dev**: builds the preview cards and full concept sites.
- **backend-dev**: server and data work.
- **qa**: fact-checks every claim against the research and tests sites before anything is sent.

## Workflow (preview-first)
research, then boss approval, then preview card and email, then qa fact-check, then send. Full site only after a business replies interested.

Working data (`local-sites/`: research, outreach log, sender config) is kept out of this repo because it contains contact details and the owner's mailing address.
