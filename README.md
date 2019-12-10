# BA 505 Final Project - Team Baseball
## Fall 2019
__This is our final project document.__
__Project.ipynb is our final project that we will use for our presentation.__
__2017_MLB_Data.csv is our dataset.__

## Overview
As a group we constructed different types of analysis from the 2017 data sheet to find some sort of conclusion. We used several types of graphs to visually display our data to help us make an educated decision about our statistics. We split our original data set into two subsets so we would be able to compare Houston Astros batting stats to the batting performance of the league in order to give a more accurate representation of our findings.

## Objectives
Use data from 2017 for all pitches thrown and hit in Minute Maid Park to see a connection between sign stealing scandal and performance. We want to provide sufficient evidence that the Houston Astros have a higher success rate at bat because they are aware of the pitch that is being thrown. One of the main goals for this project was to show that as a group we have mastered the following skills, Python, Pandas, Matplotlib, Jupyter, and GitHub, and create a fully functioning project using all of these tools. 


## Project Requirements
* **All work must be your own.** It is your responsibility to demonstrate the unique contributions made by your work. You are also expected to thoroughly understand and be able to explain any work done by your teammates.
* **Academic honesty policies and scholarship norms apply.** All relevant previous work and data sources must be properly cited.
* **The analysis must be fully reproducible, even and especially with new data.** This is to be professional work, subject to prevalent standards. Suggestion: create a separate module to load/clean/integrate your data. That will allow us to test and reuse your work in other projects.
* **Descriptive analytics (as in QA400) are sufficient.** However, there is no need to constrain your work. If you can apply forecasting or decision modeling, then feel free to do so.
* **The analysis should stand on its own.** All work will be posted a *public* repository created via GitHub Classroom. You will be asked to present your work on the final day of class, but the analysis itself should be readily accessible and understandable from your GitHub repositories without installing any additional software.
* **Project size and scope should be sufficient to demonstrate mastery of Python, Pandas, and Matplotlib.** At a minimum the datasets used should have at least 10K records with a dozen or more fields. Further, there should be some opportunity for you to filter/reduce/analyze the data using Pandas . If the work could just as easily be performed by an undergraduate in Excel, then keep looking for another project.
* **All data used must be posted in your GitHub repository.** If you are borrowing data from Kaggle, then please cite the original source in your `Readme.md` file. It should be possible for anyone to reproduce your work, including collecting the data from original sources.
* **Document your work.** At a minimum, each analytical step (code cell) should be documented with markdown cells above and below stating your intention (_above_) and interpretation (_below_). Your notebooks should tell a story about the data. **One should be able to read the rendered notebook in GitHub (without running your code or your presentation) and know exactly what you did, why you did it, and why we should care about the results.**

## Process  

1. **Watch and learn.** Study the following tutorial, which sets the bar for what constitutes A-level work in this course:  
[Reproducible Data Analysis in Jupyter](https://jakevdp.github.io/blog/2017/03/03/reproducible-data-analysis-in-jupyter)  
The tutorial is in 10 parts, with some of the more advanced work in the second half. At a minimum, your project should use the practices demonstrated in videos 1-5. To get the best grade, however, try something more advanced like the practices shown in videos 6-10.  
2. **Survey the best examples you can find.** One very convenient place to look is [Kaggle](https://kaggle.com), which has submissions from numerous data analytics competitions. Here a few particularly engaging Kaggle submissions to study:
  * [asindico//from-exploration-to-prediction](https://www.kaggle.com/asindico/from-exploration-to-prediction)
  * [anokas/exploratory-data-analysis-4 2017](https://www.kaggle.com/anokas/exploratory-data-analysis-4)
  * [sudalairajkumar/simple-exploration-notebook-5](https://www.kaggle.com/sudalairajkumar/simple-exploration-notebook-5)
  * [pmarcelino/comprehensive-data-exploration-with-python](https://www.kaggle.com/pmarcelino/comprehensive-data-exploration-with-python)
  * [This](https://github.com/fairfield-university-ba505-fall2018/final-project-filip-s-angels) is an example of last year's student project in this course. You should use that as the reference for an excellent project. __NOTE__ that two of the three students in this group got hired because of this project.

      While some are more "finished" than others, you'll find that each tells a story with data. Try to learn to do that.  

3. **Find a suitable data source.** We found and collected the data used in this project at baseballsavant.com. They provide in depth statistics for all plays that occur in MLB games. We filtered the data by pitches thrown at Minute-Made Park in 2017 and then downloaded it into a csv to be uploaded into JupyterLab. 
    Additionally, we did some outside research to help us improve on our visual analysis. They are listed here:
    [DrawingFromData](https://www.drawingfromdata.com/how-to-rotate-axis-labels-in-seaborn-and-matplotlib)
    [CMD](https://cmdlinetips.com/2018/02/how-to-subset-pandas-dataframe-based-on-values-of-a-column/)
    [Seaborn](https://seaborn.pydata.org/tutorial/categorical.html)
    [Pandas-Seaborn](https://chrisalbon.com/python/data_wrangling/pandas_with_seaborn/)
    [Pandas](https://pandas.pydata.org/pandas-docs/stable/reference/frame.html#plotting)
    [TowardsDataScience](https://towardsdatascience.com/a-guide-to-pandas-and-matplotlib-for-data-exploration-56fad95f951c)

4. **Develop a few research questions that you'd like to answer based on the data.** After carefully collecting and cleaning the data, we developed research questions that could help us attempt to prove our main point: that the Houston Astros gained a significant advantage over opponents by stealing signs throughout the 2017 season. We based our research questions off of key attributes such as pitch_name, launch_speed, and launch_angle to see how Astros’ players fared against some of the other top players in the league.
5. **Do some analysis**. We were able to answer 3 of our research questions through the use of visualizations in Pandas. We visualized some of the key attributes and how they differed between Astros players and the rest of the league. We looked for any outstanding differences between these visualizations and were able to find that there was some clear statistical evidence that they had an edge over their opponents, but our findings are not sufficient enough to definitively prove that they had an advantage over their opponents because of sign stealing.

    To make improvements on our analysis going forward, we can collect more data from previous and future years, and compare all ballparks in the MLB rather than just Minute-Made Park. We did find some of the answers to our questions but collected more data will allow us to further justify our current answers and look for stronger proof of the Astros’ advantage they gained because of sign stealing.  
6. **Try something more advanced.** Once you have a basic framework for your analysis, extend it with something more advanced. Perhaps you could try an advanced plot or maybe another data source or maybe replicated sampling to demonstrate reproducibility/lack of bias.
7. **Write and commit a `Readme.md` file inside your repository outlining your project.** This file is what GitHub will display by default for your repository, so make a good impression. It's standard Markdown, just like we use in Jupyter. Instead of using slides, you will start and end your final presentation with the `Readme.md`, so use it to link to all your files and provide (meta) information about your project: motivations, data sources, challenges, lessons learned, etc. Suggestion: write this stuff early and update it as you go along.
8. **Clean up your final notebook and GitHub repo.** The final notebook is your presentation (i.e., there will be no slides) so make sure it is readable on a TV monitor from across the room. It is also your report, so make sure every objective, decision, interpretation, and conclusion you make is throughly explained and professional-looking. (Yes, styling and organization matters. We're professionals, right?) Make sure you don't have any unfinished or extraneous artifacts left over from your explorations. (Again, we're professionals, not undergrads.)
