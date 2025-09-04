# README

Welcome! The purpose of this documentation page is to collect information on NYU's Center for Robotics and Embodied Intelligence (CREO) including inventory, README's for shared robots, and README's for shared equipment. The docs could also be extendable to new topics as well.  The docs are built using [Sphinx](https://www.sphinx-doc.org/en/master/) and [MyST](https://myst-parser.readthedocs.io/en/latest/) to allow easy contributing via Markdown, but there are nice features like cross indexing. 

## Quick start (Linux)

```bash
# from repo root
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
make -C docs html
xdg-open docs/build/html/index.html
# or open docs/build/html/index.html in a browser
```

## Contributing 
- see page in docs 
