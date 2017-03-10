{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# IMPROVE CUSTOMER SATISFACTION FOR EMIRATES AIRLINE \n",
    "\n",
    "In the service industry, keep high customer satisfaction is always among the top priority. Hence, for all airlines how customers view their service which reflects in overall rating is a good metric to measure the performance. Emirates airline is one of the airlines in the average range of overall rating (6/10). From 2010 to 2015, the rating for its service has not changed much. Improve certain parts in their service will definitely enhance customer satisfaction, and attract travellers to use the service more often or even suggest to their friends. However, Emirates needs to know where its investment would be most profitable, that is it needs to analyze cost and benefit related to increasing the performance in certain services. Therefore, in this project my aim is to provide a model where Emirates airlines can use in planning its targetted overall rating. \n",
    "\n",
    "### Data\n",
    "The data is scraped from airlinequality.com by quankiquanki from Skytrax website: https://github.com/quankiquanki/skytrax-reviews-dataset. Skytrax website has long been a great site for customers reviews of airlines, where it collects reviews and ratings for each airlines, lounges, seats and airports.\n",
    "The dataset for Emirates airline has a total sample of 691 observations with 20 columns containing information of the reviewers (name, country, date of review, type of travellers) and their ratings for each features as well as comments on the airlines. The ratings for each attribute range from 1 to 5, while overall rating is from 1 to 10. \n",
    "\n",
    "### Approach\n",
    "* First, I build a model that can predict well the overall rating based on each feature's rating. In order to do that, I conduct OLS Linear model, Ridge linear for parameter regularization and random forest. \n",
    "* Then, I select the best model among these methods and choose the important features for airlines.\n",
    "* Finally, using these features on the best models, I create a table for relative reference in planning targets for attribute ratings. This table together with the selected best model and cost-benefit analysis, Emirates airlines can build a good strategy on where to invest their resources to achieve better performance in customer satisfaction and profits.\n",
    "\n",
    "\n",
    "### Result\n",
    "* Random forest is the best performance with the lowest MSE of 1.64 on the test set. The most important factors in order that may affect overall rating are value-money rating, cabin staff, seat comfort, food beverages and inflight entertainment. These all have positive correlations with overall rating.\n",
    "\n",
    "### Recommendations \n",
    "* Based on its corporate strategy and cost-benefit analysis, Emirates may use the reference table and Random forest model to plan their target for improvement in some services.\n",
    "* While pricing is related closely with business strategy and positioning, Emirates might find it easier to improve its cabin staff and food beverages while still have huge effect on overall rating.\n",
    "\n",
    "### Further research\n",
    "Do topic and sentiment analysis on the travellers' reviews for Emirates airline to see which topics are most discussed, and alerts on negative reviews to take in-time action.\n"
   ]
  }
