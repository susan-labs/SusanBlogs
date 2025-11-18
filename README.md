# 📝 Susan’s Tech Blog

Welcome to the source code for **blogs.susankhanal.com** —  
a personal knowledge base and documentation hub built with **Hugo**, **Cloudflare Pages**, and **Obsidian**.

This repository contains the full Markdown content, assets, and configuration used to generate the website.

---

## 🚀 Tech Stack

- **Static Site Generator:** Hugo (Extended)
- **Theme:** Terminal Theme (customized)
- **Deployment:** Cloudflare Pages
- **Content Editing:** Obsidian
- **Version Control:** GitHub

---

## 📂 Project Structure

/
├── content/ # Blog posts, notes, documentation (Markdown)
├── static/ # Images, screenshots, files
├── layouts/ # Custom layouts & overrides
├── assets/ # SCSS, JS, theme assets
├── archetypes/ # Content templates
├── hugo.toml # Site configuration
└── themes/ # Hugo theme(s)

yaml
Copy code

---

## 🔧 Local Development

Make sure you have Hugo Extended installed.

```bash
hugo server -D
Visit your site at:

arduino
Copy code
http://localhost:1313
📦 Build
Build the static website:

bash
Copy code
hugo
Output will be generated inside the public/ directory.

☁️ Deployment (Cloudflare Pages)
The website is deployed automatically using Cloudflare Pages.

Recommended settings:

Build command: hugo

Build directory: public

Environment variables:

HUGO_VERSION = latest

HUGO_ENV = production

🖊 Workflow (Obsidian → Hugo → GitHub)
Write notes or blog posts in Obsidian

Save them inside the repository’s content/ folder

Commit and push to GitHub

Cloudflare Pages builds and deploys automatically

This creates a smooth, automated blogging workflow powered by Markdown.

🤝 Contributing
This is a personal blog, but suggestions and improvements are welcome.
Feel free to open an issue or pull request.

📜 License
Code is licensed under MIT.
Content is copyrighted by Susan Khanal.

🌐 Website
https://blogs.susankhanal.com/
