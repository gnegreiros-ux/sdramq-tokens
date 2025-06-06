
# Design Tokens - RAMQ

This repository contains the complete design token structure used for the RAMQ Design System, fully compatible with **Tokens Studio**.

## File Structure

```text
├── $metadata.json            # Defines token set order
├── $themes.json              # Theme configuration (e.g., semantic enabled)
├── primitive.json            # Base tokens: color, dimension, typography, etc.
├── semantic.json             # Semantic aliases: text, background, status, etc.
└── components/               # Component-specific token files
    ├── accordion/accordion.json
    ├── button/button.json
    ├── card/card.json
    ├── footer/footer.json
    ├── icon/icon.json
    ├── input/input.json
    ├── logo/logo.json
    ├── menu/menu.json
    ├── list/list.json
    ├── navbar/navbar.json
    └── text-symbols/text-symbols.json
```

## Key Features

- All tokens are written in **kebab-case** for naming consistency.
- **French descriptions** are preserved for accurate documentation.
- Uses **dynamic expressions** (e.g., `{dimension.base} * 0.25`) to enable scaling.
- Structure follows **Tokens Studio** best practices and integrates easily with Figma.

## Usage

1. Open Tokens Studio in Figma.
2. Import tokens from the zipped package.
3. Connect imported tokens to your Figma styles as needed.

## Roadmap

- Add support for light and dark themes.
- Generate compiled output in DTCG / Style Dictionary format.
- Integration with Supernova.io and other token management tools.

---

© Régie de l’assurance maladie du Québec — RAMQ Design System
