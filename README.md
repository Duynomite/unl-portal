# UNL Ancillary Sales Course

Internal training portal for licensed Clear Path Coverage agents.

**Live URL:** https://duynomite.github.io/unl-portal/
**Iframed at:** clearpathcoverage.com (password-protected page)

## What this is

A self-paced course teaching CPC's licensed Medicare agents to sell UNL Hospital Indemnity (HI) and Home Healthcare with TCare (HHC) — both as cross-sells on existing Medicare Advantage calls and as standalone ancillary leads. ~9-10 hours of content across 4 parts (Foundation, Method, Practice, Capstone) with mastery gates and a printable certification scorecard.

## Deploy structure

This repo is the **public deploy artifact only**. It contains a single static HTML file (`index.html`) served by GitHub Pages.

- **Source:** lives in the private `Duynomite/claude-projects` repo at `TOOLS/UNL_Agent_Portal.html`
- **Updates:** copy the source HTML to `index.html`, commit, push. Pages redeploys in ~30 seconds.

## Tech

Single-file React 18 + Tailwind v4 + Babel via CDN. No build step. localStorage for progress. No backend in v1 — agents do the course on one device and screenshot the cert at the end.

## Admin

Hidden gear icon revealed by `?admin=1` URL param, `#admin` hash, or `Ctrl+Shift+A` keyboard shortcut. Password-gated thereafter.

## Bug reports

Floating 🐛 button on every page. Submits open a `mailto:` to `connor@clearpathcoverage.com` with auto-captured context (current section, viewport, progress snapshot, portal version).

## License

Proprietary. For internal CPC agent use only.
