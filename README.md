Demo: ggplot_hook
================
Juan Cordova
2/18/2022

# Demo data set:

### Example from google data analytics course

## Setting up my environment

Notes: Setting up my R environment by loading the ‘tidyverse’ and
‘palmerpenguins’ packages

``` r
library(tidyverse)
library(ggplot2)
library(palmerpenguins)
```

# Visualizations

### Creating a visualization

-   Comparison between penguin’s flipper length and body mass

``` r
ggplot(data= penguins) + 
  geom_smooth(mapping = aes(x= flipper_length_mm, y= body_mass_g))
```

![](ggplot_hook_notes_files/figure-gfm/mas%20tipos%20de%20graficas-1.png)<!-- -->
