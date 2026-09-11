# Profile styling

The README follows a centered terminal-and-credentials layout. All custom artwork is in `assets/`; changing it does not require rebuilding or installing dependencies.

- Terminal: `assets/terminal_banner.svg`. Charcoal background `#0d1117`, frame `#30363d`, green prompt `#7ee787`, blue `#79c0ff`, amber `#e3b341`, purple `#d2a8ff`.
- Timing: the three commands start at 2, 9 and 22 seconds; their typing lasts 3, 4 and 4 seconds. Output finishes at 30 seconds, stays visible, and does not reset. Edit the CSS delays together to preserve reading pauses.
- Accessibility: reduced-motion preferences show the complete terminal immediately.
- Certificates: locally hosted custom display icons in `assets/certs/`, linked to issuer credentials in the README. These are display artwork, not official issuer-issued badges.
- Toolbox: full-color Skill Icons plus brand-colored Shields badges.
- Dividers: a static, subtle shell prompt separator.
- After editing an existing image, increase its README `?v=` value to refresh cached previews.

The previous SOC theme is recoverable from commit `cb57474`.
