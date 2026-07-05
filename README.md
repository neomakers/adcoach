# adcoach

`adcoach` is a Codex skill for strict copywriting rewrite coaching.

It helps with:

- rewriting ad copy, headlines, slogans, and selling points
- improving conversion-focused copy
- giving strict coach-style critique and 0-3 scoring
- producing alternate versions for social posts, short-video hooks, product copy, and landing pages

## Install

Copy this folder to:

```text
C:\Users\ufo00_sq4c08f\.codex\skills\adcoach
```

Or clone the repository and place it under your Codex skills directory as `adcoach`.

## Usage

In Codex, invoke:

```text
$adcoach 帮我改写：提升工作效率的方法
```

The default output includes diagnosis, selected techniques, rewrite versions, strict critique, 0-3 scoring, and a next training drill.

## Publish To GitHub

This local folder is already a Git repository. To publish it as a private GitHub repository:

```powershell
gh auth login
gh repo create adcoach --private --source . --remote origin --push
```

To publish it as a public repository instead, replace `--private` with `--public`.

## Structure

- `SKILL.md`: skill trigger, workflow, output contract, and guardrails
- `agents/openai.yaml`: display metadata
- `references/technique-index.md`: 77 copywriting techniques
- `references/technique-families.md`: technique categories
- `references/rewrite-playbook.md`: rewrite and scoring workflow
