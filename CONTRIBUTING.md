# Contributing Guide

This is your step-by-step guide to picking an issue, building it, and getting it merged. Follow it exactly the first time — after that it'll feel automatic.

## 1. Pick an issue

Go to the repo's **Issues** tab on GitHub. Find one that's:

- **Open** (not closed)
- **Unassigned** (no one's name is on it yet)

Comment `"I'll take this"` on the issue, and wait for it to be assigned to you before starting.

## 2. Clone the repo (first time only)

```bash
git clone https://github.com/Hey-Techys/CSS-TRACK.git
cd CSS-TRACK
```

## 3. Create your branch

Always branch from the latest `main`:

```bash
git checkout main
git pull origin main
git checkout -b issue-<number>-<short-description>
```

Example: if you're doing Block 3 issue #4, "Style a profile card using the box model":

```bash
git checkout -b issue-04-box-model-profile-card
```

## 4. Create your challenge folder

Inside the issue's folder, create a folder with your name and build your work inside it as `index.html` + `style.css`.

```
challenges/block-3/04-box-model-profile-card/your-name/index.html
challenges/block-3/04-box-model-profile-card/your-name/style.css
```

**Naming convention:** lowercase, hyphens, no spaces. This keeps folders sorted and searchable, and guarantees your work never collides with anyone else's folder.

## 5. Build your challenge

Write your HTML in `index.html` and **all** of your CSS in `style.css`, linked from the `<head>`. Check the issue description for exactly what's required, and look at the issue's `example/` folder if you get stuck.

Before opening a PR, check your own work:

- [ ] Is all styling in `style.css` (no inline `style=""` attributes or `<style>` tags)?
- [ ] Is the HTML still semantic, with labels on every form input?
- [ ] Can you see where keyboard focus is on every link and button? (Never use `outline: none`.)
- [ ] If it's a Block 4 issue — does it work at 320px wide with no horizontal scroll? Try your browser's device toolbar.

## 6. Add yourself to the hub page (optional but encouraged)

Open the root `index.html` and add one line linking to your new challenge, under the correct block section. This builds the public hub page over the course of the month.

## 7. Commit and push

```bash
git add .
git commit -m "Complete Block 3 issue #4: box model profile card"
git push origin issue-04-box-model-profile-card
```

## 8. Open a Pull Request

On GitHub, open a PR from your branch into `main`. In the PR description:

- Link the issue (`Addresses #4`)
- Add a one-line summary of what you built
- Add a screenshot (for Block 4, one mobile and one desktop)

## 9. Respond to review

A maintainer will review your PR. You might get feedback — that's normal and part of learning. Push additional commits to the same branch to address it; the PR updates automatically.

## 10. Merged!

Once merged, your points are logged in the scoring tracker. Time to pick your next issue.

---

**Questions?** Ask in the Hey_Techys Slack — don't sit stuck on git commands for more than a few minutes before asking.
