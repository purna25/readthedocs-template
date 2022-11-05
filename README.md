`pip install -r requirements.txt`
or 
`pip install -e .[doc]`

To convert the `.rst` files to `.md`
`$ rst2myst convert docs/**/*.rst`

To run auto build documentation during development
`$ sphinx-autobuild docs/source docs/build/`
