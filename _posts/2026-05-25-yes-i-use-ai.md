---
layout: post
title: "Yes, I Use AI to Write This Blog. No, I'm Not Sorry."
date: 2026-05-25 10:00:00 +0000
tags: [meta, ai, writing]
excerpt: "A transparent post about using AI as a writing tool — what it does, what it can't do, and why I think it's a perfectly good call."
---

Before you read another post on this blog, there's something you should know: I use AI to help me write. I know, shocking. A tech blogger using technology. Give me a moment to recover from the irony.

To be clear, AI here is not the author. It's a tool, the same way an IDE, a linter, or a profiler is a tool. Nobody writes a blog post about using syntax highlighting, but the moment you mention AI, suddenly you need a disclaimer. So here's mine.

I could have said nothing. Plenty of people don't. But I'd rather be upfront about how this blog gets made and let you judge the content by what it actually says. If that works for you, great. If not, I respect that too, and I promise the exit button works without AI assistance.

## What AI Does (and What It Doesn't)

English is my second language. I write well in it, I think in it, but mistakes happen in any language, and a native speaker would catch things I occasionally miss. AI handles that layer of polish.

The bigger value is format adaptation. Most of my professional writing is technical documentation, architecture artifacts, and internal articles. Those have a very different structure from a blog post. A design doc that lands perfectly in a team review would put a blog reader to sleep by paragraph three. AI helps me take the same ideas and reshape them for a format where readability matters as much as precision. Think of it as having an editor who's always available and never tired of saying "this paragraph is too dense, break it up."

But here's the part that matters most. AI didn't rewrite X-Ray's console driver for Windows while sitting in a closed airport at 3 AM. It didn't debug a race condition smeared across 30 instances of a service, all sinking into one GCP log in production. It never ran an OLAP benchmark on terabytes of data while juggling real business constraints that made the "theoretically optimal" solution completely useless.

Every post on this blog starts with something I've actually done, built, or debugged. The opinions come from projects. The recommendations come from trade-offs I've weighed in real systems. The mistakes I describe are mistakes I've made, not hypothetical scenarios generated to illustrate a point. AI has no experience. It has pattern-matched text. It can help me say what I mean more clearly, but it cannot know what I mean in the first place. That part is entirely mine.

## Why This Is a Good Call

Engineers don't type code into a plain text file and compile it by hand anymore. We use IDEs with autocompletion, linters that catch bugs before we do, and formatters that settle style arguments nobody wants to have. Nobody questions whether that makes the code "less yours." The tool didn't design the system. You did.

And honestly, I'd rather publish ten posts that share real production lessons with AI-assisted formatting than two posts that are "pure" but never get written because I ran out of weekend.

## The Bottom Line

If you find something wrong in a post, call it out. If an architecture recommendation doesn't hold up, challenge it. If the code doesn't run, tell me. That's the bar I want to be held to. Not "did you type every word yourself" but "is this actually useful."

The toolchain is my business. The content is yours to judge.
