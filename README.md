# mockingbird-99.github.io

Personal portfolio site for Jeremiah Tindana — SOC Analyst.

**Live site:** https://mockingbird-99.github.io

## What's here

- `index.html` — the entire site (structure, styles, and content in one file)
- `writeups/` — PDF incident write-ups linked from the "Investigation Write-ups" section

## Updating the site

This is a single static HTML file — no build step, no dependencies.

**To edit text** (bio, skills, experience, certs):
1. Click `index.html` in this repo
2. Click the pencil icon (Edit this file)
3. Find the section using the `<!-- ============ SECTION NAME ============ -->` comments
4. Edit the text between the HTML tags, then commit directly to `main`
5. Changes go live within ~1 minute

**To add a new write-up:**
1. Add the PDF to the `writeups/` folder
2. In `index.html`, find the commented-out `TEMPLATE` block inside the
   `<!-- ============ WRITE-UPS / PROJECTS ============ -->` section
3. Copy that template, fill in the case name, date, summary, and PDF filename
4. Paste it **above** the most recent existing card (newest first)
5. Commit — no need to touch CSS or any other file

## Certifications status

Update the `status-badge` class (`done` or `progress`) in the Certifications
section as certs are completed — currently Cisco CyberOps Associate is
`progress`.
