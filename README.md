# Paramedic Pharmacology Practice Assessment — Accuracy-Checked Build

This is a standalone, mobile-friendly practice assessment for the upcoming pharmacology post-assessment.

## Files

- `index.html` — the complete assessment website. This is the only file GitHub Pages actually needs.
- `README.md` — these setup instructions.
- `AUDIT_NOTES.md` — what was checked, what changed, and known course/test wording issues.

## What is in this build

- 206 curated practice questions
- 135 historical assessment occurrences preserved in a separate archive mode
- all prior captured pharmacology assessment questions represented
- repeated historical questions deduplicated in normal practice, while repetition is used as a priority signal
- October 1 lecture priorities and explicit test cues
- Chapter 15 Paramedic Mastery clinical-reasoning questions
- four multi-part clinical scenarios
- single-select only
- answer choices shuffled at runtime
- try-until-correct behavior
- feedback for every incorrect choice without naming the correct answer
- explanation after every correct answer
- optional Defense Mode
- medication pronunciation buttons where recognized
- Review First-Try Misses at the end of a session

## Source order used for the content audit

1. Mr. Cornett's lectures
2. Course PowerPoints
3. Assigned textbook material
4. Supplementary material, including current Kentucky EMS protocol information when useful

When course wording and outside/current clinical material differ, the assessment identifies the distinction instead of silently merging them. For an exam, the course framing is shown; for clinical practice, follow your current agency protocol and medical direction.

# Put the assessment on GitHub Pages

These steps were rechecked against GitHub's current Pages documentation in October 2026.

## 1. Extract the ZIP first

If you downloaded the ZIP package, extract it on your computer. Do **not** upload the ZIP as the only file in the repository. GitHub Pages needs `index.html` itself at the top level of the publishing folder.

## 2. Create a repository

1. Sign in to GitHub.
2. Create a **New repository**.
3. Give it a name such as `paramedic-pharmacology-review`.
4. If you are using GitHub Free, make the repository **Public** for GitHub Pages.
5. Create the repository.

You do not need Node, Jekyll, npm, a database, or GitHub Actions for this assessment.

## 3. Upload the site files

1. Open the new repository.
2. Choose **Add file → Upload files**.
3. Upload:
   - `index.html`
   - `README.md`
   - `AUDIT_NOTES.md`
4. Make sure `index.html` appears in the repository's top level—not inside another folder.
5. Commit the changes to the default branch, normally `main`.

The assessment HTML is well below GitHub's 25 MiB browser-upload limit.

## 4. Turn on GitHub Pages

1. In the repository, open **Settings**.
2. In the left sidebar, choose **Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Select your default branch, normally **main**.
5. Select **/(root)** as the folder.
6. Click **Save**.

For this one-file static site, publishing from a branch is the simplest setup.

## 5. Open the site

GitHub will build and deploy the site. This may take several minutes.

Return to **Settings → Pages** and use the published-site link once it appears.

For a project repository, the address is usually in this pattern:

`https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`

## Updating the assessment later

When a new version is created:

1. Open the same repository.
2. Choose **Add file → Upload files**.
3. Upload the new `index.html` with the same name.
4. Commit the replacement.
5. GitHub Pages will redeploy automatically.

You do not need to recreate the repository or reconfigure Pages each time.

## Local use

You can also open `index.html` directly in a modern browser without GitHub or an internet connection. The assessment has no external JavaScript or CSS dependencies.
