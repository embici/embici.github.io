# Embici Blog

A personal blog built with Hugo and hosted on GitHub Pages. The blog uses the Anatole theme for a clean and modern look.

## Features

- 🚀 Fast and responsive design
- 📱 Mobile-friendly layout
- 🌙 Dark/Light mode support
- 🔍 Search functionality
- 📝 Markdown support
- 🏷️ Tags and categories
- 📅 Date-based organization

## Getting Started

### Prerequisites
- Hugo (latest version)
- Git

### Local Development
1. Clone this repository
   ```bash
   git clone https://github.com/embici/embici.github.io.git
   cd embici.github.io
   ```
2. Install Hugo (if not already installed)
   ```bash
   brew install hugo  # for macOS
   ```
3. Run the development server
   ```bash
   hugo server -D
   ```
4. Visit `http://localhost:1313` to view the site

### Building for Production
Run `hugo` to build the site. The output will be in the `public` directory.

## Content Management

### Adding New Posts
1. Create a new markdown file in `content/posts/`
2. Add the following front matter at the top of your post:
   ```markdown
   ---
   title: "Your Post Title"
   date: YYYY-MM-DD
   draft: false
   description: "Your post description"
   tags: ["tag1", "tag2"]
   categories: ["category1"]
   ---
   ```
3. Write your content in Markdown format

### Adding Images
1. Place your images in the `static/images/` directory
2. Reference them in your posts using:
   ```markdown
   ![Alt text](/images/your-image.jpg)
   ```

## Deployment
This site is configured to be deployed on GitHub Pages. The deployment is handled automatically through GitHub Actions:
1. Push changes to the `main` branch
2. GitHub Actions builds the site
3. The built site is deployed to the `gh-pages` branch
4. GitHub Pages serves the content from the `gh-pages` branch

## Customization

### Theme Configuration
The blog uses the Anatole theme. You can customize it by:
1. Modifying `config.toml` for basic settings
2. Overriding theme files in `themes/anatole/`

### Site Configuration
Edit `config.toml` to change:
- Site title and description
- Navigation menu
- Social media links
- Theme settings

## License
This project is open source and available under the MIT License. 