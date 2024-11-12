# Documenting Projects Using Markdown 
**Author:** Mike Colbert

**Last update:** 2024-11-11 (Created: 2024-11-11)

**Description:** How to use Markdown for writing documentation for GitHub and Python notebooks (.ipynb). 

---




## Documenting a directory structure
Adapted from https://github.com/jamessizeland/python-analytics-template

```text

Project Root (Repository name)
    │
    ├── README.md          <- The top-level README for developers using this project.
    │
    ├── data
    │   ├── README.md      <- The top-level README for developers using this project.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── notebooks          
    │   ├── README.md      <- The top-level README for developers using this project.
    │   │ 
    │   └── *.ipynb        <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── code               <- Source code for use in this project.
    │   └── .py            <- Makes src a Python module
    │ 
    ├── assets             <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── *.*            <- Generated graphics and figures to be used in reporting
    │
    ├── artifacts          <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── *.*            <- Generated graphics and figures to be used in reporting
    │
    ├── .pre-commit-config.yaml    <- Source code for use in this project.
    │
    └── .gitignore         <- The Python requirements and development experience configuration file

```

**Notes:** 

This documentation uses Unicode characters that you can copy and paste directly into your Markdown file. Markdown does not provide a built-in way to generate these symbols, but by copying them, you can include them as part of your text.  
  
Here are the commonly used tree symbols you can copy:  
  
``` ├── ``` Branch symbol  
``` └── ``` End of branch symbol  
``` │ ``` Vertical line to show continuation  
  
These have the best appearance when used as a monospaced font. To get a monospaced font in Markdown, insert the documentation block in a code fence (three backticks).  
  
```text
\`\`\`
Project-Root/
├── README.md
├── pyproject.toml
├── src/
│   ├── main.py
│   ├── utils.py
│   └── modules/
│       ├── module1.py
│       └── module2.py
├── tests/
│   ├── test_main.py
│   └── test_utils.py
└── requirements.txt
\`\`\`
```


## Including alert boxes




