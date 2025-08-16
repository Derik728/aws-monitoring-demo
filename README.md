# AWS EC2 Monitoring — Demo Site

This is a static site you can host with **GitHub Pages** to showcase your project.  
It includes:
- A clean landing page
- An interactive preview modal for dashboard and alarms
- Placeholder images you can replace with real screenshots

## Replace placeholders
- Update the GitHub link in `index.html` (`yourusername` → your actual username / repo).
- Replace `assets/images/dashboard.svg` and `assets/images/alarms.svg` with your screenshots using the same filenames.

## Local preview
Open `index.html` in a browser.

## Publish on GitHub Pages
1. Create a new public repository, e.g., `aws-monitoring-demo`.
2. Upload all files from this folder (keep `index.html` at repo root).
3. Go to **Settings › Pages** → **Build and deployment** → Source: **Deploy from a branch**.
4. Branch: `main` (or `master`), Folder: **/ (root)** → **Save**.
5. Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

## Resume button
Use this HTML (or Markdown) in your resume/portfolio:

```html
<a href="https://<your-username>.github.io/aws-monitoring-demo/" target="_blank" rel="noopener">
  🚀 Launch Demo
</a>
```

or Markdown:

```md
[🚀 Launch Demo](https://<your-username>.github.io/aws-monitoring-demo/)
```
