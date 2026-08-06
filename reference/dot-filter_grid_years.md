# Filter a single grid data frame to selected years (keeps original columns)

Filter a single grid data frame to selected years (keeps original
columns)

## Usage

``` r
.filter_grid_years(df, years_keep, year_start_month = 1L)
```

## Arguments

- df:

  Data frame with a \`date\` column.

- years_keep:

  Integer vector of years (calendar or water years) to retain.

- year_start_month:

  Integer 1-12. When \> 1, uses water-year grouping.

## Value

Filtered data frame with the same columns as \`df\`.
