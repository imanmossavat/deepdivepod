# How to publish a new episode

The site is built by GitHub Pages from this repo. Publishing = adding one file in `_episodes/` plus one cover image. Decap CMS does both from a form.

## Publish with the CMS (normal way)

1. Publish the episode on Spotify first and copy its share link (Spotify: episode, `...`, Share, Copy link), e.g. `https://open.spotify.com/episode/2eFjHhKXc52elOUTkoNFnY`.
2. Go to **https://deepdivepod.eu/admin/** and log in with GitHub.
3. Episodes, **New Episode**. Fill in:
   - **Episode Number**: keep counting from the last one (the next is 32).
   - **Season**: 2 (the default). Season 1 was published through Radio 4 Brainport; from episode 32 you publish yourself.
   - **Title** and **Description** (can be several paragraphs).
   - **Cover Image**: upload a square image (PNG/JPG). It is stored in `assets/episodes/`.
   - **Spotify Link**: paste the normal share link. No iframe or embed code needed.
   - **YouTube Link** (optional): the embed URL, `https://www.youtube.com/embed/<id>`.
   - **Tags**: short lowercase words, e.g. `LLM`, `UvA`. They become clickable filters.
   - **External Links** (optional): label + URL, e.g. guest's LinkedIn.
4. Click **Publish** (top right), then **Publish now**. This commits to `main`.
5. Wait 1 to 2 minutes for GitHub Pages, then check https://deepdivepod.eu/episodes/ (hard refresh if needed).

To edit or delete an episode, open it in the same CMS and use Save or Delete entry.

## Seasons

- Numbering never resets: 32 is the first self-published episode, so it is "Season 2, Episode 1" in your head, but the site shows "Episode 32" with a "Season 2" label.
- Episodes 1 to 31 have no `season` field and are treated as Season 1 (no label).

## Without the CMS (fallback)

Create `_episodes/32.md` (copy `_episodes/30.md` as a model), put the image in `assets/episodes/ep32.png`, then commit and push to `main`:

```yaml
---
layout: episode
css: each-episode-styles.css
episode_number: 32
season: 2
title: "..."
description: |
  ...
cover: /assets/episodes/ep32.png
spotify: https://open.spotify.com/episode/2eFjHhKXc52elOUTkoNFnY
tags:
  - LLM
---
```

Preview locally with `bundle exec jekyll serve`.
