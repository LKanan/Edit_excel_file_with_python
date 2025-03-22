# Edition of an excel file with python

#### 1. Installation and importation of `openpyxl` package
- To install the package, run the following command in your terminal:
`pip install openpyxl`
- To import the package in your python script, use the following line:
`import openpyxl`

#### 2. Some tips

```python
# to open a workbook
table = openpyxl.load_workbook("file_name.xlsx")
# To select a sheet
sheet = table.active
# To iterate over the rows
for row in sheet.iter_rows():
    row0 = row[0].value
    row1 = row[1].value
```