# Murughan Chandran — Portfolio

A responsive static portfolio website and ATS-friendly resume.

## Deploy on Render

This project is configured as a Render static site. Render supports static sites with a global CDN and automatic redeploys from a connected Git repository.

### Option A — Blueprint
1. Put this project in a GitHub/GitLab/Bitbucket repository.
2. In Render, choose **New → Blueprint**.
3. Connect the repository.
4. Render will read `render.yaml` and publish the `website` directory.

### Option B — Static Site
Create **New → Static Site**, connect the repository, use:
- Build Command: leave blank
- Publish Directory: `website`

After deployment, Render provides an `onrender.com` URL. You can later connect a custom domain.

## Files
- `website/index.html` — portfolio
- `website/styles.css` — responsive styling
- `website/resume/Murughan_Chandran_Resume.pdf` — downloadable resume
- `Murughan_Chandran_Resume_ATS.docx` — editable resume
- `Murughan_Chandran_Resume_ATS.pdf` — PDF resume
- `render.yaml` — Render Blueprint configuration
