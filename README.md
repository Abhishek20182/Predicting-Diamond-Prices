<p align="center">
  <a href="https://www.udacity.com/">
    <img src='https://course_report_production.s3.amazonaws.com/rich/rich_files/rich_files/5511/s300/udacity-logo.png' alt="Udacity logo" width = 100px>
   </a>
</p>

<h3 align="center"><a href = "https://www.udacity.com/course/predictive-analytics-for-business-nanodegree--nd008t"> Udacity Predictive Analytics for Business</a></h3>
<h4 align="center">Project I: Predicting Diamond Prices</h4>


## Table of Contents
- [Project Overview](#project_overview)
- [Project Details](#details)
  - [Understand the data](#understand)
  - [Calculate the predicted price for diamond](#calculate)
  - [Make a recommendation](#recommendation)
- [Project Submission](#submission)
- [Results](#results)
- [Licensing, Authors, and Acknowledgements](#licensing)


### Project Overview <a name="project_overview"></a>
A jewelry company wants to put in a bid to purchase a large set of diamonds, but is unsure how much it should bid. In this project, you will use the results from a predictive model to make a recommendation on how much the jewelry company should bid for the diamonds.

<b>US Number System</b>
- All numbers that will be presented in this Nanodegree program will be based on the US numbering system where 5,269 is "five thousand two hundred sixty nine" and 158.1 is "one hundred fifty eight point one" where 1 is a decimal number. This is very important so please take note of this.

### Project Details <a name="details"></a>
A diamond distributor has recently decided to exit the market and has put up a set of 3,000 diamonds up for auction. Seeing this as a great opportunity to expand its inventory, a jewelry company has shown interest in making a bid. To decide how much to bid, the company’s analytics team used a large database of diamond prices to build a linear regression model to predict the price of a diamond based on its attributes. You, as the business analysts, are tasked to apply that model to make a recommendation for how much the company should bid for the entire set of 3,000 diamonds.

The following diagram represents the analysis at a high level. Since the model is already built, your analysis will focus on the right side of the diagram.

<p align=center>
  <img src="https://video.udacity-data.com/topher/2017/February/58a4e35b_predictive-diagram/predictive-diagram.png" width=600px>
</p>

The linear regression model provides an equation that you can use to predict diamond prices for the set of 3,000 diamonds. The equation is below:
<p align=center>
  <b>Price</b> = -5,269 + 8,413 x <b>Carat</b> + 158.1 x <b>Cut</b> + 454 x <b>Clarity</b>
</p>


#### Step 1 – Understand the data<a name="understand"></a>: There are two datasets.
- <b>diamonds.csv</b> contains the data used to build the regression model.
- <b>new_diamonds.csv</b> contains the data for the diamonds the company would like to purchase.
<p align=center>
  <img src="https://video.udacity-data.com/topher/2017/February/58a4de9c_data-snapshot/data-snapshot.png">
</p>
Both datasets contain carat, cut, and clarity data for each diamond. Only the diamonds.csv dataset has prices. You'll be predicting prices for the new_diamonds.csv dataset.
- Carat represents the weight of the diamond, and is a numerical variable.
- Cut represents the quality of the cut of the diamond, and falls into 5 categories: fair, good, very good, ideal, and premium. Each of these categories are represented by a number, 1-5, in the Cut_Ord variable.
- Clarity represents the internal purity of the diamond, and falls into 8 categories: I1, SI2, SI1, VS1, VS2, VVS2, VVS1, and IF. Each of these categories are represented by a number, 1-8, in the Clarity_Ord variable.
- <b>Note</b>: Transforming category variables to ordinal variables like this is not always appropriate, but we’ve done it here for simplicity.

#### Step 2 – Calculate the predicted price for diamond:<a name="calculate"></a>
For each diamond, plug in the values for each of the variables into the linear model (equation). Then solve the equation to get the estimated, or predicted, diamond price. We suggest using a spreadsheet tool like Excel, Numbers, or Google Sheets. You could also do it in Alteryx and/or Tableau if you already have your license. 

#### Step 3 – Make a recommendation:<a name="recommendation"></a>
Now that you have the predicted price for each diamond, it’s time to calculate the bid price for the whole set. Note: The diamond price that the model predicts represents the final retail price the consumer will pay. The company generally purchases diamonds from distributors at 70% of that price, so your recommended bid price should represent that.

### Project Submission:<a name="submission"></a>
To complete this project, you will be submitting a file in pdf format that contains the answers to the following questions across three steps.

#### Step 1 - Understanding the Model:
- According to the linear model provided, if a diamond is 1 carat heavier than another with the same cut and clarity, how much more would the retail price of the heavier diamond be? Why?
- If you were interested in a 1.5 carat diamond with a Very Good cut (represented by a 3 in the model) and a VS2 clarity rating (represented by a 5 in the model), what retail price would the model predict for the diamond?

#### Step 2 - Visualize the Data: Create two scatter plots. If you're not sure what a scatter plot is, see here.

- Plot 1 - Plot the data for the diamonds in the database, with carat on the x-axis and price on the y-axis.
- Plot 2 - Plot the data for the diamonds for which you are predicting prices with carat on the x-axis and predicted price on the y-axis.
- Note: You can also plot both sets of data on the same chart in different colors.
- What strikes you about this comparison? After seeing this plot, do you feel confident in the model’s ability to predict prices?

#### Step 3 - The Recommendation: 
- What bid do you recommend for the jewelry company? Please explain how you arrived at that number.

### Results: <a name="results"></a>
All the results(including graphs) are in the <a href="https://github.com/Abhishek20182/Predicting-Diamond-Prices/blob/main/Project%201%20.pdf">Project 1.pdf</a> File.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
Must give credit to Udacity to providing this data. You can find the Licensing for the data and other descriptive information at Udacity Page.
