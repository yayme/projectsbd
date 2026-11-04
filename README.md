# Bangladesh Student Project Showcase

A responsive Jekyll + GitHub Pages platform for Bangladeshi students to publish projects, showcase technical work, and receive peer feedback through GitHub Discussions (Giscus).

## Features

- Project collection powered by Markdown files in `/_projects/`
- Home page card grid with live search + tech/tag filters
- Dedicated project pages with metadata, architecture/media sections, and Giscus comments
- Submission guide for student contributors via Pull Request (`/submit/`)

## Repository structure

- `_config.yml` - site configuration, collection setup, and Giscus options
- `_projects/*.md` - project entries with front matter metadata
- `_layouts/project.html` - individual project page template
- `submit.md` - contribution instructions for students

## 1) Fork and clone

1. Fork this repository to your GitHub account.
2. Clone your fork:

```bash
git clone https://github.com/<your-username>/projectsbd.git
cd projectsbd
```

## 2) Configure the site

1. Open `_config.yml`.
2. Update:
   - `url` and `baseurl` for your deployment target
   - `giscus.repo`, `giscus.repo_id`, `giscus.category`, and `giscus.category_id`
3. Add your own project markdown files to `/_projects/` by following `submit.md`.

## 3) Preview locally

Install dependencies and run Jekyll:

```bash
bundle install
bundle exec jekyll serve
```

Then open: `http://127.0.0.1:4000`

## 4) Deploy to GitHub Pages

1. Push changes to your repository default branch.
2. In GitHub, open **Settings → Pages**.
3. Set Source to **GitHub Actions** (or your preferred Pages source).
4. Wait for the workflow to complete.
5. Visit your published site URL.

## 5) Submit a project (for students)

1. Fork the repo.
2. Add one markdown file under `/_projects/`.
3. Commit and open a Pull Request.
4. After merge, the project appears automatically on the homepage.

---

If you need a starter entry, copy `_projects/sample-project.md` and customize it.
