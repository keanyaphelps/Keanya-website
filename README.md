# Keanya's Personal Website

This is my personal website built with [Hugo](https://gohugo.io/) and deployed using GitHub Pages.

## 🌐 Live Site

Visit the live website at: [https://keanyaphelps.com/](https://keanyaphelps.com/)

## 🚀 Features

- **Fast & Modern**: Built with Hugo static site generator
- **Responsive Design**: Mobile-friendly PaperMod theme
- **Automated Deployment**: GitHub Actions for CI/CD
- **SEO Optimized**: Meta tags, sitemap, and RSS feed
- **Blog Ready**: Markdown-based content management

## 📁 Site Structure

- **About**: Learn more about me and my background
- **Blog**: Thoughts on technology, career, and community
- **Talks**: Speaking engagements and presentations
- **Community**: Community involvement and initiatives

## 🛠️ Development

### Prerequisites

- [Hugo Extended](https://gohugo.io/installation/) (v0.148.2 or later)
- [Git](https://git-scm.com/)

### Local Development

1. Clone the repository:

   ```bash
   git clone https://github.com/keanyaphelps/Keanya-website.git
   cd Keanya-website
   ```

2. Install the theme (if not already done):

   ```bash
   git submodule update --init --recursive
   ```

3. Start the development server:

   ```bash
   hugo server -D
   ```

4. Open your browser to `http://localhost:1313`

### Creating Content

- **New blog post**: `hugo new content posts/your-post-title.md`
- **New page**: `hugo new content page-name.md`

### Building for Production

```bash
hugo --gc --minify
```

## 🚀 Deployment

This site is automatically deployed to GitHub Pages using GitHub Actions. The workflow is triggered on every push to the `main` branch.

### Setup Instructions

1. **Create GitHub Repository**: Create a new repository named `Keanya-website`
2. **Enable GitHub Pages**: Go to repository Settings → Pages → Source: GitHub Actions
3. **Push Code**: Push this code to the `main` branch
4. **Automatic Deployment**: GitHub Actions will build and deploy the site

## 📝 Theme

This site uses the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme, which provides:

- Clean, minimal design
- Dark/light mode toggle
- Fast loading times
- Mobile responsive
- SEO friendly
- Social media integration

## 🤝 Contributing

If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

Built with ❤️ using Hugo and GitHub Pages.
