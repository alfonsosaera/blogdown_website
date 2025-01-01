---
title: Scheduled Post 3
author: Alfonso Saera Vila
date: '2024-12-31'
slug: scheduled-post-3
categories:
  - R
tags:
  - R Markdown
  - plot
  - regression
publishdate: '2024-12-31'
---



# Scheduled post

This post is scheduled to be published in the day before it was created.
Includes a Figure <a href="#fig:plot">1</a> generated from code


``` r
library( ggplot2 )
data.frame( x = -10:10, y = (-10:10)^2 ) |>
  ggplot( aes(x=x, y=y) ) +
  geom_point()
```

<div class="figure">
<img src="{{< blogdown/postref >}}index_files/figure-html/plot-1.png" alt="A fancy plot." width="672" />
<p class="caption"><span id="fig:plot"></span>Figure 1: A fancy plot.</p>
</div>

