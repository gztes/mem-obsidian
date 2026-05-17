Claude Code to Obsidian Session Journal
This system automatically converts your AI development and study sessions into structured, deeply detailed, and retrievable Obsidian notes. It preserves formulas, worked examples, error corrections, code snippets, and calculations so you can reference them later without ever re-reading a raw conversation log.

💡 Key Philosophy: Dense > Summarized
Most AI logging tools summarize conversations, losing the exact context. This system prioritizes density over brevity.

Instead of: "User learned about equity dilution."

This system captures: The complete formula, all variables defined, three worked examples with every step of the calculation, and a breakdown of errors made along with their explicit corrections.

🛠️ How It Works
The system organizes your knowledge into two distinct vault architectures depending on the nature of the session:

1. Academic / Coursework Vault
Designed for structured learning, theory, and course modules.

Sessions/ — Chronological session logs containing all theory, drills, and calculations.

<Institution>/[Module_Name]/ — Permanent concept notes organized by subject (e.g., Finance, Marketing, Economics).

AI-Tooling/, Fleeting/, People/, References/ — Supporting folders for tools, quick ideas, network contacts, and external resources.

2. Projects / Development Vault
Designed for active builds, software development, and entrepreneurial ventures.

Auto-Detects Projects: Scans and categorizes based on your active project names (e.g., project_alpha, next_gen_app).

project_[name]/sessions/ — Deep logs of coding sessions for that specific build.

decisions.md — A living log of locked architectural decisions, pivots, and business rationales.

architecture.md — The technical blueprint, stack definition, and system design.

📋 What Gets Captured
For Academic Work
Complete formulas with variable definitions.

Full practice drills and answers with all working steps shown.

"Error vs. Correction" breakdowns to highlight common pitfalls.

Every single calculation step preserved.

For Project & Code Work
Production-ready code snippets and implementation patterns.

Architectural changes and system dependencies.

Technical decisions alongside their explicit business or logical rationale.

Bug fixes, error logs, and the specific resolutions.

Clear, actionable "Next Steps" for your next session.

🔄 Auto-Save at Session End
When you wrap up a session (e.g., using keywords like "done", "thanks", or "wrap up"), the system automatically initiates the archiving workflow:

Detects context (Academic vs. Project) to determine the correct vault destination.

Generates a structured preview of what will be saved.

Prompts for confirmation before writing any data to your local Markdown files.

🚀 Getting Started & Configuration
To use this skill, clone the repository and update your local paths in the configuration file:

JSON
{
  "coursework_vault_path": "C:\\Users\\<Your_User>\\Documents\\Learning_Vault\\",
  "projects_vault_path": "C:\\Users\\<Your_User>\\Documents\\Projects_Vault\\"
}
```</Institution>
