# Directory maintenance

Preserve the original design described in README.md. The user rejected both redesign attempts: the decorative version was cluttered and harder to read, and the plain light version lost the original's character.

Use `e2e510a` as the design baseline, with the small SkyBlue and Bezel Studios icons added. Keep its hero, category navigation, dark blue theme, card grid, typography, and subtle effects. Default to focused content and link updates. Do not introduce slogans, scattered tiny labels, decorative panels, or another theme/layout redesign without an explicit request.

Keep all confirmed social links. Use existing brand assets for icons. This is a static directory, not a game; no game build or QA harness is needed.

For publication, review the diff, run `git diff --check` and `git diff --cached --check`, stage explicit paths, and verify the live site in Chrome after Pages finishes.
