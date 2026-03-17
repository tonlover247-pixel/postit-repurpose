# PostIT Repurpose Skill

> One piece of content. Every platform. Paste a URL, transcript, or raw idea — get TikTok, X, and LinkedIn content ready to schedule.

The most powerful skill in the PostIT ecosystem. Give it anything — a YouTube video, a blog post, a podcast transcript, an existing tweet, or even a raw idea — and it generates platform-native content for TikTok, X, and LinkedIn. All voice-matched. All algorithm-aware. All scheduled via Postiz.

**You never start from scratch again.**

---

## What It Does

- **Any input** — YouTube URL, blog URL, pasted transcript, existing post, or raw idea
- **Every platform** — TikTok script + slides, X thread + standalone tweets + reply hooks, LinkedIn post/carousel/short
- **Voice-matched** — everything sounds like you, adapted for each platform's tone
- **Algorithm rules baked in** — TikTok pacing, X thread mechanics, LinkedIn formatting — all handled
- **Flexible publishing** — walk through each platform, or say "post all" for one-shot scheduling

---

## Inputs Accepted

| Input Type | Example |
|-----------|---------|
| YouTube URL | `https://youtube.com/watch?v=...` |
| Blog / Article URL | `https://yourblog.com/post/...` |
| Pasted transcript | Podcast, video, or meeting notes |
| Existing post | Paste a tweet, thread, or LinkedIn post |
| Raw idea | "I want to talk about why X is broken" |

---

## Output Per Platform

### TikTok
- Full script (hook → open loop → body with pacing resets → CTA)
- Caption + 5 niche hashtags
- Suggested audio vibe + reason
- 6 slide descriptions (or AI-generated images via fal.ai)

### X / Twitter
- 7-tweet thread (hook → open loop → body → bookmark/RT CTA)
- 3 standalone viral tweets
- 3 reply hooks to steal impressions
- Optimal posting window

### LinkedIn
- Asks format: long-form, carousel, or short post
- Full post with hook-first formatting, line breaks, comment CTA
- First comment with link (LinkedIn algorithm rule)
- 3-5 niche hashtags

---

## Requirements

- [Claude Code](https://claude.ai/code) installed
- [Postiz](https://postiz.com) account with platforms connected (free tier works)
- [Groq](https://console.groq.com) API key (free)
- [fal.ai](https://fal.ai) key (optional — only for AI TikTok slide images)

---

## Install

```bash
/skill install github:tonlover247-pixel/postit-repurpose
```

Then give it anything:

```
"Repurpose this: https://youtube.com/watch?v=..."
"Turn this transcript into content: [paste]"
"I want to post about why most founders underprice their SaaS"
```

---

## Publishing Modes

**Per-platform review (default):**
Claude shows TikTok content → you approve/skip → shows X → you approve/skip → shows LinkedIn → you approve/skip → schedules confirmed platforms.

**Post all (fast mode):**
Say "post all" — Claude generates everything, shows a combined preview, one confirmation, schedules everything.

---

## How It Compares

| Workflow | Old way | PostIT Repurpose |
|---------|---------|-----------------|
| Blog post | Write 3 separate posts per platform manually | Paste URL → done |
| YouTube video | Manually extract clips and rewrite | Paste URL → done |
| Podcast | Transcribe → rewrite for each platform | Paste transcript → done |
| Raw idea | Open 3 different tools | Say the idea → done |

---

## Privacy & Security

- API keys stored locally in `config/config.json` (gitignored)
- Never sent anywhere except Postiz, Groq, and fal.ai (if enabled)
- Never commit your `config/` folder

---

## Part of the PostIT Skill Ecosystem

| Skill | Platform | Status |
|-------|----------|--------|
| [postit-tiktok](https://github.com/tonlover247-pixel/postit-tiktok) | TikTok | ✅ Live |
| [postit-x](https://github.com/tonlover247-pixel/postit-x) | X / Twitter | ✅ Live |
| [postit-linkedin](https://github.com/tonlover247-pixel/postit-linkedin) | LinkedIn | ✅ Live |
| postit-repurpose | All platforms | ✅ Live |

---

## License

MIT-0 — do whatever you want with it.

---

Built with Claude Code. Part of the [PostIT](https://github.com/tonlover247-pixel) project ecosystem.
