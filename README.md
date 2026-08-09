Source code of [Yijin Wang's website](https://yijinw412.github.io/yijinwang/).

Jekyll on GitHub Pages. No theme dependency — the layout and stylesheet in this
repo are self-contained.

## Editing

| File | What it controls |
| --- | --- |
| `index.md` | All page content: about, publications, education, contact |
| `_config.yml` | Name, masthead lines, SEO description, `baseurl` |
| `_layouts/default.html` | Page shell and masthead markup |
| `assets/css/style.scss` | Colors, typography, spacing (light + dark) |

Pushing to `main` rebuilds and redeploys automatically.

**`baseurl` must match the repository name.** It is currently `/yijinwang`. If
the repo is ever renamed, update `baseurl` in the same commit or every
stylesheet and image will 404.
