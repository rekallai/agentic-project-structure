# DRAFT: Rekall Agentic Project Structure (RAPS)

An opinionated layout for projects that mix human signal with AI-generated output.

## Directory Structure

| Path          | Purpose                                              |
|---------------|------------------------------------------------------|
| `specs/`      | High-signal mostly human input to the project        |
| `sources/`    | Additional context, information and artifacts for the project |
| `sources/slack/<channel>/` | Append-only feed/dump of Slack channel |
| `sources/linear/<board>/` | Append-only feed/dump of Linear tickets |
| `sources/google-docs/<file>.md` | Markdown representation of Google Docs |
| `sources/google-meets/<meeting-date>.md` | Transcripts from relevant Google Meets |
| `sources/figma/<project>.md` | Links to figma? |
| `sources/claude-design/marketing-website` | Example export of a design project |
| `plans/`      | AI-generated, dated, scoped planning artifacts       |
| `plans/marketing-website/implementation-plan.md` | Full plan in md, TLDR at the top |
| `plans/marketing-website/implementation-plan.html` | Visualized plan in rich HTML |
| `prompts/skills/`| Reusable agent capabilities                          |
| `prompts/policies/`   | Project gates and conventions agents must read.       |
| `prompts/jobs/`       | Schedulable AI prompts with triggers                 |
| `code/`       | Linked code repositories (submodules / refs)         |

