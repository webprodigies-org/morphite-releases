---
id: big-repository-import
title: "Big repositories, without the flood"
date: 2026-10-08
version: 0.4.0
tags: [improved]
summary: "Choose which existing issues come onto your board: all of them, only labelled ones, or none."
cover: big-repository-import/cover.webp
---

When a repository has more than 300 open issues, Morphite asks before bringing them onto your board.

## Choose what comes in

![The choice to sync all existing issues, only labelled issues, or cancel](big-repository-import/choices.webp)

- **Sync all** imports every open issue, newest first.
- **Only labelled** imports issues carrying any of the labels you choose.
- **Cancel** leaves existing issues where they are.

Sync stays on either way: new and changed issues can still arrive.

## Pick labels from the repository

![The repository label picker](big-repository-import/labels.webp)

Pick several labels from GitHub’s own list. A repository shared by projects can route issues by each project’s labels. You can also remove intake labels that no longer exist on GitHub.

## Follow the import

![An import’s progress in Issue sync](big-repository-import/progress.webp)

Imports run in the background with progress in **Issue sync**, and can resume rather than start over. Large boards open and scroll smoothly.
