# Week 4 Assignment — LyricTimestamps Chatbot (BoodleBox)

**Course:** Foundations of AI (M.S. in Applied AI)
**Built with:** Claude Code + GitHub, managed entirely through Claude Code's UI.

## What this is
The deliverable for Week #4: **instructions for a chatbot that runs in BoodleBox.**
The chatbot — the **LyricTimestamps Assistant** — is modeled on
[LyricTimestamps.com](https://lyrictimestamps.com) (a.k.a. MusicTimestamps), a free
tool that turns an audio file plus its lyrics into synced, **word-level timestamps**
for karaoke, subtitles, lyric videos, music apps, and language learning.

## Files in this branch
| File | What it is |
|------|------------|
| [`chatbot-instructions.md`](chatbot-instructions.md) | **The main deliverable.** Copy the "INSTRUCTIONS (paste this into BoodleBox)" section into the BoodleBox chatbot builder. |
| [`CLAUDE.md`](CLAUDE.md) | Standing profile Claude Code reads at the start of every session in this folder, so its explanations match how I want to learn. |
| [`TESTING.md`](TESTING.md) | Log of testing the chatbot in BoodleBox and the revisions made. |
| `README.md` | This file. |

## How to build the chatbot in BoodleBox
1. Open `chatbot-instructions.md` and copy the **INSTRUCTIONS** section.
2. In BoodleBox, create a new chatbot and paste it into the instructions field.
3. Name it **LyricTimestamps Assistant**.
4. Test it (see `TESTING.md`), then come back to Claude Code to revise the
   instructions and re-test until it behaves the way you want.

## Branching note
All assignment artifacts live on the **`week4-assignment`** branch, not on `main`
(the assignment requires this). `main` holds only a pointer README.

## How this was made (SDLC in plain terms)
- **Local environment:** a folder on my machine (`week4-assignment`) turned into a
  git repository — a project folder that tracks every change.
- **Remote version control:** a public GitHub repository linked to that local folder,
  so my work is backed up in the cloud and shareable.
- **Branch:** `week4-assignment` — an isolated line of work kept separate from `main`
  so the main branch stays clean.
- Claude Code ran the `git` and GitHub CLI (`gh`) commands behind the scenes; I
  managed everything through Claude Code's interface.
