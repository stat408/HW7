# HW7


Please use D2L to turn in both the Word or PDF output and your R Markdown file in.

### Q1. (5 points)
You have been made the official statistical consultant to the Space Jam basketball team. Data is stored in the framework below. Where fmg.fga are field goals (baskets) made and field goals attempted. Similarly ftm.fta is field goals made and field goals attempted. Specifically Bugs Bunny attempted 14 field goals and made 5 of them.


```
fgm.fga <- c('11-14','4-9','5-14')
ftm.fta <- c('8-11','0-1','1-5')
hoops <- data.frame(Name = c('Michael Jordan','Tasmanian Devil','Bugs Bunny'),fgm.fga,ftm.fta)
library(knitr)
kable(hoops)
```


Implement a process to extract the number of baskets made (fgm) for each player. For full credit, your approach should also work for a very large dataset (meaning you can't manually extract the three values).

### Q2. (12 points)
Revisting the graphic from Lab 2...
Download the Seattle Housing dataset, available at: [http://math.montana.edu/ahoegh/teaching/stat408/datasets/SeattleHousing.csv](http://math.montana.edu/ahoegh/teaching/stat408/datasets/SeattleHousing.csv).

#### a. (4 points)
Using base R plots, create ~~two~~ one figure~~swith at least one~~ showing the relationship between that ~~two~~ variable ~~in the data set with the~~ and housing price.

Summarize the take away points from your figure. These summaries should be 3-4 sentences and provide all of the context for your graphics so that an outside observer could understand the story you are illustrating.


#### b. (4 points)
Using ggplot2, create ~~two~~ one figure~~swith at least one~~ showing the relationship between that ~~two~~ variable ~~in the data set with the~~ and housing price.

Summarize the take away points from your figures. These summaries should be 3-4 sentences and provide all of the context for your graphics so that an outside observer could understand the story you are illustrating.
