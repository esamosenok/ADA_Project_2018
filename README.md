# Eat less sugar, you're sweet enough already
__cs_team_beta_hw2__ Project
http://htmlpreview.github.io/?https://github.com/esamosenok/ADA_Project_2018/blob/master/index.html

# Abstract
Many people consume too much sugar and even more than they realize. Some products contain added or hidden sugar like Low-fat Yogurst, BBQ Sauce, ketchup or Fruit Juice. To put in perspective, some sauces may contains more than 50 per cent of sugar. (*Ref1)

Based on the "AHA Scientific Statement" (*Ref2), the major sources of added sugars are mainly coming form those Food Categories: regular soft drinks, sugars, candy, cakes, cookies, pies and fruit drinks, dairy desserts and milk products:

Food categories	                                   Contribution to added sugar intake (% of total added sugar consumed)
Regular soft drinks	                               33.0
Sugars and candy	                               16.1
Cakes, cookies, pies	                           12.9
Fruit drinks (fruitades and fruit punch)	        9.7
Dairy desserts and milk products 
(ice cream sweetened yogurt, and sweetened milk)	8.6
Other grains (cinnamon toast and honey-nut waffles)	5.8

From there, it's easy understandable that eating too much sugar is not healthy and can cause Weight Gain, increase the risk of Hear Disease, Diabetes (*Ref3) or even Cancer, ...

Therefore, it's crucial to limit the consumption of foods with high amounts of added sugars. According to the American Heart Association (AHA) (*Ref4), the maximum amount of added sugars per day are limited to:
- Men:   150 calories per day (37.5 grams or 9 teaspoons or ~6.30 pieces of sugar)
- Women: 100 calories per day (25 grams or 6 teaspoons or ~4.20 pieces of sugar)

The US dietary guidelines advise people to limit their intake to less than 10% of their daily calorie intake. For a person eating 2,000 calories per day, this would equal 50 grams of sugar, or about 12.5 teaspoons or 8.4 pieces of sugar. (*Ref5)

“Keeping intake of free sugars to less than 10% of total energy intake reduces the risk of overweight, obesity and tooth decay,” says Dr Francesco Branca, Director of WHO’s Department of Nutrition for Health and Development.(*Ref6)

Based on the information above, we would like to explore the "Open Food Facts Datbase", apply the knowledge of data analysis technics and best practices acquired during attending Applied Data Analysis course at EPFL in Lausanne in Autumn 2018 and figure out meaninful/insightful relationship between different dimensions used to categorize the data or external metrics.

References/Sources

*Ref1 Heathy Food: How much sugar is in that sauces ?
https://www.healthyfoodguide.com.au/articles/2015/july/how-much-sugar-sauce

*Ref2 Major Sources of Added Sugars in the American Diet
https://www.ahajournals.org/doi/pdf/10.1161/circulationaha.109.192627

*Ref3 Maximum amount of added sugars recommendation from the American Heart Association
https://www.heart.org/en/healthy-living/healthy-eating/eat-smart/sugar/added-sugars

*Ref3 Relationship of Sugar to Population-Level Diabetes Prevalence
https://journals.plos.org/plosone/article/figure?id=10.1371/journal.pone.0057873.g002

*Ref4 Major Sources of Added Sugars in the American Diet
https://www.ahajournals.org/doi/pdf/10.1161/circulationaha.109.192627

*Ref5 US Dietary guideleines 
https://health.gov/dietaryguidelines/2015/guidelines/executive-summary/

*Ref6 World Health Organization: Reduce sugars intake 
http://www.who.int/mediacentre/news/releases/2015/sugar-guideline/en/



# Research questions
There are lots of different dimensions/metrics which could be used to analyse/slice the data: dates when the product was added and last modified, produced country, brand, categories (e.g. snack, dessert), country / store where the product was purchased, size and weight of the product, amount of fat, sugar, vitamins, chemicals, ingredients as text etc We will explore the dimensions/metrics above and relate some of those to each other or such generic metrics as country (producer or consumer) GDP, life expectancy (vitamins, salt, sugar, other chemicals), expore which country/store is the biggest produce/consumer of product by brand/ingredients etc. We will also check how some of the metrics evolve over time.

Explore the quality of the data, find and estimate inconsistencies (e.g. accuracy of the text description)

Finally, there are images available for each product, so we will try to analyse those using Deep Learning techniques (CNN) and relate to some of the deminsions avialable in the dataset.

We were maybe a little ambition about the analyis we would like to perform and discovered many discrepancies on the Data. Indeed, we learnt during the lecturer that the main activities performed by a Data Scientist is Data Cleaning. Based on the Data Quality of the www.openFoodFacts.org Data, we are fully agree with this assertion and we even decided to spend more time on Data Analyis.

Indeed in order to perform good analysis, it's crucial to consolidate the firt layer and understand the Data Set. We even think that this open Database should be more normalized and structured, which may offer a more solid base for further Analyis and Data Cleaning.

What is the goal to perform deeper analyis, when underlying data are not certified, checked, cleaned, cleansed and normalized. Furtheremore as you will discover in this Notebook, most of the dimensions have to be used with precaution.

Could we trust OpenFoodFacts Data ?

Should we eat too much sugar ?


# Dataset
Open Food Facts database contains the information on food products from around the world. For each item, the database stores its generic name, quantity, type of packaging, brand, category, manufacturing or processing locations, countries and stores where the product is sold, list of ingredients, any traces. 
https://world.openfoodfacts.org


# A list of internal milestones up until project milestone 3
The data was messier and more difficult to manage than we had initially thought. Many of our original ideas turned out infeasible and we have had to change our approach to things.

Our current plan until  the third milestone the 15 December is as follows:
* 25 to 28 November: Select three to five questions relating to sugar and health that we can answer with this data
* 29 to 30 November: Select a platform for our story
* 01 to 07 December: Answer the questions
* 07 to 14 December: Finalize the story

# Questions for TAa
N/A

