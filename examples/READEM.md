# Examples

Jupyter notebooks examples for each of the aquaveo libraries.

## Adding Examples
To add an example to the lists

- Add a zip with the ipynb file and any other dependencies
- Convert the ipynb to an html file and add it
-- `jupyter nbconvert --to html "notebook.pynb"`
- Add a row to the html table for the new tutorial
                <!-- 
                      One Table row for each example for the library
                      When you update an example notebook you must regenerate the html
                      `jupyter nbconvert --to html "notbook.ipynb`
                -->