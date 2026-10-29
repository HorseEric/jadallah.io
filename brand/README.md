# brand

Eric Jadallah's brand as one stylesheet, a page template and the site marks. Every personal project starts here.

The design system (principles, components, the reasons) is the source of truth; this repo is generated from it. Change values there, then here, never only here.

## Use it

Link the stylesheet:

```html
<link rel="stylesheet" href="https://jadallah.io/brand/jadallah.css">
```

or copy `jadallah.css` into the project. Start pages from `index.html`. The marks (favicons, `og-image.png`) live at the jadallah.io site root. Keep the `<head>` block from the template.

For an app or dashboard, opt into the dark theme with `<html data-theme="dark">`. Documents and sites stay on Paper.

## What is in `jadallah.css`

- Tokens as CSS variables: `--paper`, `--ink`, `--graphite`, `--link`, `--rule`, `--panel`, `--plate`, `--callout`, `--success`, `--warning`, `--error`; `--font-sans`, `--font-mono`; `--space-6` to `--space-80`; `--column`, `--control`, `--hairline`.
- Type: Helvetica Neue with Inter behind it, weights 400 and 600; SF Mono with JetBrains Mono behind it for code and data.
- Components, all prefixed `jd-`: page header and footer, sections and lists, figures and figure grids, experience, spec and data tables, callout, breadcrumb, chart styles, résumé sheet, slides, LinkedIn banner, and for apps: buttons, form controls, status messages, code.

## Rules in one breath

Number sections and figures. One column, 760px. Square corners, 1px rules, no shadows. `ink` on `paper`, `graphite` for metadata, `link` only on links. Real renders and bench photos, captioned `Fig. n.`. In an app: one primary button, every error says the fix.
