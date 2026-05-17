# Merge Conflicts Resume Template

A simple Jekyll-powered resume website template built with Liquid, Sass, and structured YAML data.

## Overview

This repository contains a static resume site using Jekyll-style layouts and includes. The resume content is stored in `_data` YAML files and rendered through the main layout in `_layouts/resume.html`.

## Repository Structure

- `index.html` - site entry point and layout assignment
- `_layouts/resume.html` - main resume page template
- `_includes/` - reusable HTML fragments such as header, icon links, and print controls
- `_data/` - resume content data files (`associations.yml`, `education.yml`, `interests.yml`, `links.yml`, `projects.yml`, `recognitions.yml`, `skills.yml`)
- `css/main.scss` - primary stylesheet
- `_sass/` - Sass partials and variables
- `images/` - image assets used by the template
- `_assets/` - Sketch source and icon assets

## Usage

This project is designed to be generated with Jekyll or served as a static site after build.

1. Install Ruby and Jekyll if not already installed.
2. Run a local development server from the repository root:

```bash
bundle exec jekyll serve
```

3. Open the site in your browser at `http://localhost:4000`.

> If the repository does not include a `_config.yml` file, add one or use your own Jekyll configuration to enable site generation.

## Customization

- Edit `_data/*.yml` to update resume content.
- Update `css/main.scss` and `_sass/` partials for styling changes.
- Adjust `index.html` and `_layouts/resume.html` for layout or structural changes.

## License

This project is licensed under the terms of the included `LICENSE` file.
