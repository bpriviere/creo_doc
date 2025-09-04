# Contributing 

## Design Philosophy
- Keep topics simple and self contained. 
- Prefer tasks and steps over long prose.
- Golden Rule: Ask yourself "Would I understand this if I were a new user?" 
- We are trying this for the first time, so please provide feedback and we will be adaptive. 

## Add a page
1. Create new **Markdown** (MyST) file `docs/source/my-page.md`
2. Add `my-page` to the toctree in `docs/source/index.md`
3. Rebuild: `make -C docs html`

## PR checklist
- [ ] New/changed page renders: `make -C docs html`
- [ ] Links work locally (open `docs/build/html/index.html`)
- [ ] We use automated testing so you won't be able to push if the changes do not at least work locally 
- [ ] Commands are copy/paste runnable on Linux