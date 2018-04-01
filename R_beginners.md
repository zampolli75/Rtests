We believe that the best way to approach a new software or programming language is to challenge yourself to solve a problem. You might find it hard at first, but if you like you solve this kind of problems it means you're in the right career path.

# Challenge
We want to buy an Alexa smart speaker for our lab. However, due to the many different products that Amazon is offering (e.g., Echo Dot, Echo, Amazon Tap) we are not able to agree on which to buy. Our boss told us that we are free to choose whatever speaker we want as long as the price does not exceed $100.
Since we like to adopt a systematic approach to all we do, we challenge you to scrape the prices of the different Alexa speaker from the Amazon website and present some summary statictics and compare nicely the different product prices. From the chart we will ultimately expect to have a clear view of the Amazon devices we can afford.

# Steps
In the DDS Lab we love [R](https://www.r-project.org/about.html). We use the R software for a variety of activities, from data-manipulation, data-visualization, text-mining, statistical analysis, web-scraping, reporting, and many more. Following, we will indicate some steps that will guide you in the accomplishment of the taks using the R language. Feel free to use the programming language you are most confortable with, but if you have never used any other programming language we strongly suggest you to start with R.

- Install [R](https://www.r-project.org)
- Install the [Rstudio IDE](https://www.rstudio.com). Rstudio has many features (e.g., tools for plotting or debugging) that makes working with R much easier. 
- Download into R the [Amazon webpage](
https://www.amazon.com/s/ref=sr_nr_n_1?fst=as%3Aoff&rh=n%3A9818047011%2Ck%3Asmart+speaker&keywords=smart+speaker&ie=UTF8&qid=1522605843&rnid=2941120011) with the information about the Alexa devices. We suggest you to use the [rvest](https://github.com/hadley/rvest) R library to scrape the information.
- Extract the price, title, and url linked to the title for each Alexa product present in the webpage.

You should bould a table that looks like this:
| title                                   | price | url                                                                                                                                                                             |
|-----------------------------------------|-------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Echo (2nd Generation) - Charcoal Fabric | 99.99 | https://www.amazon.com/all-new-amazon-echo-speaker-with-wifi-alexa-dark-charcoal/dp/B06XCM9LJ4/ref=sr_1_1?s=amazon-devices&ie=UTF8&qid=1522619060&sr=1-1&keywords=smart+speaker |

- Perform some summary statictics of the data. For example, mean, max, min, media price. Feel free to use whatever you feel more adapt to visualize this data (e.g., table, boxplot).
- Plot a barchart of the product prices. Use the y axis to indicate the product price, and in the x axis indicate the product name. We suggest you to use the [ggplot2](https://github.com/tidyverse/ggplot2) to produce the chart.
- Produce a report where you **comment on your findings** the include the table with all the Alexa products, the summary statistics, and the barchart. We suggest you to use [Rmarkdown](https://rmarkdown.rstudio.com) to produce the report. However, feel free to use any other software (e.g., Word). 

