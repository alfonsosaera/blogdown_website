---
title: Scheduled Post
author: 'Alfonso Saera Vila'
date: '2025-01-01'
slug: scheduled-post
categories: ["R"]
tags: ["R Markdown", "plot", "regression"]
publishdate: '2025-01-01'
---




# Scheduled post

Including a Figure <a href="#fig:plot">1</a>.


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

