# Fix up semester object for canceled and makeup classes

Fix up calendar and rd_items to account for classes that are canceled
and rescheduled for makeup.

## Usage

``` r
fixup_semester(semester)
```

## Arguments

- semester:

  A semester object returned by
  [`load_semester_db()`](https://j-magnolia.github.io/semestr/reference/load_semester_db.md).

## Value

A fixed up `semester` object.

## Examples

``` r
if (FALSE) { # \dontrun{
semester <- fixup_semester(semester)
} # }
```
