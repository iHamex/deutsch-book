# AGENTS.md - Repo-Wide Rules for AI Agents (READ FIRST, ALWAYS)

This repository is the **personal property of Hamed Okhovvat**. AI agents and
tools operate here only as assistants. The rules below are HARD, PERMANENT,
NON-NEGOTIABLE restrictions. They were added after a violation damaged this
repository. Do not "improve", "soften", or "rewrite" these rules.

---

## HARD BAN - NEVER add AI credit, attribution, or branding to anything

NEVER add ANY of the following to any commit message, file, comment, or output
in this repository:

- `🤖 Generated with <any tool name>`
- `Co-Authored-By: ...` (any tool, any address)
- `Generated with ...`
- `Authored by <AI>` / `Written by <AI>` / signatures, logos, or emoji credits
- Any line that could register a second GitHub account as a contributor

**Why:** one such line (`Co-Authored-By: Codebuff <noreply@codebuff.com>`)
registered an unwanted third party as a contributor to the owner's personal
repository. It will NEVER happen again.

**Commit rules:**

1. Commit messages are PLAIN TEXT only: a short imperative summary line,
   optionally followed by a body explaining the change. Nothing else.
2. NEVER append credit, signature, emoji, or attribution lines to a commit.
3. NEVER change the git author or committer identity (git config) - the
   repository commits under the owner's own identity, and nothing else.
4. NEVER register any account other than the owner's as author or co-author.
5. NEVER commit, push, deploy, or rewrite history unless the owner explicitly
   asked for it.
6. Before finishing: `git log -1 --format=%B` must contain NO line matching
   "Generated", "Co-Authored", "codebuff", "<tool>", or emoji credits.

**If you are about to write one of those lines: STOP. It is forbidden.**

---

## HARD RULE - NEVER shrink content on your own initiative

NEVER reduce the depth, breadth, or example count of any lesson because it feels
long enough to you. Thin files do not teach. Every lesson must stand alone as a
complete learning unit: full tables, abundant examples with English translations,
frames to memorize, and a cheat sheet. The owner - and ONLY the owner - decides
what stays, what goes, and when a file is complete. If a file looks thin, EXPAND
it. Never the reverse.

---

Other conventions for editing content live in `.RULES-FORMATTING.md` (repo
root). Read it before creating or editing any markdown file. The visual
element standard (which Material element carries which content) lives in
`.RULES-VISUAL.md` - read it before writing any lesson content.
