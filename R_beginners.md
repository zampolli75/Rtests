We believe that the best way to learn to use a new software for data analysis is to work on solving real-world problems. You might find it hard at first, but if you like to solve this kind of problems, it means you're in the right career path.

# Scenario
We want to buy an [Alexa smart speaker](
https://www.amazon.com/s/ref=sr_nr_n_1?fst=as%3Aoff&rh=n%3A9818047011%2Ck%3Asmart+speaker&keywords=smart+speaker&ie=UTF8&qid=1522605843&rnid=2941120011) for our lab, but we cannot afford to spend more than $100.
We could collect the prices manually in a spreadsheet, but what if something change on the wepage - e.g., new products are added or the prices change? We definetely need a more systematic approach.
Thus, your task is to scrape the information of the different speakers from [Alexa smart speaker](
https://www.amazon.com/s/ref=sr_nr_n_1?fst=as%3Aoff&rh=n%3A9818047011%2Ck%3Asmart+speaker&keywords=smart+speaker&ie=UTF8&qid=1522605843&rnid=2941120011) and present some summary statistics to help us deciding which product to buy. Think about how to present the information effecively, for instance using graphs or tables. Eventually, we expect to have a clear understanding of the speakers that we can afford.

# Output

 - A document for presentation purposes. If you use R, we suggest looking into [Rmarkdown](https://rmarkdown.rstudio.com) to produce the report. However, free to use any other software (e.g., Word) to produce the final report.
 - The code you used for scraping the webpage.
 - A dataset with at least: price, product name, and URL to the product page. The .csv format is preferred.
 
 
| Product name                            | price | url                                                                                                                                                                             |
|-----------------------------------------|-------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Echo (2nd Generation) - Charcoal Fabric | 99.99 | https://www.amazon.com/all-new-amazon-echo-speaker-with-wifi-alexa-dark-charcoal/dp/B06XCM9LJ4/ref=sr_1_1?s=amazon-devices&ie=UTF8&qid=1522619060&sr=1-1&keywords=smart+speaker |

  - The code you used for the analysis/presentation of the results. In the analysis you might want to include:
      - Summary statistics (e.g., mean, max, min, median price). 
      - A bar chart of the product prices (we suggest you use [ggplot2](https://github.com/tidyverse/ggplot2))
      - Comments on your analysis and results.
      - Resources you used extensively to accomplish the challenge. It is entirely fine to use resources you find on the web as guide/inspiration for your work, but we expect you to provide the most important ones you used.

# Software

Feel free to scrape Amazon prices with the programming language you are most comfortable with. If you have never used any other programming language, we strongly suggest starting with [R](https://www.r-project.org/about.html). In the DDSLab we like it because it helps to work on a number of tasks such as data-manipulation, data-visualization, text-mining, statistical analysis, web-scraping, reporting, etc.

Follow these steps to set up R:

- Install [R](https://www.r-project.org)
- Install the [Rstudio IDE](https://www.rstudio.com). Rstudio has many features (e.g., tools for plotting or debugging) that makes working with R much easier. 
