# Siva's GitHub Pages Portfolio

Welcome to my GitHub Pages site! This repository contains my professional portfolio and serves as a hub for the tools and projects I'm developing.

## 🚀 Live Site

Visit the live site at: [https://siva4it.github.io](https://siva4it.github.io)

## 📁 Repository Structure

```
siva4it.github.io/
├── _config.yml          # Jekyll configuration
├── index.md             # Main homepage
├── README.md            # This file
└── _tools/              # Individual tool pages (future)
```

## 🛠️ Features

- **Modern Design**: Clean, responsive layout with professional styling
- **Profile Section**: Personal information and social links
- **Tools Showcase**: Dedicated sections for your development tools
- **Mobile Responsive**: Optimized for all device sizes
- **SEO Optimized**: Proper meta tags and structure

## 🔧 How to Update

### Adding New Tools

1. **Create a new tool page** in the `_tools/` directory:
   ```markdown
   ---
   layout: tool
   title: Your Tool Name
   description: Brief description of your tool
   repo_url: https://github.com/username/tool-repo
   live_url: https://your-tool-demo.com
   ---
   
   ## About This Tool
   
   Detailed description of your tool...
   ```

2. **Update the main page** (`index.md`) to include your new tool in the tools grid.

### Updating Profile Information

Edit the `index.md` file to update:
- Profile information
- Skills and technologies
- Social media links
- Tool descriptions

### Changing the Theme

The site uses the Cayman theme by default. You can change it in `_config.yml`:

```yaml
theme: jekyll-theme-cayman
```

Available themes include:
- `jekyll-theme-cayman` (current)
- `jekyll-theme-minimal`
- `jekyll-theme-slate`
- `jekyll-theme-tactile`

## 🎨 Customization

### Colors and Styling

The site uses custom CSS embedded in the `index.md` file. You can modify:
- Color scheme in the `.profile-header` gradient
- Card hover effects
- Typography and spacing
- Mobile responsiveness

### Adding New Sections

You can add new sections by editing `index.md`:
- Experience timeline
- Blog posts
- Testimonials
- Contact forms

## 📱 Social Media Integration

The site includes links to:
- GitHub profile
- LinkedIn profile
- Email contact

Update these in both `_config.yml` and `index.md`.

## 🚀 Deployment

This site automatically deploys when you push changes to the `main` branch. GitHub Pages will:
1. Build the site using Jekyll
2. Deploy it to `https://siva4it.github.io`
3. Update within a few minutes

## 🔍 SEO and Analytics

The site includes:
- Meta descriptions
- Open Graph tags
- Structured data
- Social media cards

Consider adding Google Analytics by including the tracking code in your `_config.yml` or creating a custom layout.

## 📝 Future Enhancements

Planned features:
- [ ] Individual tool pages with detailed documentation
- [ ] Blog section for technical articles
- [ ] Interactive demos of tools
- [ ] Contact form integration
- [ ] Newsletter signup
- [ ] Dark mode toggle

## 🤝 Contributing

If you find any issues or have suggestions for improvements, feel free to:
1. Open an issue
2. Submit a pull request
3. Contact me directly

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Built with ❤️ using GitHub Pages and Jekyll** 