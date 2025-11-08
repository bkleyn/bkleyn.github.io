# Personal Site

Personal portfolio website for Bernard Kleynhans - Actuary and Data Scientist.

Live site: [http://bkleyn.com](http://bkleyn.com)

## Tech Stack

- **Jekyll** - Static site generator
- **GitHub Pages** - Hosting
- **Bootstrap** - Frontend framework
- **Font Awesome** - Icons
- **Docker** - Local development environment

## Local Development

### Using Docker (Recommended)

1. Make sure Docker is installed and running
2. Run the development server:
   ```bash
   docker-compose up
   ```
3. Visit [http://localhost:4000](http://localhost:4000)

The site will automatically rebuild when you make changes.

### Using Local Jekyll

1. Install Ruby and Bundler
2. Install dependencies:
   ```bash
   bundle install
   ```
3. Run the development server:
   ```bash
   bundle exec jekyll serve
   ```
4. Visit [http://localhost:4000](http://localhost:4000)

## Updating Content

All content is managed through the `_data/data.yml` file. Edit this file to update:

- Profile information (name, tagline, contact details)
- About section
- Work experience
- Education
- Projects
- Publications
- Interests

After editing, the site will automatically rebuild in development mode.

## Theme Customization

The theme skin can be changed in `_config.yml`:

```yaml
theme_skin: ceramic # Options: blue, turquoise, green, berry, orange, ceramic
```

Custom styles can be added in `assets/css/main.scss`.

## Deployment

The site is automatically deployed to GitHub Pages when changes are pushed to the `main` branch.

Custom domain configuration is in the `CNAME` file.

## Project Structure

```
├── _config.yml          # Site configuration
├── _data/
│   └── data.yml        # All site content
├── _includes/          # Reusable HTML components
├── _layouts/           # Page templates
├── _sass/              # Stylesheets
├── assets/             # Images, CSS, JavaScript
└── docker-compose.yml  # Docker development setup
```

## License

© 2025 Bernard Kleynhans. All Rights Reserved.