# Security Policy

## Project scope

`my-game-DOPE` is a mini game prototype. It is not currently positioned as a production multiplayer or commercial game.

## Security principles

- Do not commit secrets, API keys, tokens, or private data.
- Validate any user-provided input before using it.
- Avoid unsafe external scripts or untrusted asset sources.
- Handle browser storage failures and missing assets cleanly.
- Document any future third-party integrations.

## High-risk areas

- browser storage
- user input
- external assets
- analytics if added
- monetization or payments if added
- account systems if added

## Current limitations

This is a prototype. A production version would require dependency scanning, input validation, data/privacy review, deployment hardening, and broader browser testing.
