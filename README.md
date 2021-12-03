<!-- Badge for License -->
<div align="right">

  [![](https://img.shields.io/github/license/Hsins/TclKB.svg?style=flat-square)](./LICENSE)

</div>

<!-- title, logo and description -->
<div align="center">
  <img src="https://i.imgur.com/Oa3XMd0.png" alt="Tcl Knowledge Base" height="150px">

# TclKB (Tcl Knowledge Base)

🪶 _Knowledge Base (KB) for developers who are using the [Tcl (Tool Command Language)](https://www.tcl.tk/) programming language._

</div>

## Branches

There are three branches for difference use here:

- [`main`](https://github.com/Hsins/TclKB/tree/main) holds the README and License.
- [`docs`](https://github.com/Hsins/TclKB/tree/docs) stores the resource code of this [knowledge base](https://hsins.github.io/TclKB/).
- [`gh-pages`]([.tree/gh-pages](https://github.com/Hsins/TclKB/tree/gh-pages)) hosts the website pages published by GitHub Actions (check the [workflow file](https://github.com/Hsins/TclKB/blob/docs/.github/workflows/site-deployment.yaml)).

## Quick Start

```bash
# clone the project and checkout to 'docs' branch
$ git clone https://github.com/Hsins/TclKB.git
$ cd TclKB && git checkout docs

# create the virtual environment
$ python3 -m venv env

# activate the virtual environment
$ source env/bin/activate                       # Unix-like
$ .\env\Scripts\Activate.ps1                    # Windows

# install dependencies
$ pip install -r requirements.txt

# start the server
$ mkdocs serve
```

## License

Licensed under the MIT License, Copyright © 2021-present Hsins.
