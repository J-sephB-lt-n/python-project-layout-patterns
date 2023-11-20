https://docs.python-guide.org/writing/structure/

```bash
.
├── LICENSE           
├── MANIFEST.in
├── Makefile          # defines runnable project tasks (e.g. build, install_dependencies, run, clean_up etc.)
├── README.md         # project entry documentation (first thing new user will read)
├── docs              # reference documentation
│   ├── Makefile
│   ├── conf.py
│   ├── index.rst
│   └── make.bat
├── requirements.txt  # list of package dependencies
├── actual_module     # the core project code
│   ├── __init__.py
│   ├── core.py
│   └── helpers.py
├── setup.py          # package and distribution management
└── tests             # scripts related to testing your code 
    ├── __init__.py
    ├── context.py
    ├── test_advanced.py
    └── test_basic.py
```