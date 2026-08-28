# SHAYA OS — Project Scope

## What it is
An Arch-based Linux distribution with Hyprland as the default desktop,
built as a minimal/hacker-oriented distro other people could realistically
use — not just a personal setup, and not just a reskin of Arch.

## Identity
Retro terminal / hacker-green CRT aesthetic — expressed through boot
splash, MOTD, terminal theming, and a signature branded system-info tool.
Personality is meant to be real, not just cosmetic: the project also aims
for genuine improvements in stability, hardware compatibility, and
organization over a raw Arch install.

## Installer
Terminal/script-based (`install.sh`), not a GUI installer like Calamares.
Should be hardened over time — real error handling, sensible partitioning,
driver detection — rather than staying a rough first-draft script.

## Hardware support
No upfront broad-hardware engineering effort. Compatibility issues (driver
detection, edge cases) get handled reactively as they're discovered,
starting with the maintainer's own hardware.

## Default package philosophy
Minimal but useful: a working terminal + Hyprland setup plus common
essentials (browser, file manager, everyday tools) — not bare-minimum,
not "batteries included" with a large curated app set.

## Package sources
Standard Arch repositories + AUR only. No custom package repository or
packaging infrastructure planned.

## Openness
GitHub repo (github.com/Harsh-Oraon/shaya-os) is public, but not being
actively promoted or announced. Visible to whoever finds it; not seeking
users or contributors at this stage.

## Ownership & pace
Built solo, hands-on — every step done and understood by the maintainer
rather than delegated. Treated as a long-term (2-3 year) project with no
fixed deadline; expected to move in bursts around school and slow down
during busy periods.

## Explicitly out of scope (for now)
- Custom package repository
- GUI installer
- Broad hardware compatibility testing program
- Actively growing a user/contributor base
- Custom compositor or kernel work (may be revisited as a stretch goal
  well beyond v1.0, not part of the core plan)

## Milestones
See `docs/roadmap.md` for the phased build plan (v0.1 → v1.0 and beyond).
