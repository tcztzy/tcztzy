# Publish This As `tcztzy/tcztzy`

GitHub only shows a special profile README when the repository name exactly matches the account name.

For this account, that repository must be:

- `tcztzy/tcztzy`
- public
- with `README.md` at the repository root

## What Is In This Folder

- `README.md`: the profile homepage content
- `assets/header.svg`: the custom banner used by the README

## Suggested Publish Flow

1. Sign in to GitHub in a browser.
2. Create a new public repository named `tcztzy`.
3. Do not initialize it with another `README.md`.
4. Copy the contents of this folder into that repository.
5. Push to `main`.

Example commands after the repository exists:

```bash
cd /Users/tcztzy/GitHub/tcztzy-profile
git init -b main
git add README.md assets/header.svg PROFILE_SETUP.md
git commit -m "Add GitHub profile README"
git remote add origin git@github.com:tcztzy/tcztzy.git
git push -u origin main
```

If HTTPS is preferred:

```bash
git remote add origin https://github.com/tcztzy/tcztzy.git
git push -u origin main
```

## Suggested Pinned Repositories

To make the profile page and the README reinforce each other, pin these six repositories on GitHub:

1. `skills`
2. `swarmx`
3. `yallm`
4. `xcc`
5. `RL4GenomeBench`
6. `cotton2k`

## Small Tweaks You May Want

- Replace `tcztzy@gmail.com` with another public contact if you prefer.
- If you want a more minimal look, remove the toolbelt badges section.
- If you want a stronger job-seeking signal, add one sentence near the top with the exact roles you are targeting.
- If you want a more research-heavy profile, swap one systems project out for `jupymcp` or `zotmcp` in the pinned set.

## Why This Structure

- The top banner makes the page recognizable without depending on external image hosts.
- The intro says who you are and what you build in two short paragraphs.
- The project grid shows range without turning into a wall of badges.
- The rest of the page stays stable even if dynamic stats services break.
