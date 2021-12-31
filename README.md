# James Kowalik Portfolio

Data analysis and data science project examples.

#  [Project 1: Pitchfork Scores Data Analysis and Prediction](https://github.com/jamesk185/Project---The-Pitchfork-Effect)

An independent data science project by James Kowalik completed in October 2021.

Link to report: [https://rpubs.com/jamesk185/824113](https://rpubs.com/jamesk185/824113)

### Overview:

- Written and programmed in R.
- Data processing and cleaning.
- Writing functions and building new variables, predictors.
- Data analysis.
- Using machine learning to perform prediction.

### Background:

Pitchfork is one of the most widely read online music magazines. It is most famed for its album review scores and 'Best New Music' award system. It assigns a score from 0 to 10 to one decimal place for an album that is released and reviewed by one of their writers. An album which receives a score of higher than 8.0 will often receive 'Best New Music' status- an indicator that it is of particularly high quality and an award which holds a lot of influence in terms of the album's sales and credibility.

The aim of this project will be to explore a dataset of Pitchfork reviews and, ultimately, build a prediction model that attempts to predict the score an album will get when reviewed by Pitchfork.

The below image is taken from the data analysis stage (and the report) and shows correlation between the predictors I built and the score.

![](/images/Pitchfork_project_scatter_graphs.png) 

<br />
<br />

# [Project 2: Vizualisation of Climate Data Recorded in Chiyoda, Japan](https://github.com/jamesk185/Vizualisation-of-Climate-Data-Recorded-in-Chiyoda-Tokyo-Japan-Python-)

A data science project completed as part of the *Applied Plotting, Charting & Data Representation in Python* course by University of Michigan. Completed in December 2021.

Link to Report : [https://github.com/jamesk185/Vizualisation-of-Climate-Data-Recorded-in-Chiyoda-Tokyo-Japan-Python-/blob/main/Report.md](https://github.com/jamesk185/Vizualisation-of-Climate-Data-Recorded-in-Chiyoda-Tokyo-Japan-Python-/blob/main/Report.md)

Link to Graphic : [https://github.com/jamesk185/Vizualisation-of-Climate-Data-Recorded-in-Chiyoda-Tokyo-Japan-Python-/blob/main/Graph.png](https://github.com/jamesk185/Vizualisation-of-Climate-Data-Recorded-in-Chiyoda-Tokyo-Japan-Python-/blob/main/Graph.png)

### Overview:

- Written and programmed with Python using Jupyter Notebook.
- Data processing and cleaning.
- Data visualization.

### Background:

How have air temperature, total precipitation and relative humidity changed in Chiyoda, Japan over the last century and how do they compare to Michigan, USA?

With the primary focus being on Chiyoda, Tokyo, I will take a broad look at changes in climate condition over the last century in three key areas; air temperature, precipitation and humidity. For means of comparison and further interesting insight, and with the course being conducted by University of Michigan, I will include the air temperature and precipitation data for Ann Arbor, Michigan.

Below is the final produced graphic.

![](/images/Chiyoda_weather_Graph.png)

# [Project 3: Next Word Predictor App](https://github.com/jamesk185/JHU-DSS-Data-Science-Capstone-Project)

Completed as part of the *Data Science Capstone* course in the Johns Hopkins University Data Science Specialization in October 2021.

Link to pitch presentation: [https://rpubs.com/jamesk185/819061](https://rpubs.com/jamesk185/819061)

Link to shiny app: [https://jamesk185.shinyapps.io/WordPredictor/](https://jamesk185.shinyapps.io/WordPredictor/)

### Overview:

- Written and programmed in R.
- Natural language processing and tokenization.
- Creating an application using R's shinyapps.

### Background:

The aim of this project was to create an application that allows use of a predictive text model. With my app, a user will type a sentence, and the app will predict the next word in the sentence for them. My app will provide 4 options for the user where clicking on one of them will add it to the input box.

This was achieved through analysis of text data and natural language processing. In this process, tokenization was used to create datasets of 'n-gram' word combinations. With this, I tried various methods that looked at ultimately finding the best efficiency of the final product. That is to say, increasing the 'n' in 'n-grams' to have word combinations of, say, 8 words, would absolutely improve the accuracy of a word prediction model but the code would most likely not run in a reasonable timeframe on most computers. Also, the speed of the final product output from the app's user's perspective must be considered in this efficiency.

Below is a screenshot of the app's interface.

![](/images/next_word_predictor_screenshot2.png)

# [Project 4: Interactive Mapping of Covid-19 Deaths](https://github.com/jamesk185/JHU-DSS-Developing-Data-Products-Course-Project)

Completed as part of the *Developing Data Products* course in the Data Science Specialization by Johns Hopkins University in September 2021.

Link to shiny app: [https://jamesk185.shinyapps.io/ddpCourseProject/](https://jamesk185.shinyapps.io/ddpCourseProject/)

Link to presentation: [https://rpubs.com/jamesk185/805644](https://rpubs.com/jamesk185/805644)

### Overview:

- Written and programmed in R.
- Data processing and cleaning.
- Creating an application using R's plotly and shinyapps.

### Background:

The instructions for this project were as follows. “First, you will create a Shiny application and deploy it on Rstudio's servers. Second, you will use Slidify or Rstudio Presenter to prepare a reproducible pitch presentation about your application.”

My project is about the Covid-19 pandemic. As we approach a year and a half since the disease began to impact societies greatly all over the world, using maps created in plotly, I aim to provide a means for comparison between Covid-19 deaths in 2020 and in 2021. The user of my application will be able to see things such as which countries may have been largely unaffected by the initial outbreak but suffered from a huge relative increase in deaths as the virus spread further and wider. There will be 3 maps; the total number of deaths up until August 24th 2020, the total number of deaths up until August 24th 2021, and the percentage growth in deaths from August 24th 2020 to August 24th 2021.

The image below is a screenshot of the application in use.

![](/images/world_covid_deaths_map_screenshot.png)


