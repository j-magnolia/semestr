# Build a lab assignment

Build a lab assignment: Generate an `.Rmd` file for a lab assignment web
page and PDF handout.

## Usage

``` r
build_lab_assignment(schedule, date, cal_entry, semester, dry_run = FALSE)
```

## Arguments

- schedule:

  A schedule data frame.

- date:

  The date of the lab.

- cal_entry:

  A calendar entry for the lab session.

- semester:

  A list of data for the semester, from the database.

- dry_run:

  Don't actually write assignment files to disk.

## Value

An updated schedule data frame
