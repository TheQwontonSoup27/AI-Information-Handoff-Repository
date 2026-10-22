# Project Status — Soups Unified Launcher (SUL)

**Last updated:** 2026-10-22  
**Project state:** Requirements and architecture baseline prepared; no implementation/testing claims made by this document.

## Confirmed planning decisions
- Project name: Soups Unified Launcher (SUL).
- Open-source, modular desktop launcher with 10 feature modules described in `PROJECT_SPEC.md`.
- Security foundations, theme hooks, safe file operations, logs, and recovery are first-stage requirements.
- Helldivers 2 version 7.1.1 isolation is a separate testable track; preserve the original Steam installation.
- Medal.tv is the intended capture/clipping integration, constrained to supported APIs and desktop interfaces.
- Included UI images are conceptual design references, not production assets.

## Not yet verified
- Programming language/UI framework/target OS.
- Repository implementation state and tests.
- Game adapter functionality, multiplayer integrity checks, Steamworks replacement, Medal API access, and emulator-specific support.
- Project license and third-party license review.

## Next action
Claude should inspect the real repository and propose the smallest useful first vertical slice before making broad changes. Follow `CLAUDE.md` and `PROJECT_SPEC.md`.
