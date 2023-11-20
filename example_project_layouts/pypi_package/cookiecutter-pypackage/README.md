
https://github.com/waynerv/cookiecutter-pypackage/

https://waynerv.github.io/cookiecutter-pypackage

```bash
.
├── .bumpversion.cfg
├── .editorconfig
├── .git
│   ├── HEAD
│   ├── config
│   ├── description
│   ├── hooks
│   │   ├── applypatch-msg.sample
│   │   ├── commit-msg.sample
│   │   ├── fsmonitor-watchman.sample
│   │   ├── post-update.sample
│   │   ├── pre-applypatch.sample
│   │   ├── pre-commit
│   │   ├── pre-commit.sample
│   │   ├── pre-merge-commit.sample
│   │   ├── pre-push.sample
│   │   ├── pre-rebase.sample
│   │   ├── pre-receive.sample
│   │   ├── prepare-commit-msg.sample 
│   │   ├── push-to-checkout.sample
│   │   └── update.sample
│   ├── info
│   │   └── exclude
│   ├── objects
│   │   ├── info
│   │   └── pack
│   └── refs
│       ├── heads
│       └── tags
├── .github
│   ├── ISSUE_TEMPLATE.md             # example template to use for submitting an issue on github
│   └── workflows
│       ├── dev.yml
│       ├── preview.yml
│       └── release.yml
├── .gitignore                        # tells git which files must not be source-controlled
├── .pre-commit-config.yaml           # pre-commit settings 
│                                     #     "pre-commit" is code run prior to commiting code to git
│                                     #     e.g. abandon the commit if code fails automated quality check
├── CHANGELOG.md                      # keeps a history of package version changes
├── CONTRIBUTING.md                   # information for users wanting to contribute to the package
├── LICENSE
├── README.md                         # root project documentation (first thing new user will read)
├── docs                              # project documentation
│   ├── api.md
│   ├── changelog.md                  # an automatic copy of CHANGELOG.md in the root project directory
│   ├── contributing.md               # an automatic copy of CONTRIBUTING.md in the root project directory
│   ├── index.md                      # an automatic copy of README.md in the root project directory
│   ├── installation.md               
│   └── usage.md
├── makefile                          # defines runnable parts of the project
│                                     #     format, lint, coverage, clean etc.
├── mkdocs.yml                        # settings control automatic generation of documentation
│                                     #     (this uses the mkdocstrings package)
├── my_project_name                   # folder containing the core project code
│   ├── __init__.py
│   ├── cli.py                        # example command-line project script
│   └── my_project_name.py            # main project entrypoint script 
├── pyproject.toml                    # python project settings file (controls package build)                      
├── setup.cfg                           
└── tests                             # scripts related to testing the code 
    ├── __init__.py
    └── test_my_project_name.py
```