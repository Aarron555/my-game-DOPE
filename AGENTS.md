# Engineering Protocol

Use this file as the project standard for future AI-assisted code changes.

## Core standard

- Validate input and state changes before using them.
- Avoid placeholder logic in playable paths.
- Keep game state predictable where practical.
- Handle missing assets, reset flows, browser storage issues, and build errors clearly.
- Keep dependencies minimal and documented.
- Do not commit secrets, tokens, or private data.

## Change workflow

1. Break the requested change into small parts.
2. Identify likely reliability and gameplay failure modes before coding.
3. Implement the full change with readable code and clear errors.
4. Add or update tests where practical.
5. Verify the app can build or run, or document what was not verified.

## Hiring-proof emphasis

This repo should demonstrate product prototyping, game loop thinking, UI interaction, deployable frontend work, and disciplined documentation.
