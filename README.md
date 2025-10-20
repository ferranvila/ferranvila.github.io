# Ferran Vila – Software Architect Portfolio

This repository contains the source code of my personal website and portfolio, hosted on **GitHub Pages** and powered by **Jekyll** using the `jekyll-theme-minimal` theme.

The site showcases my professional profile, experience, and selected software projects.

---

## Prerequisites

Before running the site locally, make sure you have installed:

```bash
brew install rbenv ruby-build
rbenv init
rbenv install 3.3.4
rbenv global 3.3.4
gem install bundler jekyll
```

---

## Local Setup

Clone this repository and install dependencies:

```bash
git clone https://github.com/ferranvila/ferranvila.github.io.git
cd ferranvila.github.io
bundle install
```

Run the site locally:

```bash
bundle exec jekyll serve
```

Then open [http://localhost:4000](http://localhost:4000) in your browser.

---

## Deployment

GitHub Pages automatically builds and deploys the site from the `master` branch.

Custom domain configuration: `www.ferranvila.com`

---

## License

This repository is published under the [MIT License](https://opensource.org/licenses/MIT).

---

© 2025 Ferran Vila. All rights reserved.