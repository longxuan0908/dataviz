# MACS 40700 - Data Visualization (Spring 2017)

|  | [Dr. Benjamin Soltoff](http://www.bensoltoff.com/) |
|--------------|----------------------------------------------------|
| Email | soltoffbc@uchicago.edu |
| Office | 249 Saieh Hall |
| Office Hours | Th 2-4pm |
| GitHub | [bensoltoff](https://github.com/bensoltoff) |

* **Meeting day/time**: MW 1:30-2:50pm, Saieh Hall, Room 247
* Office hours also available by appointment

## Course description

Social scientists frequently wish to convey information to a broader audience in a cohesive and interpretable manner. Visualizations are an excellent method to summarize information and report analysis and conclusions in a compelling format. This course introduces the theory and applications of data visualization. Students will learn about theory of cognition and perception in order to understand how humans process and synthesize information in a visual medium, while also developing techniques and methods for generating rich, informative, and interactive visualizations for both data exploration and explanation. These techniques will be developed using software implementations in [R](https://www.r-project.org/) and [D3](https://d3js.org/).

### Prerequisites

Students are expected to have prior programming experience; this is not an introductory programming course and students without this experience will have significant difficulties keeping up with the material. Experience could come from completion of [MACS 30500 - Computing for the Social Sciences](http://cfss.uchicago.edu/), an alternative course on programming at UChicago or undergrad, or self-taught experience using either R or Python. Students should also be familiar with the [Git version tracking system](https://git-scm.com/) and be comfortable with the Git workflow (commit, push, pull, merge, etc.). Finally, some basic experience with probability/statistical theory (especially regression analysis) will be helpful, though not required.

## Grades

| Assignment | Points |
|------------------|--------|
| [Assignment 1](assignments/assignment-1.md) | 15 |
| Assignment 2 | 15 |
| Assignment 3 | 15 |
| Assignment 4 | 15 |
| [Final project](assignments/final-project.md) | 30 |
| Participation | 10 |
| **Total Points** | 100 |

## Disability services

If you need any special accommodations, please provide us with a copy of your Accommodation Determination Letter (provided to you by the Student Disability Services office) as soon as possible so that you may discuss with me how your accommodations may be implemented in this course.

## Readings

Readings for the course will come primarily from the following books, as well as an assortment of journal articles:

* **TA** - [Cairo, Alberto. *The Truthful Art: Data, charts, and maps for communication*. New Riders, 2016.](http://proquestcombo.safaribooksonline.com.proxy.uchicago.edu/book/databases-and-reporting-tools/9780133440492)
* **FA** - [Cairo, Alberto. *The Functional Art: An introduction to information graphics and visualization*. New Riders, 2012.](http://proquestcombo.safaribooksonline.com.proxy.uchicago.edu/book/graphic-design/9780133041187)
* **D3** - [Murray, Scott. *Interactive data visualization for the Web*. O'Reilly Media, Inc., 2013.](http://alignedleft.com/work/d3-book)
* **Munzer** - Munzner, Tamara. *Visualization analysis and design*. CRC Press, 2014.
* **R4DS** - [Wickham, Hadley and Garrett Grolemund. *R for Data Science*. O'Rielly Media, Inc., 2017.](http://r4ds.had.co.nz/)

> I recommend you purchase a copy of TA. R4DS and D3 are both available for free online, however you can also purchase a hard-copy if you prefer that medium. TA and FA are also available as ebooks through the UChicago library (follow the links above, authentication required).

## Course schedule

| Date | Day | Topic | Due dates |
|---------|-----|------------------------------------|-------------------------------------------------------|
| Mar. 27 | M | Introduction to data visualization |  |
| Mar. 29 | W | Principles of data visualization |  |
| Apr. 3 | M | Design and evaluation |  |
| Apr. 5 | W | Grammar of graphics and `ggplot2` |  |
| Apr. 10 | M | Designers vs. engineers | [Assignment 1](assignments/assignment-1.md) |
| Apr. 12 | W | Multivariate data visualization |  |
| Apr. 17 | M | Graphical perception and cognition |  |
| Apr. 19 | W | Exploratory data analysis |  |
| Apr. 24 | M | Rules of thumb | Assignment 2 |
| Apr. 26 | W | Statistical learning models |  |
| May 1 | M | Interactivity (theory) |  |
| May 3 | W | Interactivity in R |  |
| May 8 | M | Geospatial visualization | Assignment 3 |
| May 10 | W | Introduction to D3 |  |
| May 15 | M | Network visualization |  |
| May 17 | W | More D3 |  |
| May 22 | M | Text visualization | Assignment 4 |
| May 24 | W | Effective presentations |  |
| May 29 | M | No class (Memorial Day) |  |
| May 31 | W | Final project presentations | Present [final project](assignments/final-project.md) |
| June 4 | Su |  | Submit [final project](assignments/final-project.md) |

## References and Readings

All readings are required unless otherwise noted. Adjustments can be made throughout the quarter; be sure to check this repository frequently to make sure you know all the assigned readings.

1. Basic principles of visualization
    * TA Ch 1, 2, 5
1. Simple charts
    * TA Ch 1, 2, 5
1. Design and evaluation
    * TA 2-4
    * Visualizations to critique in-class on Monday
        * [Earth Temperature Timeline](https://xkcd.com/1732/)
        * [Gun Deaths in America](https://fivethirtyeight.com/features/gun-deaths/)
        * [Marriage](https://xkcd.com/1431/)
        * [The Paper Mountain](http://www.nature.com/news/the-top-100-papers-1.16224)
        * [Trump popularity](https://projects.fivethirtyeight.com/trump-approval-ratings/)
1. Grammar of graphics and `ggplot2`
    * [Wickham, Hadley. "A layered grammar of graphics." *Journal of Computational and Graphical Statistics* 19.1 (2010): 3-28.](http://www-tandfonline-com.proxy.uchicago.edu/doi/abs/10.1198/jcgs.2009.07098)
    * [R4DS Ch 1-3](http://r4ds.had.co.nz/)
1. Designers vs. engineers
    * FA Ch 3
    * [Gelman, Andrew, and Antony Unwin. "Infovis and statistical graphics: different goals, different looks." *Journal of Computational and Graphical Statistics* 22.1 (2013): 2-28.](http://www-tandfonline-com.proxy.uchicago.edu/doi/full/10.1080/10618600.2012.761137)
    * [Wickham, Hadley. "Graphical criticism: some historical notes." *Journal of Computational and Graphical Statistics* 22.1 (2013): 38-44.](http://www-tandfonline-com.proxy.uchicago.edu/doi/full/10.1080/10618600.2012.761140?src=recsys)
1. Exploratory data analysis
    * TA Ch 6-7
1. Graphical perception and cognition
    * FA Ch 5-7
    * [Cleveland, William S., and Robert McGill. "Graphical perception: Theory, experimentation, and application to the development of graphical methods." *Journal of the American statistical association* 79.387 (1984): 531-554.](http://www.jstor.org.proxy.uchicago.edu/stable/2288400)
    * [Heer, Jeffrey, and Michael Bostock. "Crowdsourcing graphical perception: using mechanical turk to assess visualization design." *Proceedings of the SIGCHI Conference on Human Factors in Computing Systems*. ACM, 2010.](http://dl.acm.org.proxy.uchicago.edu/citation.cfm?id=1753357&CFID=745610279&CFTOKEN=53601915)
    * [Spence, Ian, and Stephan Lewandowsky. "Displaying proportions and percentages." *Applied Cognitive Psychology* 5.1 (1991): 61-77.](http://onlinelibrary.wiley.com.proxy.uchicago.edu/doi/10.1002/acp.2350050106/abstract;jsessionid=E21007114F95498B3EA95F35DD6A21BF.f03t04)
    * [Siegrist, Michael. "The use or misuse of three-dimensional graphs to represent lower-dimensional data." *Behaviour & Information Technology* 15.2 (1996): 96-100.](http://web.b.ebscohost.com.proxy.uchicago.edu/ehost/detail/detail?sid=7f75c721-2db0-4d09-9a39-4c63f8cdae48%40sessionmgr103&vid=0&hid=107&bdata=JnNpdGU9ZWhvc3QtbGl2ZSZzY29wZT1zaXRl#AN=7613951&db=iih)
1. Multivariate data visualization
    * TA Ch 8-9
1. Rules of thumb
1. Statistical learning models
    * ISLR Ch 3
1. Interactivity (theory)
1. Interactivity in R
1. Geospatial visualization
    * TA Ch 10
1. Introduction to D3
    * Murray TBD
1. Network visualization
1. More D3
    * Murray TBD
1. Text visualization
1. Effective presentations
1. No class (Memorial Day)
1. Final project presentations
