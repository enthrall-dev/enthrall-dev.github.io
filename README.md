# Enthrall Dev

Welcome to the Enthrall Dev portfolio site. This is a Jekyll-based website showcasing captivating and innovative applications developed by a solo developer.

## Features

- Jekyll-based static site
- Tailwind CSS for styling
- JSON data for easy app management
- Default icon for apps without an icon
- Contact page

## Setup

### Prerequisites

- Ruby and Jekyll installed
- Node.js and npm installed

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/enthrall-dev.github.io.git
   cd enthrall-dev.github.io
   ```

2. **Install Jekyll dependencies:**

   ```bash
   bundle install
   ```

3. **Install Tailwind CSS and other npm dependencies:**

   ```bash
   npm install
   ```

4. **Build the Tailwind CSS file:**

   ```bash
   npm run build:css
   ```

5. **Serve the site locally:**

   ```bash
   bundle exec jekyll serve
   ```

6. **Open your browser and visit:**

   ```
   http://localhost:4000
   ```

## Usage

### Adding Apps

Apps are managed through a JSON file located at `assets/data/apps.json`. Each app should have the following structure:

```json
[
  {
    "icon": "/path/to/icon.png",
    "name": "App Name",
    "description": "A brief description of the app.",
    "link": "https://link.to/app"
  }
]
```

### Default Icon

If an app does not have an icon, a default icon located at `assets/images/default-icon.png` will be used.

### Contact Page

The contact page is accessible from the navigation menu and provides an email link for reaching out.

## Deployment

This site is configured to be deployed to GitHub Pages. Ensure your repository is named `enthrall-dev.github.io` and push your changes to the `main` branch.

## License

This project is licensed under the MIT License.
