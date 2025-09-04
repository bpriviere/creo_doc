# Contributing 

How to write, build, and submit docs changes.

## Proposed Organization
- If one wants to add an item to the CREO doc: first add it to the inventory, and then we link a README to that item
- The inventory is a big table of items, pictures, and a link to the readme. 
- The README is a separate topic page for each item that contains particular information of each item: how to use, etc. 

## Documentation Philosophy
- Keep README's simple and self contained. 
- Golden Rule: Ask yourself "Would I understand this if I were a new user?" 

## How to add a page
- Create new **Markdown** (MyST) file `docs/source/my-page.md`
- Add `my-page` to the toctree in `docs/source/index.md`
- Rebuild: `make -C docs html`

## How to add a header
- Create new folder `docs/source/my-header`
- Add `my-header` to the toctree in `docs/source/index.md`
- Rebuild: `make -C docs html`

## Pull Request (PR) checklist
- Run `make -C docs html` and verify docs work locally (open `docs/build/html/index.html`). We use a docs build check so you won't be able to push or PR if the changes do not at least work locally. 
