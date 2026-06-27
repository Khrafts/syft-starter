# syft-starter — your workspace for *Ship Your First Thing*

This is the empty workspace you build in. It is deliberately small: a starter page, one read-only example app, and the file hygiene the course sets up in Module 2. The course lessons themselves live somewhere else (see below). This repo is where you *do the work*.

## Start here — make your own copy

You can't save work into a repo you don't own, and an AI coding agent saves your work by pushing it to a repo. So the first move is to make your own copy of this one.

1. **Use this template.** At the top of this page, click the green **`Use this template`** button → **`Create a new repository`**. Pick any name you like (`my-first-thing` works). This creates a copy under *your* GitHub account that you own outright.
2. **Open a Codespace on your copy.** On your new repository, click **`Code`** → the **`Codespaces`** tab → **`Create codespace on main`**. It boots in about a minute with your editor, terminal, and tools ready.
3. **Follow the course from there.** Module 0 Lesson 5 walks the first-run in detail; Modules 2 and 3 are where this workspace fills up.

> **Why a copy, not this repo directly?** Your copy is yours. Your AI agent can push to it freely, and nothing you do touches anyone else's work. Working directly in a repo you don't own would mean you couldn't save what you make.

## Where the course lives

The lessons — the words you read and work through — are at **[github.com/Khrafts/ship-your-first-thing](https://github.com/Khrafts/ship-your-first-thing)** (and, once it's live, at **shipyourfirstthing.com**). Read the course there; build here. You don't need a copy of the course repo to take the course — you need a copy of *this* one.

## What's in here

- **`index.html`** — a tiny starter page with a name and a tagline. Module 3 ("the loop") builds it up one step at a time with your AI agent. It starts almost empty on purpose.
- **`sample-app/`** — a small, real-shaped example app you *read* in Module 3.5 to learn the file shapes. It is reference only: **do not run `npm install` against it.** Its own README repeats that warning.
- **`.gitignore`, `.claudeignore`, `.geminiignore`, `.claude/settings.json`** — the file hygiene from Module 2 Lesson 6. They keep secrets (like a `.env` file) and clutter (like `node_modules/`) out of git and out of your AI agent's reach. Module 2 explains each one.
- **`.devcontainer/`** — tells Codespaces how to set up your workspace: Node, and the Live Preview extension you use to see `index.html` in a browser tab. You don't edit this; it just means your Codespace is ready the moment it boots.

## Licensing

Code in this repository is under the MIT license (see `LICENSE`). The `sample-app/` example mirrors course material from *Ship Your First Thing*; see that project's `LICENSING.md` for terms.
