# AGENTS.md — bedrock

## What it is

**bedrocks** is a starter repository ("Bedrock starter") for the Salamander jewelry
business group. It currently contains only `LICENSE`, `.gitignore` (WordPress-flavored)
and `README.md`. No application code yet.

## Stack

- Starter stage — no stack chosen yet.

## Structure

```
bedrocks/
├── .gitignore   # WordPress-flavored starter ignore list
├── LICENSE      # GPL-3.0
└── README.md    # Bedrock starter
```

## Build & Run

- Task 1 (`ask.sh`): create a new site from the starter — prompts for the sitename, then runs `docker run --rm -v "$PWD:/app" composer create-project roots/bedrock <sitename>`.

## Conventions

- Workspace-wide rules live in `~/webs/Agents/AGENTS.md`.
- README logo rule applies here (logo file: `bedrock.svg`, first README line).
- Starting/finishing work: read `~/webs/Agents/todo.md` when the trigger matches.
