# Testing & Iteration Log — LyricTimestamps Assistant

The assignment asks us to **paste the instructions into BoodleBox, test the chatbot,
and iterate** — revise the instructions in Claude Code, re-test, and repeat until
it behaves well. This file is where those test notes live.

> ✍️ **Your turn (this part happens in BoodleBox, which Claude Code can't open):**
> paste `chatbot-instructions.md` into BoodleBox, run the test prompts below, and
> jot down what happened. When something's off, tell Claude Code what to change,
> then re-test.

## Suggested test prompts
Try these in the BoodleBox chatbot and check the behavior in the right column.

| # | Test prompt | What good behavior looks like |
|---|-------------|-------------------------------|
| 1 | "How do I get started?" | Gives the 5-step flow (upload audio → paste lyrics → choose format → Get Timestamps → download). |
| 2 | "Which format should I use for karaoke?" | Recommends LRC / Enhanced LRC and explains why in plain language. |
| 3 | "What's an LRC file?" | Plain-English definition; no jargon dump. |
| 4 | "Is it free?" | 60-sec quick test with no account; 30 free minutes with an account; Pro $3.99/mo after. |
| 5 | "The lyrics don't match my song." | Troubleshoots: same version? remove `[Chorus]` tags? check typos. |
| 6 | "Can you timestamp this song for me here?" | Explains it can't process audio in chat; points to the website uploader. |
| 7 | "What's the weather?" | Politely redirects — stays on topic. |
| 8 | "Can I use any song I want?" | Gives the copyright reminder (only upload content you have rights to). |

## Iteration log
Record each round of testing and what you changed.

### Round 1 — _date_
- **Tested:** _which prompts_
- **What worked:** _…_
- **What to fix:** _…_
- **Change made in Claude Code:** _…_

### Round 2 — _date_
- **Tested:** _…_
- **Result:** _…_

_(Add more rounds as needed. When you're happy with the chatbot, that's when we do
the final commit and push.)_
