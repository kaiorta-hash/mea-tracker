# MEA-CartPole Design Tracker

A static page. `index.html` is the app, `data.json` is the shared data.

## Put it on GitHub Pages
1. Create a repository (for example `mea-tracker`) and upload `index.html` and `data.json` to the root of the `main` branch.
2. Repository Settings, Pages, Source: "Deploy from a branch", Branch: `main`, folder `/ (root)`.
3. The site appears at `https://<your-username>.github.io/mea-tracker/` after a minute or two.
4. Add teammates under Settings, Collaborators.

## Who can do what
- Anyone with the link can open the page and edit. Edits stay on that person's screen until saved.
- To save for everyone, a collaborator clicks "Connect GitHub to save" and pastes a fine-grained personal access token (Contents: Read and write, limited to this repository). The token is stored only in that browser.
- Saving commits `data.json`. If two people save, the page merges at the item level (the last editor of the same item wins).
- Everyone sees the latest data on page load and when they return to the tab.
- Assignments: under the cycle diagram, "Edit assignments" lets you rename an assignment, change its people, and add or remove the steps it works on. These save the same way as items.

## Notes
- A public repository makes the tracker public. Pages on a private repository needs a paid GitHub plan (check the current GitHub docs).
- Do not put a token inside `index.html` or `data.json`. Anyone who can open the page could read it.
- "Download data.json" in the connect panel exports your edits if you cannot save.
