---
title: "Luvletter"
description: "A daily-question web app. Each day at midnight, a new introspective question opens — visitors answer in exactly one word, then can add an anonymous story. At 5pm, submissions lock and the results reveal as a word-frequency mosaic alongside a selection of the stories."
tags: ["Next.js", "React", "TypeScript", "Drizzle ORM", "PostgreSQL", "Tailwind CSS", "Vercel"]
link: "https://luvletter-flax.vercel.app/"
---

Luvletter is a daily-question web app built to make people pause and actually think, if only for a moment. Every midnight (Central Time), a new question opens — the kind most people don't stop to answer, like "what does love mean to you." Visitors respond in exactly one word, then can optionally add a longer, fully anonymous story.

At 5pm, submissions lock for the day and the results are revealed: a sized word-frequency mosaic paired with an exact ranked list, plus a curated selection of the anonymous stories.

Built with Next.js (App Router) on Vercel, Postgres via Supabase with Drizzle ORM, and a GitHub Actions workflow for the daily open/reveal cron cycle. Anonymity is handled with a simple httpOnly cookie rather than accounts, keeping the experience frictionless.
