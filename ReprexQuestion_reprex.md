# Can’t get summarywidget output as inline

I have been using the `crosstalk` package, and I am a big fan, however, I have the issue that I can\`t seem to understand how to put the output of the package in an inline code. The webpage states the following:

**The output of summarywidget is enclosed in a <span> tag so you can use it inline in text. See the Introduction for an example.**

However I made [this example](https://github.com/derek-corcoran-barrios/SummaryWidgetQuestion/blob/master/example.Rmd) shown in this repository, and published in [this rpubs](https://rpubs.com/derek_corcoran/SummaryWidget). And it can be seen that the outputs are not an inline code, as seen in this image:

![](https://i.imgur.com/uxlXnlh.png)

But when I see the result of the package [example page](https://kent37.github.io/summarywidget/index.html) it is inline:

![](https://i.imgur.com/31bUvJk.png)

But I copied exactly their code, any idea on what I am doing wrong?

<details style="margin-bottom:10px;">
<summary>
Standard output and standard error
</summary>

``` sh
-- nothing to show --
```

</details>
<details style="margin-bottom:10px;">
<summary>
Session info
</summary>

``` r
sessioninfo::session_info()
#;-) ─ Session info ───────────────────────────────────────────────────────────────
#;-)  setting  value
#;-)  version  R version 4.2.0 (2022-04-22)
#;-)  os       Ubuntu 18.04.6 LTS
#;-)  system   x86_64, linux-gnu
#;-)  ui       X11
#;-)  language (EN)
#;-)  collate  en_US.UTF-8
#;-)  ctype    en_US.UTF-8
#;-)  tz       Europe/Copenhagen
#;-)  date     2022-06-01
#;-)  pandoc   2.17.1.1 @ /usr/lib/rstudio/bin/quarto/bin/ (via rmarkdown)
#;-) 
#;-) ─ Packages ───────────────────────────────────────────────────────────────────
#;-)  package     * version date (UTC) lib source
#;-)  cli           3.3.0   2022-04-25 [1] CRAN (R 4.2.0)
#;-)  crayon        1.5.1   2022-03-26 [1] CRAN (R 4.2.0)
#;-)  curl          4.3.2   2021-06-23 [1] CRAN (R 4.2.0)
#;-)  digest        0.6.29  2021-12-01 [1] CRAN (R 4.2.0)
#;-)  ellipsis      0.3.2   2021-04-29 [1] CRAN (R 4.2.0)
#;-)  evaluate      0.15    2022-02-18 [1] CRAN (R 4.2.0)
#;-)  fansi         1.0.3   2022-03-24 [1] CRAN (R 4.2.0)
#;-)  fastmap       1.1.0   2021-01-25 [1] CRAN (R 4.2.0)
#;-)  fs            1.5.2   2021-12-08 [1] CRAN (R 4.2.0)
#;-)  glue          1.6.2   2022-02-24 [1] CRAN (R 4.2.0)
#;-)  highr         0.9     2021-04-16 [1] CRAN (R 4.2.0)
#;-)  htmltools     0.5.2   2021-08-25 [1] CRAN (R 4.2.0)
#;-)  httr          1.4.2   2020-07-20 [1] CRAN (R 4.2.0)
#;-)  knitr         1.39    2022-04-26 [1] CRAN (R 4.2.0)
#;-)  lifecycle     1.0.1   2021-09-24 [1] CRAN (R 4.2.0)
#;-)  magrittr      2.0.3   2022-03-30 [1] CRAN (R 4.2.0)
#;-)  mime          0.12    2021-09-28 [1] CRAN (R 4.2.0)
#;-)  pillar        1.7.0   2022-02-01 [1] CRAN (R 4.2.0)
#;-)  pkgconfig     2.0.3   2019-09-22 [1] CRAN (R 4.2.0)
#;-)  png           0.1-7   2013-12-03 [1] CRAN (R 4.2.0)
#;-)  purrr         0.3.4   2020-04-17 [1] CRAN (R 4.2.0)
#;-)  R.cache       0.15.0  2021-04-30 [1] CRAN (R 4.2.0)
#;-)  R.methodsS3   1.8.1   2020-08-26 [1] CRAN (R 4.2.0)
#;-)  R.oo          1.24.0  2020-08-26 [1] CRAN (R 4.2.0)
#;-)  R.utils       2.11.0  2021-09-26 [1] CRAN (R 4.2.0)
#;-)  R6            2.5.1   2021-08-19 [1] CRAN (R 4.2.0)
#;-)  reprex        2.0.1   2021-08-05 [1] CRAN (R 4.2.0)
#;-)  rlang         1.0.2   2022-03-04 [1] CRAN (R 4.2.0)
#;-)  rmarkdown     2.14    2022-04-25 [1] CRAN (R 4.2.0)
#;-)  rstudioapi    0.13    2020-11-12 [1] CRAN (R 4.2.0)
#;-)  sessioninfo   1.2.2   2021-12-06 [1] CRAN (R 4.2.0)
#;-)  stringi       1.7.6   2021-11-29 [1] CRAN (R 4.2.0)
#;-)  stringr       1.4.0   2019-02-10 [1] CRAN (R 4.2.0)
#;-)  styler        1.7.0   2022-03-13 [1] CRAN (R 4.2.0)
#;-)  tibble        3.1.7   2022-05-03 [1] CRAN (R 4.2.0)
#;-)  utf8          1.2.2   2021-07-24 [1] CRAN (R 4.2.0)
#;-)  vctrs         0.4.1   2022-04-13 [1] CRAN (R 4.2.0)
#;-)  withr         2.5.0   2022-03-03 [1] CRAN (R 4.2.0)
#;-)  xfun          0.31    2022-05-10 [1] CRAN (R 4.2.0)
#;-)  xml2          1.3.3   2021-11-30 [1] CRAN (R 4.2.0)
#;-)  yaml          2.3.5   2022-02-21 [1] CRAN (R 4.2.0)
#;-) 
#;-)  [1] /home/derek/R/x86_64-pc-linux-gnu-library/4.2
#;-)  [2] /usr/local/lib/R/site-library
#;-)  [3] /usr/lib/R/site-library
#;-)  [4] /usr/lib/R/library
#;-) 
#;-) ──────────────────────────────────────────────────────────────────────────────
```

</details>
