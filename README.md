# Repository - Analysis

### This repository contains code analysing a limited set of reviews left by customers for Apple AirPods to glean some data relating to consumer preferences. <br>
![alt text](https://images.unsplash.com/photo-1713492527322-471061e52516?w=900&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Nnx8YXBwbGUlMjBlY29zeXN0ZW18ZW58MHx8MHx8fDA%3D)
### Objective- To analyse topic prevalence within the reviews and identify whether members of the Apple ecosystem are more likely to leave a positive review than non-members.

### INTRODUCTION-
Insights into consumers' opinions about a product is vital in product improvement. In this limited experiment, I aim to analyse a small dataset of reviews left by Apple AirPods users. The data is segemented based on how long the customer has used the product. <br> 
The dataset has 2 broad categories of reviews- <br>
1. Reviews mentioning the Apple ecosystem <br>
2. Other reviews, which for the purpose of this analysis, have been considered to be reviews left by customers who do not place importance on the product's integration into the Apple ecosystem <br>


I will pick out some key topics mentioned in the reviews, and create a heatmap which explores the prevalence of said topic within each dataset as well as the combined dataset. <br>
<br>
I also test a small hypothesis that members of the Apple ecosystem are more likely to say positive things about the AirPods. **Will this hold true?** <br>

#### Exploratory Data Analysis 1 - Average Ratings

I wanted to explore whether members of the Apple ecosystem would be more likely to be critical or supportive of Apple AirPods

#### Exploratory Data Analysis 2 - Word Count Plot

I wanted to quickly visualise the most common words used within the 2 datasets, and hence, have created Word Count Plots where the size of the word shows its prevalence

#### Exploratory Data Analysis 3 - Heatmap of common words

To get a more granular look on what members of the ecosystem versus others talk about relating to the Apple AirPods based on how long they've used the product
There are 4 buckets of product usage -
1. Less than 1 month
2. More than 1 month but Less than 6 months
3. More than 6 months
4. Unknown (Data Not Available)


### CONCLUSION-

A. Based on EDA 1, we know that members of the Apple ecosystem are around 2.5% more likely to give a lower rating to Apple AirPods than others.

B. Based on EDA 2, we see some words being used very frequently across the datasets. They are- <br>
[i] Ecosystem reviews - **Ecosystem, Product, Sound, Quality** <br> 
[ii] Other reviews - **Use, Quality, Easy, Sound** <br>

C. The heatmap is a rich data source, and can be interacted with here - 
### https://kirtanag.github.io/data_analysis/AirPodsInteractiveHeatmap.html

Some key conclusions from it include: <br>
[a] Overall, a lot of users talk about the product's sound quality, as well as phone (presumably about connecting to their phone) <br>
[b] Unsurprisingly, members of the ecosystem talk about sound quality more than other reviewers. <br>
[c] There is a non-trivial downward movement of the mention of quality in the overall heatmap as time progresses. <br>
[d] More people talk about how the AirPods work more than 6 months into using it. <br>
