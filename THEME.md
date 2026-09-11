# Profile styling

The README follows a centered terminal-and-credentials layout. All custom artwork is in `assets/`; changing it does not require rebuilding or installing dependencies.

- Terminal: `assets/terminal_banner.svg`. Charcoal background `#0d1117`, frame `#30363d`, green prompt `#7ee787`, blue `#79c0ff`, amber `#e3b341`, purple `#d2a8ff`.
- Timing: each command types at 10 characters per second (100 ms per character), matching the reference's normal command cadence. The sequence finishes at about 21 seconds, holds until 28.2 seconds, gently clears, and restarts every 30 seconds.
- Accessibility: reduced-motion preferences show the complete terminal immediately.
- Certificates: locally hosted custom display icons in `assets/certs/`, linked to issuer credentials in the README. These are display artwork, not official issuer-issued badges.
- Toolbox: a categorized local SVG panel with full-color Skill Icons below it.
- Profile, progression, current learning and toolkit panels: standalone 560px SVG assets. Learning status is qualitative, with no invented progress percentages.
- Security+: a neutral dashed study tile, explicitly in progress; no earned badge or credential link.
- Dividers: a static, subtle shell prompt separator.
- After editing an existing image, increase its README `?v=` value to refresh cached previews.

The previous SOC theme is recoverable from commit `cb57474`. The previous charcoal version is in `04da99c`.
