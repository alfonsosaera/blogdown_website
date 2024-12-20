---
title: New Post Test
author: 'Alfonso Saera vila'
date: '2024-12-20'
slug: hi-hugo
categories: ["R"]
tags: ["R Markdown", "plot", "regression"]
---




# Including Plots - Test 2

You can also embed plots. See Figure <a href="#fig:plot">1</a> for example:


``` r
library( ggplot2 )
data.frame( x = -10:10, y = (-10:10)^2 ) |>
  ggplot( aes(x=x, y=y) ) +
  geom_point()
```

<div class="figure">
<img src="{{< blogdown/postref >}}index_files/figure-html/plot-1.png" alt="A fancy pie chart." width="672" />
<p class="caption"><span id="fig:plot"></span>Figure 1: A fancy pie chart.</p>
</div>

