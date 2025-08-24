# Multiplayer Golf Scorecard

This repository hosts the **Multiplayer Golf Scorecard** as a static site via GitHub Pages.

## How to deploy on GitHub Pages

1. Create a new public repository on your GitHub account (e.g., `multiplayer-golf-scorecard`).
2. Place `index.html` in the **root** of the repository.
3. Commit and push.

   ```bash
   git add index.html README.md
   git commit -m "Initial commit with scorecard"
   git branch -M main
   git push -u origin main
   ```

4. On GitHub: go to **Settings → Pages** → set Source = `Deploy from a branch`, select `main` branch, folder `/ (root)`.

5. After saving, your site will be live at:

   ```
   https://<your-username>.github.io/<repo-name>/
   ```

## Firebase setup

- In Firebase Console → Authentication → Enable **Anonymous Sign-in**
- Add `github.io` (or `<your-username>.github.io`) to **Authorized domains**
- Enable Firestore Database with test rules (or copy the rules provided earlier).

