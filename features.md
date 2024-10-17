# Features

List of features of the project.

## List of features

- Data source: Data can be read from command line arguments, files, or standard input.
- Data output: Data can be written to files or standard output.
- Config file: The config file contains the list of headers and its properties.
  - data type: The data type of the column.
  - column name: The name of the column.
  - threshold for integers: The threshold value for the column. There will be three thresholds. If the value is greater than the upper threshold, the value shown in red, if the value is less than the lower threshold, the value shown in yellow, and if the value is between the two thresholds, the value shown in green.
  - case for strings: The case of the string. The case can be upper, lower, or title.
  - delimiter: The delimiter of the records.
  - space can be removed: If the value is true, the spaces in the string will be removed.
  - special characters can be removed: If the value is true, the special characters in the string will be removed.
  - sort order: The order of the sorting. The order can be ascending or descending.
  - date format: The format of the date. The format can be dd/mm/yyyy, mm/dd/yyyy, or yyyy/mm/dd.
  - list join: The delimiter of the list.
  - Basic statistics: The basic statistics of the column. The basic statistics can be mean, median, mode, standard deviation, variance, minimum, maximum, and count.
  - map values: The map values of the column. The map values can be the key-value pair. For example, all the values of the column will be incremented by n.
  - filter values: The records will be filtered based on the filter values. For example, all the negative values will be removed.
  - background color: The background color of the column. The background color can be red, yellow, green, blue, or white.
  - text color: The text color of the column. The text color can be red, yellow, green, blue, or white.
- Supports bootstrap color coding.
- Add icons to the column by replacing values with icons, and support font awesome icons.