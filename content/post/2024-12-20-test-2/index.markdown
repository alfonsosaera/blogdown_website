---
title: Test 2
author: 'Alfonso Saera Vila'
date: '2024-12-20'
slug: test-2
categories: ["R"]
tags: ["R Markdown", "plot", "regression"]
---




# New Post test

You can also embed plots. See Figure <a href="#fig:plot">1</a> for example:


``` r
library( ggplot2 )
data.frame( x = -10:10, y = (-10:10)^3 ) |>
  ggplot( aes(x=x, y=y), color = 'lightblue' ) +
  geom_point() +
  geom_line() +
  theme_bw()
```

<div class="figure">
<img src="{{< blogdown/postref >}}index_files/figure-html/plot-1.png" alt="A plot" width="672" />
<p class="caption"><span id="fig:plot"></span>Figure 1: A plot</p>
</div>
