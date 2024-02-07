# Dynamic Programming Volume 1

Public repo for the textbook **Dynamic Programming Volume 1** by [Thomas J.
Sargent](http://www.tomsargent.com/) and [John
Stachurski](https://johnstachurski.net/).

| Folder | Description |
|--------|-------------|
| website | HTML files that build the website |
| code-book | jupyter-book powered code-book as a companion to the book |
| pdf | PDF of the book |

## PDF

The PDF is available in `pdf/dp.pdf`

Comments and feedback are very welcome.
The easiest way to provide feedback is to open an issue above.

## Codebooks

> The repo also contains all of the Julia and Python code found in the code snippets within
> the textbook, as well as Julia and Python code to reproduce all figures.

The repo contains a Jupyter Book with all code and figures used in the book. To build it locally, 

1. Clone the repo
2. Create an environment using `environment.yml`
3. You will have to install Julia 1.9 if you haven't already (Note: There is no Julia version on Conda for Windows systems).
4. Run `python3 create_code_book.py` from the root directory of the repo. This should take a few minutes to finish running.

Figures generated by the Julia code can be found in the `./code-book/figures/` folder.

To contribute to the codebook, 

1. Edit the scripts in `source_code_jl/` and `source_code_py/`.
2. Edit the chapter_meta dictionaries in `create_code_book.py` to 
- include or remove scripts
- change the order of the scripts
- change function calls
3. Run `create_code_book.py` to generate the codebook.