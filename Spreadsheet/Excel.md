# [`Microsoft Excel`](git config core.ignorecase false)

## Overview
I maintain the following file as a repository for commands and functions I write, whenever I find myself using [`Microsoft Excel`](https://products.office.com/en-us/excel).

## Functions

### Trim by keyword in text cell
```excel
=MID(B2, FIND("gmt",B2) + 7, FIND("""",B2,FIND("""",B2)-1) - FIND("""",B2) + 36)
```
