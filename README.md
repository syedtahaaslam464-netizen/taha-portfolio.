# Taha Aslam — Portfolio Website

A responsive personal portfolio with a separate starter admin page.

## Files
- `index.html` — public portfolio
- `style.css` — design and responsive layout
- `data.js` — portfolio content (experience, education, skills, projects)
- `admin.html` / `admin.js` / `admin.css` — local admin editor
- `assets/` — profile image and CV

## Important admin limitation
This is a static GitHub Pages project. The included admin editor saves personal edits in the current browser's `localStorage`; it does **not** securely publish changes to all visitors. The password is visible in client-side JavaScript and is not secure authentication. For a real multi-device admin panel with shared updates, connect Firebase or Supabase (authentication + database + image storage) before using it for sensitive or production content.

Default demo password: `taha-admin-2026`. Change it in `admin.js` before publishing. Do not use this demo password for any important account.

## Add your profile photo
Replace `assets/profile-placeholder.svg` with your photo file (e.g. `profile.jpg`) and update `profileImage` in `data.js` to `assets/profile.jpg`.

## Add your CV
Put your PDF at `assets/Taha_Aslam_CV.pdf`. The current project includes the supplied CV PDF.

## Publish on GitHub Pages
1. Create a new GitHub repository named `taha-portfolio`.
2. Upload all files and folders from this project (not the ZIP itself).
3. Open repository **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Wait for GitHub Pages to publish. Your URL will be shown in the Pages section, usually `https://YOUR-USERNAME.github.io/taha-portfolio/`.

## Update experience, education, skills and projects
Edit the corresponding arrays in `data.js`, then upload/commit the changed file to GitHub.
