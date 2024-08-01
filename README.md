# Celebrity Marketing Experiment

### Methodology and Experimental Design

I utilized Qualtrics to conduct a survey that aimed to understand how consumers view products, such as clothing, accessories, and cosmetics. Although the sample size (total number of survery respondents) was quite small, results were still shown to be significant. The survey assigned participants to either a control group or a treatment group when they entered the survey using Qualtrics randomization feature. The same experiment was conducted across six products: a gray hoodie, a leather shoulder bag, loafer slingbacks, sunglasses, a leather bomber jacket and mascara. After looking at the images, each participant estimated the price of the product and their intent to purchase it, on a scale of 1 to 5. Additionally, few datapoints on respondent's demographic were collected (age, gender, and budget).


### Data Preprocessing

In order to prepare our dataset for analysis, the first step was to create a 'Treatment' column, a binary variable indicating if a participant was assigned to the treatment or control group. The dataset produced by the survey was extremely messy and unorganzied but after effectively transforming the data, the number of columns dropped from 62 columns to 29.


### Results

<img width="852" alt="Screen Shot 2024-07-31 at 10 03 00 PM" src="https://github.com/user-attachments/assets/a91c0e9b-5708-411e-bcf6-e80bc744d78f">


<img width="761" alt="Screen Shot 2024-07-31 at 10 03 31 PM" src="https://github.com/user-attachments/assets/db1810f2-bc99-4485-b46b-a0736a1ade08">

As highlighted by the asterisks, the average of the respondent's price estimates were statistically significant for 5/6 products (p-value < 5%), ultimately rejecting the null hypothesis that there is no significant difference between the percieved price of a product between the treatment and control group.


Note - there are more specific results (i.e. regression model including conditional ATE, and fixed effects) in the output of the main script.
