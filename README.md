# Codex Pets

Personal Codex custom pets.

## Structure

Each pet lives in its own folder under `pets/`:

```text
pets/
  starling/
    pet.json
    spritesheet.webp
```

To install a pet locally, copy the pet folder into:

```text
~/.codex/pets/
```

For example:

```bash
cp -R pets/starling ~/.codex/pets/starling
```

The extra `contact-sheet.png`, `validation.json`, `review.json`, and `previews/` files are QA artifacts for checking the pet before installing it.
