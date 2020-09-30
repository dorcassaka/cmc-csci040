# HW 2: Visualizing interesting datasets

![comic](convincing.png)

**Description:** 
You will perform a simple data visualization on a dataset of your choice and create a webpage that describes the results.

**Due:** 
Sunday, 10 October, midnight

**Learning objectives:**

1. complete a python project on your own
1. integrate python knowledge with HTML knowledge
1. understand how python allows more advanced data analysis than tools like excel

## Instructions

1. Find two datasets that are interesting to you, and download them.
   Good places to look for datasets include:

    1. https://github.com/jdorfman/awesome-json-datasets

    1. https://catalog.data.gov/dataset?res_format=JSON

    1. http://data.un.org/

   You may use any dataset of your choosing, but if you work closely with another student, you must not use the same datasets as that student.

   Some datasets are in CSV format instead of JSON format.
   CSV files are even easier to work with than JSON files,
   and [the book has a whole chapter of examples](https://automatetheboringstuff.com/chapter14/).

1. Generate two plots, one from each of your datasets.  
   Your plots may be any type of plot that is appropriate for your data (e.g. line chart, bar chart, scatter chart, etc.),
   but least one of your plots must contain two data sources (e.g. two different lines in a line graph, two different sets of bars in a bar chart).
   The plots should have properly labeled x and y axes, and a legend (only needed for the plot containing multiple data sources).
   Additionally, the tick labels for both the x and y axes should appear in a reasonable order (e.g. sorted),
   and they must be legible.
   See the [matplotlib samples library](https://matplotlib.org/3.1.1/tutorials/introductory/sample_plots.html) for examples of well formatted plots.

   Two examples of acceptable plots are:

   <img src=trump_bar.png>

   <img src=trump_line1.png>

   An example of an unacceptable plot is:

   <img src=trump.png>

1. Generate a webpage in HTML that displays both of your plots.
   The webpage should:

    1. Use appropriate tile, h1, and p tags (you may use other tags to arrange the layout, but are not required to)
    
    1. For each plot: 
    
        1. You should have a short 2-5 sentence description that describes the data you plotted

        1. The description should include a link to the original data source

    1. Also include a link to this project webpage on your webpage

1. Upload your webpage to github.
   Upload a link to your webpage and your python code for generating the plots to sakai.

## Grading rubric

Each plot is worth 4 pts.

Your HTML page is worth 2 pts.

## Extra credit

You can receive 1 point of extra credit if you use the mpld3 extension to matplotlib to generate interactive html plots and include those in your webpage.
See the [mpld3 examples library](https://mpld3.github.io/examples/index.html) for examples of how to do this.
