# tommmys Lab

[![Deploy](https://github.com/tommmylee/tommmylee.github.io/actions/workflows/deploy.yml/badge.svg)](https://github.com/tommmylee/tommmylee.github.io/actions/workflows/deploy.yml)
[![pages-build-deployment](https://github.com/tommmylee/tommmylee.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/tommmylee/tommmylee.github.io/actions/workflows/pages/pages-build-deployment)

A simple, clean, and responsive academic portfolio website built with [Jekyll](https://jekyllrb.com/) and the [al-folio](https://github.com/alshedivat/al-folio) theme.

## 🌐 Live Demo

Visit the site at: [https://tommmylee.github.io](https://tommmylee.github.io)

## ✨ Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Dark Mode**: Automatic light/dark theme switching
- **Academic Profile**: Showcase your publications, projects, and research
- **Blog**: Built-in blogging capabilities with categories and tags
- **Publications**: Automatically generated from BibTeX files
- **Projects**: Display your research projects with custom categories
- **CV Page**: Clean layout for your curriculum vitae
- **Search**: Integrated search functionality for posts and content
- **Social Media Integration**: Links to all your professional profiles
- **GitHub Pages Ready**: Easy deployment to GitHub Pages

## 🚀 Quick Start

### Using Docker (Recommended)

```bash
# Pull and run the pre-built image
docker compose pull
docker compose up
```

Then open your browser and navigate to `http://localhost:8080`

### Local Setup

```bash
# Install dependencies
bundle install
pip install jupyter

# Run the server
bundle exec jekyll serve
```

Then open your browser and navigate to `http://localhost:4000`

## 📁 Project Structure

```
├── _bibliography/      # BibTeX files for publications
├── _books/             # Book reviews and recommendations
├── _news/              # News and announcements
├── _pages/             # Main pages (about, cv, projects, etc.)
├── _posts/             # Blog posts
├── _projects/          # Project descriptions
├── _sass/              # Custom SCSS styles
├── assets/             # Images, CSS, JS, and other static files
├── bin/                # Utility scripts
└── _config.yml         # Site configuration
```

## ⚙️ Configuration

Edit `_config.yml` to customize:

- **Site Info**: Title, name, description, keywords
- **URL Settings**: Your GitHub Pages URL
- **Theme**: Color schemes, dark mode settings
- **Analytics**: Google Analytics, Pirsch, etc.
- **Features**: Enable/disable math, masonry layout, tooltips, etc.
- **Social Links**: Add your social media profiles

## 📝 Content Management

### Adding Publications

1. Add your BibTeX entries to `_bibliography/papers.bib`
2. Jekyll will automatically generate the publications page

### Creating Blog Posts

1. Create a new file in `_posts/` with format `YYYY-MM-DD-title.md`
2. Add front matter with title, description, and tags

### Updating Projects

1. Create markdown files in `_projects/`
2. Use front matter to set project image, category, and description

## 🛠️ Deployment

### GitHub Pages (Automatic)

1. Push changes to your `main` branch
2. GitHub Actions will automatically build and deploy
3. The site will be available at your GitHub Pages URL

### Manual Deployment

```bash
bundle exec jekyll build
# Deploy the contents of _site/ to your hosting server
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This work is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## 🙏 Acknowledgments

- Built with [al-folio](https://github.com/alshedivat/al-folio) theme
- Powered by [Jekyll](https://jekyllrb.com/)
- Hosted on [GitHub Pages](https://pages.github.com/)

---

**Last Updated**: 2024
