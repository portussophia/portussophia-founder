# James Roy Dennis — Founder Portfolio

**Domain:** https://founder.portussophia.com  
**Purpose:** Public Founder identity, biography, inquiry mode, selected work, applied lineage, and bounded engagement  
**Publication:** Jekyll on GitHub Pages

## Canonical boundary

This repository owns the Founder-facing surface for James Roy Dennis. The complete PortusSophia™ definition, governing declaration and programme disciplines, field architecture, research catalogue, programme provenance, and artifact standing remain canonical at https://public.portussophia.com.

Orientation may overlap. Complete programme ownership must not.

The governing portfolio and brand workbooks are private source material and must not be committed to this public repository.

## Local preview on Windows

Use Ruby 3.3 with the RubyInstaller Devkit and its MSYS2/MINGW development toolchain. Conda Ruby is not used because Jekyll's native gem extensions require the Windows development toolchain.

From the repository root:

```bat
bundle install
bundle exec jekyll serve --host 127.0.0.1 --port 4000 --no-watch
```

Open `http://127.0.0.1:4000/` while the command remains running.

## Navigation and routes

`_data/navigation.yml` is the sole primary-navigation source.

- `/` — Home
- `/bio/` — canonical biography hub
- `/bio/30/`, `/bio/120/`, `/bio/300/` — protected biography variants
- `/inquiry/` — Founder inquiry mode, origination, and stewardship
- `/work/` — curated selected work
- `/work/ten-old-ghosts/` — preferred long-form reading experience for the speculative dialogue *Ten Old Ghosts, One Very Long Dinner*
- `/lineage/` — applied professional lineage
- `/engage/` — bounded ways to engage

## Retained and superseded legacy material

- `/founder-statement/` is retained as a non-primary route. Its malformed front matter and attribution language were corrected; the page now states Founder responsibility, bounded AI contribution, authority limits, and the programme-surface boundary.
- `/about/` is retained as a non-primary boundary note and now explains the intentional separation between Founder and programme surfaces.
- The former homepage publication catalogue, capabilities list, and consulting sections are superseded by the focused Home, Selected Work, Applied Lineage, and Engage routes. Git history preserves the earlier copy.
- Founder and programme images are served from `https://assets.portussophia.com/img/site/`. The portrait uses `james-roy-dennis.jpg`; programme references use `logo.png`. Local image copies remain temporarily as rollback assets while the shared host is established.
- The `/bio/30/`, `/bio/120/`, and `/bio/300/` routes and short/medium/long functions remain stable. Their copy is harmonized to the canonically approved professional title; `/bio/` is the canonical hub sourced from the established long biography.
- `problem-statement.md` is intentionally absent. No universal problem statement is supplied on behalf of a visitor; each person or institution declares the problem they believe they are carrying. The stale navigation reference was removed rather than replaced.

No legacy content file was silently deleted during the first-stage reconstruction.

## Rights and use

Copyright © 2026 PortusSophia, LLC. All rights reserved.

See [`RIGHTS.md`](RIGHTS.md) for the repository’s default rights and use statement.

See [`LICENSE.md`](LICENSE.md) for the limited permissions specific to reading, citing, linking to, and briefly quoting material from the Founder portfolio.