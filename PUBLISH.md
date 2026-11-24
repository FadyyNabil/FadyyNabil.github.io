# Put the portfolio on GitHub Pages

## 1. Review it first

Open `index.html`. Check the bio, skills, project descriptions and email address. These files are ready to upload, but **have not been published**. A published GitHub Pages site is visible on the open internet.

The data-analysis card links directly to the published project repository: https://github.com/FadyyNabil/student-performance-analysis.

## 2. Create a repository

Sign in to the GitHub account `FadyyNabil`.

1. Choose **New repository**.
2. Suggested name: `portfolio`. For a GitHub Free account, choose **Public** to use GitHub Pages.
3. Choose **Create repository**.

The repository name above is a suggestion, not an existing repository.

## 3. Upload the files

1. Extract the ZIP first. Do not upload the ZIP itself.
2. In the repository, choose **uploading an existing file**, or **Add file > Upload files** if the repository already contains files.
3. Upload `index.html`, `styles.css`, `script.js`, `favicon.svg`, `portrait.png`, `README.md` and `PUBLISH.md` from **inside** the extracted folder. Do not nest them inside another folder.
4. Choose **Commit changes**. Use the `main` branch.
5. Add the empty `.nojekyll` file too. If your file picker hides it, choose **Add file > Create new file**, name it `.nojekyll`, enter no content, and commit it. The site is plain static HTML, so it does not need Jekyll processing.

The main file list should show `index.html` directly, alongside `styles.css` and the other files.

## 4. Switch Pages on

1. Open the repository's **Settings**.
2. In the sidebar, choose **Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Set the branch to **main** and folder to **/ (root)**.
5. Choose **Save**.
6. Give GitHub time to deploy, then return to **Settings > Pages** and use **Visit site**. Copy the URL GitHub displays rather than guessing one.

GitHub says changes can take up to 10 minutes to publish. If it is not ready, check the repository's **Actions** tab for deployment errors.

## 5. Check the live site

- Open the actual **Visit site** link on a phone and a computer.
- Check that styling appears, navigation reaches every section, and contact links go where expected.
- Open the menu on a narrow screen; press Escape on a keyboard to close it.
- Confirm the analysis link opens the student-performance-analysis repository.
- Add the displayed site URL to the repository's **About > Website** field and your GitHub profile if desired.

## Later changes

Edit the files and commit the changes to `main`. Pages redeploys from that branch. Keep all project links current.

## If something looks wrong

- **404:** confirm `index.html` is directly in the repository root, `main` contains the files, Pages uses `main` and `/ (root)`, and deployment succeeded.
- **No styling:** keep `styles.css` beside `index.html`; filenames and letter case must match.
- **Old version:** wait for deployment, then refresh or try a private browser window.
- **Email does not open:** the visitor may not have a default email app. The address is displayed so it can be copied manually.

No paid hosting or custom domain is required for this setup. Do not upload passwords, API keys, credentials or private documents to this repository. This static site cannot run an ASP.NET Core server or SQL database.

Official guides checked when preparing these steps:

- https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
