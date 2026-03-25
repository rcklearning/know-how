# Know-how (blog source)

This repository contains the **source code and content for my blog** (built with Jekyll and hosted via GitHub Pages).

## Live site
- https://rcklearning.github.io/know-how/

## Local development

### Prerequisites
- Ruby + Bundler
- Node.js (some tooling/assets may rely on it)

### Install dependencies
```bash
bundle install
```

### Run locally
```bash
bundle exec jekyll serve -l -H localhost
```

Then open:
- http://localhost:4000

## Using Docker (optional)
If you prefer not to install Ruby locally, you can use the included Docker setup:

```bash
docker compose up
```

Then open:
- http://localhost:4000

## Attribution / upstream template
This blog is based on the **Academic Pages** template, which in turn is built on the **Minimal Mistakes** Jekyll theme.

- Academic Pages: https://github.com/academicpages/academicpages.github.io
- Minimal Mistakes: https://github.com/mmistakes/minimal-mistakes

See `LICENSE.md` for licensing details.

---

<div align="center">

[![GitHub repo](https://img.shields.io/badge/repo-rcklearning%2Fknow--how-24292e?logo=github)](https://github.com/rcklearning/know-how)
[![License](https://img.shields.io/github/license/rcklearning/know-how?color=blue)](https://github.com/rcklearning/know-how/blob/master/LICENSE.md)
[![Last commit](https://img.shields.io/github/last-commit/rcklearning/know-how)](https://github.com/rcklearning/know-how/commits/master)

</div>