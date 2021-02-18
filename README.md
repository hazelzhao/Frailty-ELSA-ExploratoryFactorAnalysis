# Frailty-ELSA-ExploratoryFactorAnalysis

## Intro

The aim of this study is to discover the internal structure of the resulting frailty index of participants in the English Longitudinal Study of Ageing (ELSA), to identify factors contained in the cumulative deficits model. 

The 62 deficits in the frailty index are classified into several domains: mobility, disability, physician diagnosed conditions, self-reported eyesight and hearing, self-rated general health, movement, CES-D depression scales (mental health) and cognitive function.  Tetrachoric and polychoric correlation coefficient are calculated as the basis of Exploratory Factor Analysis (EFA). Keiser-Meyer-Olkin (KMO) and Bertlett's Test of Sphericity are used to test if a set of variables are suitable for factor analysis. Multiple methods are used when determining the number of factors to extract, such as Kaiser's rule, scree plot and parallel analysis. Interpretability and model fit statistics are used to choose a model with better performance. Principal axis is employed to extract factors. In order to generate a model which has more simple structure, factor rotation is used. 


## Data 
The data source is from the English Longitudinal Study Ageing (ELSA), which is distributed by the UK Data Service with the title “English Longitudinal Study of Ageing: Waves 0-9,1998-2019”. The data set is Wave 4. The survey was conducted in 2008-2009, included 11050 participants.


### Data Preparation

The purpose of this step is to transform the raw data into data that meets requirement for analysis, including

1. select relevant items based on papers

2.Deriving variables: some deficits measure symptoms, which may be related with other diseases. In this case, this 
type of deficits needs to be distinguished with the disease such that the measure does not overlap.

3.Recoding/scaling: this involved reassigning values of variables. Different variables have different value scale, some variables are binary having either value “0”(No/Good; a negative result of a deficit) or “1” (Yes/Bad; a positive result of a deficit), some variables are ordinal having values 1 to 4 or 1 to 5, for convenience of analysis, all values are rescaled within 0 and 1. For example, hearing has original value “1”,”2”,”3”,”4”,”5”, it is rescaled as “0”,”0.25”,”0.5”,”0.75”,”1”. A higher value represents a worse result of a frailty deficit.

### Frailty Index  

### EFA within each subset of variables





