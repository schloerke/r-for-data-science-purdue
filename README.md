# Purdue Seminar - R for Data Science

## Chat:

Please post comments and questions here: [Gitter](https://gitter.im/r4ds-purdue/Lobby?utm_source=share-link&utm_medium=link&utm_campaign=share-link)
 

## Schedule:

Subscribe here: [Google Calendar (that can't be embeded)](https://calendar.google.com/calendar/embed?src=4aiemu59kqid73n3dkojvt9ics%40group.calendar.google.com&ctz=America/New_York&mode=AGENDA)


Wednesdays<br/>
5:30-6:30pm <br/>
**SC 246** <br/>
02/22, 03/01, 03/08, (SPRING BREAK), 03/22, 03/29, 04/05, 04/12, 04/19, 04/26

## Topics to cover:

1. 02/15 - [ggplot2](http://r4ds.had.co.nz/data-visualisation.html); √
1. 02/22 - [github](https://desktop.github.com), [R markdown](http://r4ds.had.co.nz/r-markdown.html), [tibbles](http://r4ds.had.co.nz/tibbles.html) and [strings](http://r4ds.had.co.nz/strings.html); √
  * Github
      * Learn: https://try.github.io
      * Guides: https://guides.github.com
  * Markdown
      * Daring Fireball: https://daringfireball.net/projects/markdown/syntax
  * Regular Expressions
      * Regex Pal: http://regexpal.com.s3-website-us-east-1.amazonaws.com
1. 03/01 - [tidy data](http://r4ds.had.co.nz/tidy-data.html)√ and [data transformation](http://r4ds.had.co.nz/transform.html)√. Maybe [relational data](http://r4ds.had.co.nz/relational-data.html)
  * tidy data
    * Data structure
      * Columns are variables
      * Rows are observations
      * Data frame cells are values
    * Functions
      * split - separate one column into many columns
      * gather - merge multiple columns into a key column and value column
  * Data transformations
    * Functions
      * mutate - make a alteration to the data set
      * select - grab certain columns or remove certain columns
      * group_by - set up the data set ot be grouped by certain columns
      * summarise - get summary metrics according to the grouped columns
1. 03/08 - [functions](http://r4ds.had.co.nz/functions.html)√ and [pipes](http://r4ds.had.co.nz/pipes.html)√
1. 03/22 - [model basics](http://r4ds.had.co.nz/model-basics.html)
1. 03/29 - [web scraping](https://github.com/schloerke/presentation-2015_10_20-web_scraping/blob/master/Web%20scraping.pdf) - prior presentation
1. 04/05 - [Exploratory Data Analysis](http://r4ds.had.co.nz/exploratory-data-analysis.html)
1. User provided dataset exploration - would like to do this twice.  Please suggest datasets you'd like to explore!
1. [nested data.frames](http://r4ds.had.co.nz/many-models.html#list-columns-1) ?
1. Suggestions? Have already add some string manipulations and webscripting.



## Materials

### Books

* **R for Data Science**
    * Link: http://r4ds.had.co.nz
    * "This is the website for “R for Data Science”. This book will teach you how to do data science with R: You’ll learn how to get your data into R, get it into the most useful structure, transform it, visualise it and model it. In this book, you will find a practicum of skills for data science. Just as a chemist learns how to clean test tubes and stock a lab, you’ll learn how to clean data and draw plots—and many other things besides. These are the skills that allow data science to happen, and here you will find the best practices for doing each of these things with R. You’ll learn how to use the grammar of graphics, literate programming, and reproducible research to save time. You’ll also learn how to manage cognitive resources to facilitate discoveries when wrangling, visualising, and exploring data."
* **Advanced R**
    * Link: http://adv-r.had.co.nz
    * "This is the companion website for “[Advanced R](http://amzn.com/1466586966?tag=devtools-20)”, a book in Chapman & Hall’s R Series. The book is designed primarily for R users who want to improve their programming skills and understanding of the language. It should also be useful for programmers coming to R from other languages, as it explains some of R’s quirks and shows how some parts that seem horrible do have a positive side."
    
    
### Learn R

* ***DataCamp***: 
  * Link: https://www.datacamp.com/getting-started?step=2&track=r
  * Price: Maybe $30 a month.  Worth the price.
* ***swirl***:
  * Link: http://swirlstats.com/students.html
  * "Learn R, in R"
  * Course Descriptions: https://github.com/swirldev/swirl_courses#swirl-courses
  * Price: Free!
  * Usage:
  ```{r}
  # setup
  install.packages("swirl")
  library("swirl")
  swirl::install_course_url("https://github.com/swirldev/swirl_courses/archive/master.zip", multi = TRUE)
  
  # regular useage
  library(swirl)
  swirl()
  ```
* RStudio Resources:
  * Link: https://www.rstudio.com/online-learning/
