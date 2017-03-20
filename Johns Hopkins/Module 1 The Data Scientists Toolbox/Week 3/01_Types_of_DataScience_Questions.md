# Types of Data Science Questions

##  Descriptive
* Describe a set of data
  * commonly applied to census data
  * description and interpretation are different steps
  * Descriptions can usually not be generalized without additional statiscal modeling
* Ngrams Viewer

##  Exploratory
* Find relationships you didn't know about
  * good for discovering new connections
  * not for generalizing or prediction
  * Correlation doe snot imply causation
* The Sloan Digital Sky Survey

##  Inferential
* Use a relatively small sample of data to say something about a bigger population
  * most common goal of statistical models
  * depends heavily on population
* Effect of Air Pollution Control on Life Expectancy in the United States
  * Analyse a small subset of population

## Predictive
* use data on some objects to predict values for another object
  * If X predicts Y it doe snot mean that X causes Y
  * depends heavily onmeasuring the right variables
* Election Predictions (Five Thirty Eight)
* Target figured out a girl was pregnant based on search/purchase history

##  Causal
* to find out what happens to one variable when you make another variable change
  * usually randomized studies are required to identify causation
  * Causal relationships are usually identified as average effects, but may not apply to app individuals
  * Gold standard

##  Mechanistic
* Understand the exact changes in variabls that lead to changes in other variables for individual objects
  * incredibly hard to infer, except in simple situations
  * usually modeled by a deterministic set of equations (pysics/engineering science)
  * Generally the random component of the data is measurement error
  * If the equationsa re known but the parameters are not, they may be inferred with data analysis