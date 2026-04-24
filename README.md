# CS320 TUI project site

Static project documentation page: open `index.html` locally, or use `npm start` to serve on [http://localhost:3000](http://localhost:3000).

## Deploy to the web (GitHub Pages)

1. **Create a new repository** on [GitHub](https://github.com/new) (empty, no README required).

2. **Push this project** (from this folder in a terminal):
   ```bash
   git remote add origin https://github.com/<YOUR_USER>/<YOUR_REPO>.git
   git push -u origin main
   ```
   If you have not made the first commit yet, run:
   ```bash
   git add -A
   git commit -m "Add project site"
   git push -u origin main
   ```

3. **Turn on GitHub Pages**
   - Open the repo on GitHub → **Settings** → **Pages** (left sidebar under “Code and automation”).
   - Under **Build and deployment** → **Source**, choose **GitHub Actions** (not “Deploy from a branch”).

4. The **Deploy to GitHub Pages** workflow runs on every push to `main`. When it finishes, the site is at:
   - **Project site:** `https://<your-username>.github.io/<repo-name>/`

5. The first run may need **Settings → Actions → General** set to “Allow all actions and reusable workflows” if Actions were disabled for the repo.
