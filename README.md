# Hello everybody,
## I am Alexander and this is my coding portfolio.

I made my master in Biology and now I am on my way of getting into the IT.<br>
Who knows, maybe this journey will lead me to become a developer or go into BI?<br>
Here, I will share some of my programming projects that I coded.<br>
Enjoy the short summaries or have a look at the code on github.<br>

Cheers,

*Alexander*
<!--Project: -->
# [My FreeCodeCamp Responsive Web Design Projects (HTML/CSS)](https://github.com/AlexandersProjects/pancake_recipe_website/tree/main)
I got my FreeCodeCamp Responsive Web Design Certificate!<br>
For this I went through the course (estimated 300 hours) and finished these 5 projects.

### This is my Certificate:
[<img src="./images/responsive_web_design_FCC_Certificate.jpg" width="600" height="450">](https://www.freecodecamp.org/certification/alexanders_coding_journey/responsive-web-design)

## And here are my creations:
### This is my Hulk Tribute page:
[<img src="./images/responsive_web_design_FCC_Tribute_page.jpg" width="450" height="600">](https://codepen.io/alexandersprojects/full/oNWqEOb)

### This is my Hulk-Fans Survey page:
[<img src="./images/responsive_web_design_FCC_Survey_page.jpg" width="450" height="600">](https://codepen.io/alexandersprojects/full/BaRrYem)

### This is my Hulk Landing page:
[<img src="./images/responsive_web_design_FCC_Landing_page.jpg" width="600" height="450">](https://codepen.io/alexandersprojects/full/abWYqgo)

### This is my Fake Technical Documentation:
[<img src="./images/responsive_web_design_FCC_Technical_documentation.jpg" width="600" height="600">](https://codepen.io/alexandersprojects/full/VwbXQJj)

### This is my Portfolio page:
[<img src="./images/responsive_web_design_FCC_portfolio.jpg" width="450" height="600">](https://codepen.io/alexandersprojects/pen/QWvmQXx)

<!--Project: -->
# [Including CSS in my code (HTML/CSS)](https://github.com/AlexandersProjects/pancake_recipe_website/tree/main)
Here, I updated my trial website and made a CatPhotoApp with HTML and CSS.

## Example output:
<img src="./images/Pancake_recipe_website_CSS_update.jpg" width="450" height="700">
<img src="./images/CatPhotoApp.jpg" width="350" height="600">

<!--Project: -->
# [First website in HTML (HTML)](https://github.com/AlexandersProjects/pancake_recipe_website/tree/main)
This is my first HTML Website.
I created a simple pancake recipe and experimented with some HTML code.

## Example output:
<img src="./images/Pancake recipe website picture.jpg" width="450" height="700">

<!--Project: -->
# [ANOVA of tips (Python)](https://github.com/AlexandersProjects/ANOVA_python)
* Explored the data
  * Boxplots
  * QQ-plots
  * Histograms
  * Used different R libraries for data exploration
* Controlled the data for outliers
* Compared if the total bills are statistically significantly different per weekday.

## Hypothesis

H1: The weekday has an effect on the amount of the total bill.
(M[1] != M[2] != M[3] != M[4])

H0: The weekday has no effect on the amount of the total bill.
(M[1] = M[2] = M[3] = M[4])

## Conclusion
### ANOVA
The weekday has a significant influence on the total bill (F(3, 240) = 2.767 , p = 0.0424). 3.34 % of the spread of the total sum can be explained by the weekday. According to Cohen (1988) is the effect size of 0.186 a small effect.

### Post-hoc-Test
The Bonferroni Post-Hoc-Test shows that no groups can be generalized out of the weekday (all p > 0.05). Thursday (M=17.68, SD=7.89, N=62), Friday (M=17.15, SD=8.30, N=19), Saturday (M=20.44, SD=9.48, N=87) and Sunday (M=21.41, SD=8.83, N=76) are not significantly different.

It can be concluded that no independent groups can be formed that differ from each other. Hence, although the ANOVA was significant, the H0 is kept and H1 declined.

## Example output:
<img src="./images/anova_python_violin_plot.png" width="450" height="450">
<img src="./images/anova_python_mean_plot.png" width="450" height="450">

<!--Project: -->
# [Statistical Analysis of tips (Python)](https://github.com/AlexandersProjects/stats_in_python)
* Explored the data
  * Boxplots
  * QQ-plots
  * Histograms
  * Used different Python libraries for data exploration
* Controlled the data for outliers
* Used Pearson to check if there is a correlation between the total bill and the tip
* Compared if man and woman give significantly different tips.

## Conclusion
### Pearson
The tip and the total bill correlate positively significant (r = 0.6757341, p < 2.2e-16, n = 244). Hence, it can be said the higher the total bill the higher the tip. 45.66 % of the spread of the whole variance can be explained through the tip and the total bill. According to Cohen (1992) is the effect size of 0.68 a strong effect. The H0 can be discarded.

### T-Test
There is no significant difference between the tip of women (M = 2.83, SD = 1.16, n = 87) and man (M = 3.09, SD = 1.49, n = 157), (t(242) = -1.3879, p= 0.1665, n=244)). According to Cohen (1992) is the effect size of 0.185 no effect. The H0 cannot be discarded.

## Example output:
<img src="./images/stats_in_python_histogram.png" width="450" height="450">
<img src="./images/stats_in_python_probability_plot.png" width="450" height="300">

<!--Project: -->
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

<!--Project: -->
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

<!--Project: -->
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

<!--Project: -->
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

<!--Project: -->
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


<!--Project: -->
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

<!--Project: -->
# [SQL film festival database](https://github.com/AlexandersProjects/SQL_Filmfestival_Database)
* I constructed a database from scratch
* I created all necessary tables
* I made all the necessary connections and indices
* I created views, procedures and triggers
* I made useful table and scalar functions

## The created database:
<img src="./images/film_festival_database_diagram.jpg" width="1200" height="600">

<!--Project: -->
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

<!--Project: -->
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

<!--Project: -->
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
