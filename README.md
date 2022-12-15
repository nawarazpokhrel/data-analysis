# Learning Notes

## Drop in pandas 
### syntax
`df.drop(["column_name"],axis)`

Remove rows or columns by specifying label names and corresponding axis, or by specifying directly index or column names. When using a multi-index, labels on different levels can be removed by specifying the level. 

`axis{0 or ‘index’, 1 or ‘columns’}, default 0`
Whether to drop labels from the index (0 or ‘index’) or columns (1 or ‘columns’).


# Describe In pandas

Descriptive statistics include those that summarize the central tendency, dispersion and shape of a dataset’s distribution, excluding NaN values.

## syntax
`df.describe()`

