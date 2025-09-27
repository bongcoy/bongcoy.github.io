# Muhammad Pascal Dewantara - Portfolio Website

Portfolio website built with Jekyll and hosted on GitHub Pages. Features a modern design with complementary color scheme (#00C0F5 and #F57800) and Roboto font.

## Features

- **Single Page Application**: One page with smooth anchor navigation
- **Responsive Design**: Optimized for all device sizes
- **Modern UI/UX**: Clean design with smooth animations
- **Sections**:
  - Hero section with call-to-action
  - About section with companies and tools
  - Experience timeline
  - Project showcase grid
  - Social media links

## Setup Instructions

### Prerequisites
- Ruby (2.7+)
- Bundler gem
- Git

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/your-portfolio-repo.git
   cd your-portfolio-repo
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Run the development server**
   ```bash
   bundle exec jekyll serve
   ```

4. **View locally**
   Open http://localhost:4000 in your browser

### GitHub Pages Deployment

1. **Create a new repository** on GitHub named `yourusername.github.io`

2. **Push your code**
   ```bash
   git add .
   git commit -m "Initial portfolio commit"
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll to Pages section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Save

4. **Your site will be available** at `https://yourusername.github.io`

## Customization

### Update Personal Information

1. **Basic Info** - Edit `_config.yml`:
   ```yaml
   title: Your Name
   email: your.email@example.com
   description: Your Description
   url: "https://yourusername.github.io"
   ```

2. **About Section** - Edit `index.html` in the about section

3. **Experiences** - Edit `_data/experiences.yml`:
   ```yaml
   - role: "Your Role"
     company: "Company Name"
     duration: "X years"
     responsibilities:
       - "Responsibility 1"
       - "Responsibility 2"
     tools:
       - "Tool 1"
       - "Tool 2"
   ```

4. **Projects** - Edit `_data/projects.yml`:
   ```yaml
   - name: "Project Name"
     image: "assets/images/project-name.jpg"
     tools:
       - "Tool 1"
       - "Tool 2"
   ```

### Add Project Images

1. Create `assets/images/` directory
2. Add your project screenshots (recommended: 400x300px)
3. Update image paths in `_data/projects.yml`

### Customize Colors

Edit CSS variables in `assets/css/main.css`:
```css
:root {
  --primary-color: #00C0F5;
  --secondary-color: #F57800;
  /* Add your custom colors */
}
```

## File Structure

```
├── _config.yml           # Jekyll configuration
├── _data/
│   ├── experiences.yml   # Experience data
│   └── projects.yml      # Project data
├── _layouts/
│   └── default.html      # Main layout template
├── assets/
│   ├── css/
│   │   └── main.css      # Styles
│   ├── js/
│   │   └── main.js       # JavaScript
│   └── images/           # Project images
├── index.html            # Main page content
├── Gemfile              # Ruby dependencies
└── README.md            # This file
```

## Technologies Used

- **Jekyll**: Static site generator
- **HTML5 & CSS3**: Modern web standards
- **Vanilla JavaScript**: For interactions
- **Roboto Font**: Clean, modern typography
- **Responsive Design**: Mobile-first approach
- **GitHub Pages**: Free hosting

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Need help?** Open an issue or contact me through the social links on the website.