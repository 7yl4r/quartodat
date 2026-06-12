# quartodat
Document your dataset with a quarto-powered website.

# Overview
Pages for the website can be generated from `.html`, `.md`, `.qmd` or `.ipynb` files.
Edit the `_quarto.yml` file to configure the website.

The following example files are included:

* `README.md` - This file. It is not added to the website. This is the developer-facing entry point.
* `index.qmd` - This is the homepage of the website. It is the first page users will see.
* TODO: `notebooks/load-data.qmd` - This is an example notebook that loads data and displays it in the website.
* TODO: `notebooks/load-data.ipynb` - This is the same as `load-data.qmd`, but in IPython format.

# Usage
## Website Deployment
It is recommended to deploy your quarto website to GitHub pages using the quarto CLI:

```bash
quarto publish
```

----------------------------------------------------------------------------

# Attribution
This project is powered by the [quartodat template](https://github.com/7yl4r/quartodat).


