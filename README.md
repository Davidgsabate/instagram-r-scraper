Instagram R scraper
=========

Scrape Instagram using the [instagram-java-scraper](https://github.com/floresfdev/instagram-java-scraper) Java library in R.

Based on the [project](https://github.com/postaddictme/instagram-java-scraper) of [postaddictme](https://github.com/postaddictme).


### Dependencies

To run Java applications you need the [Java Runtime Environment](http://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html).

To execute Java code in R you need to install the package [rJava](https://cran.r-project.org/web/packages/rJava/index.html) from CRAN:

```r
install.packages("rJava")
```


### Instructions

1) Configure the settings at the top of the script `scraper.R`:

```r
## User account to scrape
user_account <- "berlinphil"

## Max number of posts to retrieve
media_count <- as.integer(100)
```

2) Run the script:

```r
source("scraper.R")
```

3) Find the output datasets in the `./dataout/` directory.