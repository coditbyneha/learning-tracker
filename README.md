# Learning Tracker

My 8-week developer learning plan with a live progress page.

- **The plan:** [PLAN.md](PLAN.md). This is the only file I edit.
- **The website:** `index.html` reads `PLAN.md` and shows my progress, the current week and whether I am on track.

## One-time setup

1. Create a new **public** repository named `learning-tracker`.
2. Click **Add file → Upload files**. Upload `index.html`, `PLAN.md` and `README.md`, then click **Commit changes**.
3. Click **Add file → Create new file**. Name it `.nojekyll`, leave it empty, and click **Commit changes**. This tells GitHub Pages to publish `PLAN.md` exactly as it is.
4. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, pick **main** and **/ (root)**, then click **Save**.
5. Wait 1–2 minutes. The site is live at `https://<your-username>.github.io/learning-tracker/`.

## Daily use

1. Open the website and click **Tick a topic**. It opens `PLAN.md` in the GitHub editor.
2. Change `[ ]` to `[x]` for each topic I can explain out loud without notes.
3. Click **Commit changes**. The website updates by itself in about a minute.

Each tick is a commit, so my GitHub profile shows my learning streak.

## Changing the plan

- **Add a topic:** add a new line `- [ ] **Topic:** short note` under the right week.
- **Change dates:** edit the `Start:` and `Goal:` lines at the top of `PLAN.md`. Each `## Week N` section is 7 days from the start date.
- **Other lines:** `Word:`, `Learn:` and `Speak:` lines show up in each week's card.
