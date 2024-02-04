
## Check for discrepancies in CSR tables and listing reports.

![](image/Picture1.png){fig-align="center" width="412"}

## Purpose / Short Description of CRV

Check for discrepancies in CSR tables and listing reports. 

# User Requirements

1.  Check for reports with undefined titles

2.  Check for missing footnote references

3.  Check for duplicate records in reports

4.  Check report creation dates

5.  Compare program file names against NAME parameter in %iniprog call

6.  Check for empty reports

7.  Check for missing %iniprog and/or %endprog calls

8.  Check SAS log files

9.  Check AE reports for discrepancies

10. Check Big N within each population group

11. Check for hardcoded libnames and formats

12. Check for reports with invalid values

13. Run study specific checks

See how to publish your own documentation in the [devops-docs-example](https://github.com/bayer-int/devops-docs-example) repository on GitHub.com.

## Subpages

- [page](page.md)
- [test/](test/index.md)
- [test/test](test/test.md)
- [test/test-1](test/test-1.md)

## Project layout

    .github/workflows   # The GitHub Actions automation.
    mkdocs.yml          # The configuration file.
    docs/
        index.md        # The documentation homepage.
        ...             # Other markdown pages, images and other files.
