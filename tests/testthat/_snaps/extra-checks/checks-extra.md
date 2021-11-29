## Checks for [pkgstats (v9.9)](https://github.com/ropensci-review-tools/pkgstats)

git hash: [](https://github.com/ropensci-review-tools/pkgstats/tree/)

- :heavy_check_mark: Package name is available
- :heavy_check_mark: has a 'CITATION' file.
- :heavy_multiplication_x: Package depends on the following obsolete packages: [blah]
- :heavy_multiplication_x: does not have a 'codemeta.json' file.
- :heavy_multiplication_x: does not have a 'contributing' file.
- :heavy_check_mark: uses 'roxygen2'.
- :heavy_check_mark: 'DESCRIPTION' has a URL field.
- :heavy_check_mark: 'DESCRIPTION' has a BugReports field.
- :heavy_multiplication_x: Package has no HTML vignettes
- :heavy_multiplication_x: These functions do not have examples: [pkgstats_from_archive.Rd].
- :heavy_check_mark: Package has continuous integration checks.
- :heavy_multiplication_x: Package contains unexpected files.

**Important:** All failing checks above must be addressed prior to proceeding

Package License: GPL-3

---


### 1. Statistical Properties

This package features some noteworthy statistical properties which may need to be clarified by a handling editor prior to progressing.

<details>
<summary>Details of statistical properties (click to open)</summary>
<p>

The package has:

- code in C++ (9% in 3 files) and R (91% in 19 files)
- 1 authors
- no  vignette
- no internal data file
- 9 imported packages
- 11 exported functions (median 43 lines of code)
- 120 non-exported functions in R (median 21 lines of code)
- 12 R functions (median 16 lines of code)

---

Statistical properties of package structure as distributional percentiles in relation to all current CRAN packages
The following terminology is used:
- `loc` = "Lines of Code"
- `fn` = "function"
- `exp`/`not_exp` = exported / not exported

The final measure (`fn_call_network_size`) is the total number of calls between functions (in R), or more abstract relationships between code objects in other languages. Values are flagged as "noteworthy" when they lie in the upper or lower 5th percentile.

|measure                 | value| percentile|noteworthy |
|:-----------------------|-----:|----------:|:----------|
|files_R                 |    19|       77.9|           |
|files_src               |     3|       82.9|           |
|files_vignettes         |     0|        0.0|TRUE       |
|files_tests             |     7|       83.7|           |
|loc_R                   |  2698|       88.6|           |
|loc_src                 |   277|       29.5|           |
|loc_tests               |   266|       58.4|           |
|num_vignettes           |     0|        0.0|TRUE       |
|n_fns_r                 |   131|       78.1|           |
|n_fns_r_exported        |    11|       45.5|           |
|n_fns_r_not_exported    |   120|       82.1|           |
|n_fns_src               |    12|       83.7|           |
|n_fns_per_file_r        |     4|       52.3|           |
|n_fns_per_file_src      |     4|       36.9|           |
|num_params_per_fn       |     1|        1.1|TRUE       |
|loc_per_fn_r            |    23|       77.1|           |
|loc_per_fn_r_exp        |    43|       76.8|           |
|loc_per_fn_r_not_exp    |    22|       79.5|           |
|loc_per_fn_src          |    16|       61.3|           |
|rel_whitespace_R        |    19|       88.1|           |
|rel_whitespace_src      |    24|       85.5|           |
|rel_whitespace_tests    |    27|       85.0|           |
|doclines_per_fn_exp     |    31|       34.6|           |
|doclines_per_fn_not_exp |     0|        0.0|TRUE       |
|fn_call_network_size    |   104|       77.8|           |

---

</p></details>


### 1a. Network visualisation

Click to see the [interactive network visualisation of calls between objects in package](network.html)

---

### 2. `goodpractice` and other checks

('goodpractice' not included with these checks)

---

### 3. Other Checks


:heavy_multiplication_x: Package contains the following unexpected files:

- a
- b


:heavy_multiplication_x: Package contains the following (potentially) obsolete packages:

- sp
- rgdal


See our [Recommended Scaffolding](https://devguide.ropensci.org/building.html?q=scaffol#recommended-scaffolding) for alternatives.


---

<details>
<summary>Package Versions</summary>
<p>

|package  |version   |
|:--------|:---------|
|pkgstats |42    |
|pkgcheck |42    |

</p>
</details>