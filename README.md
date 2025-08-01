# Databricks_exercise

Import new data and merge them into an existing target table

1. A new CSV file has been imported.
The file cannot be read easily due to quotation marks. Therefore, it must first be cleaned up. 
The cleaned file is saved again as a CSV file.

2. Now the cleaned file is read in and compared with the target table.
If new rows are included, they are inserted; if identical IDs are found, the individual columns are checked for differences,
and if differences are found, this column is updated in the target table.
