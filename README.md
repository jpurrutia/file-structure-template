.
├── Makefile                        --- A series of scripts used to build the package
├── Module                          --- Module, the main body of package lives here
│   ├── __init__.py                 --- Initialize the module and import the sub-modules
│   ├── helper_functions            --- Sub folder, contains helper functions
│   │   ├── __init__.py             --- Initialize the sub-module
│   │   └── function.py             --- A Script included in the package
│   └── tools                       --- Inner folder contains various scripts included in the package
│       ├── __init__.py             --- Initialize the sub-module
│       └── tool.py                 --- A Script included in the package
├── README.md                       --- A brief introduction of the library
├── buildspec.yml                   --- File used to direct codebuild actions
├── environment.yml                 --- File used to build virtual environments for package
├── setup.py                        --- File containing the library build instructions and various dependencies
└── tests                           --- Test cases for the package
    └── test_tool.py                --- pytest script that tests toop.py file


