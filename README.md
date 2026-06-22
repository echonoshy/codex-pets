# Codex Pets

Personal Codex custom pets.

## Pets

| Pet | Preview | Description |
| --- | --- | --- |
| Starling | ![Starling idle preview](pets/starling/previews/idle.gif) | A star-eyed anime-sticker debugging companion with a cream moon hair tuft, cyan-blue side hair, black hoodie, yellow star patch, and a small blue build-tool charm. It feels curious, careful, and focused on build, verify, and review loops. |
| Starry Avatar | ![Starry Avatar idle preview](pets/starry-avatar/previews/idle.gif) | A starry-eyed anime avatar pet based on the provided cartoon profile image. |

## Install

Clone this repository:

```bash
git clone https://github.com/echonoshy/codex-pets.git
cd codex-pets
```

Install every pet in this repository:

```bash
mkdir -p ~/.codex/pets
cp -R pets/* ~/.codex/pets/
```

Or install just one pet:

```bash
mkdir -p ~/.codex/pets
cp -R pets/<pet-id> ~/.codex/pets/<pet-id>
```

Restart Codex after copying the files. Codex loads custom pets from:

```text
~/.codex/pets/<pet-id>/
```

Each installed pet needs at least:

```text
pet.json
spritesheet.webp
```

## Repository Structure

Each pet lives in its own folder under `pets/`:

```text
pets/
  starling/
    pet.json
    spritesheet.webp
  starry-avatar/
    pet.json
    spritesheet.webp
```

The extra `contact-sheet.png`, `validation.json`, `review.json`, and `previews/` files are QA artifacts for checking the pet before installing it.
