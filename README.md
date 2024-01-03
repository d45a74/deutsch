# My German notes

[GitHub page](https://d45a74.github.io/deutsch/)

## Markdown as website

[Mkdocs](https://squidfunk.github.io/mkdocs-material/publishing-your-site/)

- [admonitions](https://squidfunk.github.io/mkdocs-material/reference/admonitions/#supported-types)
- [formatting](https://squidfunk.github.io/mkdocs-material/reference/formatting/#usage)

``` bash
 docker volume create --name mkdocs -d local -o type=none -o o=bind -o device="$PWD"
 docker run --rm -it -p 8000:8000 -v mkdocs:/docs squidfunk/mkdocs-material
```

## By week

```mermaid
xychart-beta
    title "By week"
    x-axis "day of week" [monday, tuesday, wednesday, thurthday, friday, saturday, sunday]
    y-axis "distance" 0 --> 40
    bar [0,7.23]
    line [5.53, 11.06, 16.59, 22.12, 27.65, 33.18, 38.71]
```

## By month

```mermaid
xychart-beta
    title "By month"
    x-axis [jan, feb, mar, apr, may, jun, jul, aug, sep, oct, nov, dec]
    y-axis "distance" 0 --> 2024
    bar [120, 350]
    line [171.43, 331.8, 503.23, 669.13, 840.56, 1000, 1200, 1370, 1500, 1670, 1790, 2024]
```
