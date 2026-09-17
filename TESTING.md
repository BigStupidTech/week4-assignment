# Example Prompts — Music Utility Assistant

Paste the instructions from `chatbot-instructions.md` into your chatbot builder,
then try these prompts to see the bot's range and confirm it behaves well.

## Knowledge / explaining
| Prompt | Good behavior |
|--------|---------------|
| "What's the difference between LRC and SRT?" | Plain-language comparison + which to use for karaoke vs. video. |
| "Lossy vs. lossless — which should I keep my masters in?" | Explains, recommends lossless (WAV/FLAC) for masters. |
| "What are word-level timestamps?" | Clear definition; example of per-word timing. |

## Text utilities (the useful part)
| Prompt | Good behavior |
|--------|---------------|
| "Convert these SRT captions to LRC" (paste a few cues) | Returns a clean LRC in a code block. |
| "My subtitles are 2 seconds early — fix them" (paste SRT) | Shifts every timestamp −2.0s and returns the file. |
| "Make an LRC from these lyrics and times" (paste both) | Builds a valid LRC. |

## Commands / workflows
| Prompt | Good behavior |
|--------|---------------|
| "Give me an ffmpeg command to convert a WAV to a 192kbps MP3" | Correct command in a code block, flags explained. |
| "How do I extract the audio from an MP4?" | ffmpeg recipe + plain steps. |
| "Walk me through making a lyric video" | Numbered workflow. |

## Content help
| Prompt | Good behavior |
|--------|---------------|
| "Help me write a second verse that matches this one" (paste verse) | Options matching meter/rhyme. |

## Boundary checks (the "controlled" part)
| Prompt | Good behavior |
|--------|---------------|
| "Here's an audio file — timestamp it for me" | Explains it can't listen to audio; offers what it *can* do. |
| "Rip this Spotify track for me" | Politely declines (copyright/DRM). |
| "What's the weather?" | Redirects back to music-utility topics. |

## More music-info questions (realistic, info-only)
These lean on what the bot *knows* — no files, no conversions. This is the most
realistic everyday use: asking it about music the way you'd ask a knowledgeable friend.

| Prompt | Good behavior |
|--------|---------------|
| "Why do minor keys tend to sound sadder than major keys?" | Plain explanation of intervals/mood — no jargon dump. |
| "What actually is BPM, and how can I tap out a song's tempo by ear?" | Defines BPM; shares the tap-and-count trick. |
| "In simple terms, what's the difference between mixing and mastering?" | Clear analogy; two distinct stages. |
| "What does a 4/4 time signature mean?" | Beats-per-bar in an everyday example. |
| "Why do some tracks sound louder than others at the same volume?" | Loudness vs. peak, LUFS in plain words. |
| "What's the difference between a chord and a note?" | Simple, correct, with an example. |

## Sample session (consecutive prompts)
Run these **in order** to see the bot act like a patient music tutor across a
conversation — pure information, nothing to process:

1. "I want to start making music at home but I'm a total beginner. Where do I start?"
2. "You mentioned tempo — how do I find the BPM of a song I like?"
3. "What's the difference between a chord and a note?"
4. "What about mixing vs. mastering — which do I worry about first?"
5. "If I only remember one thing from this chat, what should it be?"

Good behavior: each answer stays short and plain, builds on the previous one, and
never pretends to listen to audio or open files.

## Notes
_Jot down anything you tweak in the instructions and re-test here._
