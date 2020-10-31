# Hello everybody,
## I am Alexander and this is my coding portfolio.

I made my master in Biology and now I am on my way to become an Data or Business Analyst.
Who knows, maybe this journey will lead me to become an data scientist?
Here, I will share some of my python projects that I coded.
Enjoy the short summaries or have a look at the code on github.

Cheers,

*Alexander*

# [Freedom Status ANOVA (R)](https://github.com/AlexandersProjects/freedom_comparison_worldwide)
* Explored the data
  * Boxplots
  * QQ-plots
  * Histograms
  * Used different R libraries for data exploration
* Controlled the data for outliers
* Compared if the different Freedom status are statistically significantly different groups.

## Hypothesis

H1: There is a mean difference between degree of freedom and the relative GDP.
(FS[F] != FS[NF] != FS[PF])

H0: There is no mean difference between degree of freedom and the relative GDP.
(FS[F] = FS[NF] = FS[PF])

## Conclusion
### ANOVA
The degree of freedom has a signifikant influence on the relative GDP (F(2, 49.062) = 15.491 , p = 6.097e-06). 19.4 % of the variation in the relative GDP around the overall mean can be explained by the degree of freedom. The effect strength according to Cohen (1988) is f = 0.4907 and corresponds to a strong effect.

### Post-hoc-Test
The Tukey post-hoc-test shows, that two groups can be constructed according to degree of freedom (all p < .05): free (M = 27841401	, SD = 26632852, N = 56), and not-free (M = 12368148, SD = 18508685,N = 21) and partially-free (M = 6202767	, SD = 10345156, N=44) form the second group.

It can be concluded that two independent groups can be formed that differ from each other. Freedom is the most effective. H0 is declined, H1 accepted.

## Example output:
<img src="./images/freedom_qqplot.png" width="600" height="450">
<img src="./images/freedom_profilediagram.png" width="450" height="450">

# [Handwritten digits recognition (Python)](https://github.com/AlexandersProjects/ml_number_recognition)
* Imported 20000 pictures
* Cleaned and reshaped the images
* Explored/ visualized the images
* Performed different prediction models:
  * Linear regression
  * Decision tree
  * Random Forest
  * Simple Neuronal Network
  * Try of convoluted Neuronal Network
* Tried different evaluation methods
  * Heatmap with errors
  * Loss over epochs
  * Accuracy

## Example output:
<img src="./images/digits_visualization.png" width="450" height="450">
<img src="./images/digits_error_heatmap.png" width="450" height="450">

# [Pokemon comparison (R)](https://github.com/AlexandersProjects/legendary_pokemon_comparison)
* Explored the data
* Controlled the data
* Compared if legendary pokemon have statistically higher attack than non-legendary pokemon.

## Hypothesis

H0: The attack of legendary pokemon is lower or equal than of non-legendary pokemon.
(M[L] </= M[NL])

H1: The attack of legendary pokemon higher than of non-legendary pokemon.
(M[L] > M[NL])

## Conclusion
Legendary (M = 116.68, SD = 30.35, n = 65) pokemon have significantly higher attacks than non-legendary (M = 75.67, SD = 30.49, n = 735) pokemon (t(798) = -10.397, p = 2.513e-05, n= 798). Hence, the H0 can be discarded.
The effect-size is d = 3.438535 and is according to Cohen (1988) a very strong effect.

## Histrogram of pokemon attack:
<img src="./images/pokemon_histogram.png" width="600" height="450">

# [Asteroid diameter prediction (Python)](https://github.com/AlexandersProjects/Asteroid_Diameter_Prediction)
* Cleaned the data
* Explored the data
* Performed different prediction models:
  * Linear regression
  * Polynomial regressions
  * Decision tree
  * Random Forest

## Example output:
<img src="./images/asteroids_decision%20tree.png" width="450" height="450">
<img src="./images/asteroids_Decision%20Tree_Error%20Curve.png" width="450" height="450">

# [Overfitting example (Python)](https://github.com/AlexandersProjects/ueberanpassung_Beispiele)
* Used pipelines
* Used convenience functions for calculations
* performed:
  * Linear regression
  * Quadratic regression
  * Cubic regression
* Made different plots

## Example output:
<img src="./images/lineare_regression_ueberanpassung_001.png" width="450" height="450">
<img src="./images/quadratische_regression_ueberanpassung_002.png" width="450" height="450">
<img src="./images/kubische_regression_ueberanpassung_003.png" width="450" height="450">

# [Linear Regression (Python)](https://github.com/AlexandersProjects/linear_regressions)
* performed:
  * linear regression
  * multiple linear regression
  * polynomial regression
  * exploratory Data analysis
* Made different plots

## Example output:
<img src="./images/linear_regression.png" width="450" height="450">

<img src="./images/seaborn_pairplot.png" width="800" height="800">


# [SQL film festival database](https://github.com/AlexandersProjects/SQL_Filmfestival_Database)
* I constructed a database from scratch
* I created all necessary tables
* I made all the necessary connections and indices
* I created views, procedures and triggers
* I made useful table and scalar functions

## The created database:
<img src="./images/film_festival_database_diagram.jpg" width="1200" height="600">


# [Height and weight Dataset with OOP (Python)](https://github.com/CrazyShaddy/height_weight_analysis_and_prediction)
* I scraped data from a website
* I explored the data
* I included everything in objects (OOP)
* I retained graphs from my classes
  * Sub plots
  * Regression line
* I made my first small prediction

## Created output:
<img src="./images/linear_reg_1.png" width="450" height="450">
<img src="./images/subplot_1.png" width="600" height="600">
<img src="./images/prediction_output.png" width="600" height="600">


# [Exploratory Data Analysis (Python)](https://github.com/CrazyShaddy/Exploratory-Data-Analysis)
* I explored data from an online database
* I extracted different dataframes
* I merged important dataframes
* I made
  * Bar charts
  * Pie chart
  * Box plot
  * Sub plots
  * Different sub plots in one figure

## Created output:
<img src="./images/bar_chart_001.png" width="600" height="600">

<img src="./images/bar_chart_meals_per_food.png" width="600" height="600">

<img src="./images/pie_chart_cuisine_share.png" width="550" height="400">

<img src="./images/box_cuisine_price.png" width="450" height="450">

![](/images/first_subplot_scatter.png)

![](/images/three_plots.png)


# [Compound Interest calculator (Python)](https://github.com/CrazyShaddy/Compound_Interest_Calculator)
* I made a calculator that calculates the compound interest and plots the graph from start till finish
* I took the user input
* I made functions to
  * retain the CI
  * save the x-values
  * calculate the compound interest
* I made lists for x- and y-values
* Finally, I plotted the graph with matplotlib

## Example output:

![](/images/Output_console.png)

![](/images/CI_example.png)
