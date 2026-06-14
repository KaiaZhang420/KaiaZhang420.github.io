# Kaia Zhang - Academic Personal Website

This repository contains the source code for my academic personal website. The site introduces my research background, publications, projects, teaching, education, and professional experience.

Website: <https://kaiazhang420.github.io/>

## Site Content

The website includes:

- Research interests
- Publications
- Projects
- Education
- Teaching
- Professional experience

## Technical Structure

This site is built with:

- Jekyll
- GitHub Pages
- AcadHomepage template

The main content and configuration files are:

- `_pages/about.md` - homepage and main academic profile content
- `_config.yml` - site configuration, author information, navigation, and theme settings
- `_data/navigation.yml` - navigation links
- `images/` - profile, publication, and site images
- `Gemfile` - Ruby/Jekyll dependencies for local development
- `run_server.sh` - local development script

## Run Locally

Install the Ruby dependencies from the existing `Gemfile`:

```bash
bundle install
```

Then start the local Jekyll server using the repository script:

```bash
bash run_server.sh
```

The script runs:

```bash
bundle exec jekyll liveserve
```

## Attribution

This website is based on the [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io) template. The template attribution and license information are preserved in this repository.
