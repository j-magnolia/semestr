# Build reading, homework, and lab assignments

Build reading, homework, and lab assignments from a schedule dataframe

## Usage

``` r
build_assignments(schedule, semester, dry_run = FALSE)
```

## Arguments

- schedule:

  A schedule dataframe.

- semester:

  A semester object (list).

- dry_run:

  Don't actually write assignment files to disk.

## Value

An updated schedule dataframe
