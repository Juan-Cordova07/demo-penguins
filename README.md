# demo-penguins
Demo data set: Example from google data analytics course

---
title: "Demo: ggplot_hook"
author: "Juan Cordova"
date: "2/18/2022"
output: github_document
---
# Demo data set: 

### Example from google data analytics course

## Setting up my environment
Notes: Setting up my R environment by loading the 'tidyverse' and 'palmerpenguins' packages

```{r loading packages, message=FALSE, warning=FALSE}
install.packages("tidyverse")
install.packages("ggplot2")
install.packages("palmerpenguins")
library(tidyverse)
library(ggplot2)
library(palmerpenguins)
```

# Visualizations

### Creating a visualization
* Comparison between penguin's flipper length and body mass

```{r mas tipos de graficas, message=FALSE, warning=FALSE}
ggplot(data= penguins) + 
  geom_smooth(mapping = aes(x= flipper_length_mm, y= body_mass_g))
```


