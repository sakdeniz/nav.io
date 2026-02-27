# Navio Web Site (https://nav.io)

This project is built with **Jekyll** and uses **Bundler** for dependency management.

## 📦 Requirements

- Ruby (>= 2.7 recommended)
- Bundler
- Jekyll

Check versions:

```bash
ruby -v
bundle -v
jekyll -v
```

---

## 📥 Installation

Clone the repository:

```bash
git clone https://github.com/USERNAME/REPO_NAME.git
cd REPO_NAME
```

Install dependencies:

```bash
bundle install
```

---

## 🧪 Development Server

Start the local server:

```bash
bundle exec jekyll serve
```

Open:

http://localhost:4000

### If the site is inside a subfolder

```bash
bundle exec jekyll serve --source nav.io
```

---

## 🏗️ Build for Production

```bash
bundle exec jekyll build
```

Output directory:

```
_site/
```

---

## ⚙️ Configuration

Main configuration file:

```
_config.yml
```

Production build:

```bash
JEKYLL_ENV=production bundle exec jekyll build
```

---

## 📁 Project Structure

```
.
├── _layouts
├── _includes
├── _posts
├── _config.yml
├── assets
├── index.md
└── Gemfile
```

---

## 🚀 Deployment

Compatible with:

- GitHub Pages
- Netlify
- Vercel
- Any static hosting

---

## 🛠 Useful Commands

Live reload:

```bash
bundle exec jekyll serve --livereload
```

Clean build:

```bash
bundle exec jekyll clean
```

---

## 🐛 Troubleshooting

### Could not locate Gemfile

Run the command inside the project root where `Gemfile` exists.

### Port already in use

```bash
bundle exec jekyll serve --port 4001
```

---

## 📄 License

MIT
