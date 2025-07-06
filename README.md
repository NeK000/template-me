# Me Page (Hugo Static Site)

[![Visit Live Demo](https://img.shields.io/badge/Visit%20Live%20Demo-brightgreen?style=for-the-badge)](http://NeK000.github.io/template-me/)

**This is a template repository!**

To use it, click the "Use this template" button on GitHub to create your own repository. Do not clone this repository directly—instead, create a new repo from this template, then clone your new repository.

This is a simple, responsive single-page site built with [Hugo](https://gohugo.io/). It features a profile image, title, description, and a set of customizable buttons/links. The site is styled with custom CSS and is ready for deployment on GitHub Pages.

## License

This project is licensed under the [MIT License](LICENSE).

## Project Structure

```
config.toml
LINTING.md
package.json
README.md
stylelint.config.js
data/
  config.yaml
layouts/
  index.html
public/
  index.html
  index.xml
  sitemap.xml
  categories/
    index.xml
  css/
    style.css
  images/
    background.jpg
    logo.png
  tags/
    index.xml
static/
  css/
    style.css
  images/
    background.jpg
    logo.png
```

## Setup Instructions

1. **Install Hugo**: Download and install Hugo from the [official website](https://gohugo.io/getting-started/installation/).

2. **Clone the Repository**:
   ```sh
   git clone <repository-url>
   cd me
   ```

3. **Run the Development Server**:
   ```sh
   hugo server
   ```
   Open your browser at [http://localhost:1313](http://localhost:1313) to view the site.

## Customization

- **Site Content**: Edit `data/config.yaml` to change the site title, description, main image, and button links.
- **Styles**: Modify `static/css/style.css` for custom styles.
- **Images**: Place your images in `static/images/`.
- **Layout**: The main HTML structure is in `layouts/index.html`.

## Deployment to GitHub Pages

This project includes a GitHub Actions workflow to automatically build and deploy your site to GitHub Pages:

1. **Set the `baseURL` in `config.toml`** to your GitHub Pages URL, e.g.:
   ```toml
   baseURL = "https://<your-username>.github.io/<your-repo-name>/"
   ```
2. **Push to the `main` branch**. The workflow in `.github/workflows/gh-pages.yml` will build and deploy your site to the `gh-pages` branch.
3. **Configure GitHub Pages** in your repository settings to serve from the `gh-pages` branch.

## Contributing

Feel free to open issues or submit pull requests for improvements or new features.

---

© 2025 Nikolay Nikolov