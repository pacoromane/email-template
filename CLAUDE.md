# Claude Instructions

You are editing a production HTML email for Paco Romane comedy-show updates.

## Requirements

- Preserve the 600px desktop email container.
- Use table-based email HTML.
- Keep essential styles inline.
- Do not add JavaScript.
- Do not use nested HTML comments.
- Do not apply mobile stacking rules globally to all `td` elements.
- Scope show-card mobile rules only to `.show-card`.
- Scope featured-content rules only to `.feature-layout`.
- Preserve Gmail, Apple Mail, and Outlook compatibility.
- Preserve the existing dark vintage comedy aesthetic.
- Keep all image URLs absolute and hosted under:

  `https://pacoromane.github.io/comedy-show-updates/assets/images/`

## Show-card editing

Each show must remain a complete block between:

- `SHOW CARD START`
- `SHOW CARD END`

Never leave unmatched `table`, `tr`, or `td` tags.

## Before returning code

Check for:

- balanced HTML table tags
- valid image paths
- no placeholder ticket URLs
- mobile responsiveness
- no visible instructional comments
- no fake mailing address
