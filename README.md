# Eat less sugar, you're sweet enough already
__cs_team_beta__

Please follow the link to view the website for the data story

http://openfoodfacts.funspirit.ch

# Abstract
Many people consume too much sugar, often even without realizing it. Is is not uncommon for products to contain added or hidden sugar, products such as low-fat yogurt, BBQ Sauce, ketchup or fruit juice. To put into perspective, some sauces may contains more than 50 per cent of sugar. (*Ref1) Based on the "AHA Scientific Statement" (*Ref2), the major sources of added sugars can be found in categories such as regular soft drinks, sugars, candy, cakes, cookies, pies and fruit drinks, dairy desserts and milk products:

It's easy to consume too much sugar and the drawbacks are many. Overconsumption can lead to obesity, increase the risk of heart disease, diabetes (*Ref3) and even cancer. With the abundance of sweets that add a great deal of sugar even when consuming little (see table below), this issue is bigger than ever.

| Food categories | Contribution to added sugar|
| ------ | ------ |
| | intake (% of total added sugar consumed)|
| Regular soft drinks | 33 |
| Sugars and candy | 16.1|
| Cakes, cookies, pies | 12.9|
| Fruit drinks  |9,7|
| Dairy desserts and milk products |8.6|
| Other grains |5.8|


Therefore, it's crucial to limit the consumption of foods with high amounts of added sugars. According to the American Heart Association (AHA) (*Ref4), the maximum amount of added sugars per day are limited to:

* **Men**: 150 calories per day 
(37.5 grams or 9 teaspoons or ~6.30 pieces of sugar)

* **Women**: 100 calories per day 
(25 grams or 6 teaspoons or ~4.20 pieces of sugar)

The US dietary guidelines advise people to limit their intake to less than 10% of their daily calorie intake. For a person eating 2,000 calories per day, this would equal 50 grams of sugar, or about 12.5 teaspoons or 8.4 pieces of sugar. (*Ref5)
“Keeping intake of free sugars to less than 10% of total energy intake reduces the risk of overweight, obesity and tooth decay,” says Dr Francesco Branca, Director of WHO’s Department of Nutrition for Health and Development.(*Ref6)

Based on the information above, we would like to explore the "Open Food Facts Datbase", apply the knowledge of data analysis techniques and best practices acquired during attending Applied Data Analysis course at EPFL in Lausanne in Autumn 2018 and figure out meaninful/insightful relationship between different dimensions used to categorize the data or external metrics.

# Initial idea 
There are lots of different dimensions/metrics which could be used to analyse/slice the data: dates when the product was added and last modified, produced country, brand, categories (e.g. snack, dessert), country / store where the product was purchased, size and weight of the product, amount of fat, sugar, vitamins, chemicals, ingredients as text etc. 

We plan to explore the dimensions/metrics above and relate some of those to each other or such generic metrics as country (producer or consumer) GDP, life expectancy (vitamins, salt, sugar, other chemicals), expore which country/store is the biggest produce/consumer of product by brand/ingredients etc. We also plan to check how some of the metrics evolve over time and perform some Data Cleaning and see how we can enrich the data.

If we have time it would be nice to see how we can apply techniques of machine learning, maybe to relate images of food products to levels of sugar or the like.

# Research questions
* What is the most sugary product, and what is its nutrition score ?
* Is there a relation between the amount of fat, sugar and salt in products ?
* Does the amount of sugar in a product depend on the brand type (low-cost, high-cost, biological etc) ?
* How many products contain more sugar than recommened, and how does that relate to the category type?

We were originally very ambitous with our plans for what we would do with the data. However, during the exploratory phase of the project we encountered problems. Categories were lacking, values were outside of valid ranges, the naming system differed between contributors et cetera et cetera - in essence, the data was quite messy. This did indeed match well with what we had heard during lectures, that one of the most time consuming tasks for the Data Scientist was data cleaning, but it nevertheless came as a slight surprise. To that end we decided to spend more time at data exploration and data cleaning that we could have used for analysis, if the database had been more structured in the first place.

Given all the problems we encountered with the data we would recommend some caution when observing the results. After all, if the underlying data is flawed then so will the conclusions drawn from it.

# Dataset
Open Food Facts database contains the information on food products from around the world. For each item, the database stores its generic name, quantity, type of packaging, brand, category, manufacturing or processing locations, countries and stores where the product is sold, list of ingredients and more.

*"The project was started by Stéphane Gigandet, creator of the food blogs portals Recettes de Cuisine (French) and Very Good Recipes, and various other collaborative and/or food-related projects (mostly in French, e.g. Manger Bloguer and Informations Nutritionnelles). Stéphane takes care in particular of the technical architecture of Open Food Facts, its development and the hosting of the site and its database."*

*"The contributors to the Open Food Facts project are people that are passionate about food. They add products to the database and they are also the primary source for improvements and applications ideas through the Idea Forum and several others venues for the Open Food Facts community to share and discuss. Open Food Facts is a project open to all: you can join them by creating an account in less than a minute, and you can add your first product in a few more minutes."*

# Contributions
**Samasionak Yauheni:** Presentation and Poster

**Steve Rey:** Website, Data exploration, Data cleaning, Data game

**Victor Wiklund:** Data analysis

# References/Sources
* Ref1 Heathy Food: How much sugar is in that sauces ?
* Ref2 Major Sources of Added Sugars in the American Diet
* Ref3 Maximum amount of added sugars recommendation from the American Heart Association
* Ref4 Relationship of Sugar to Population-Level Diabetes Prevalence
* Ref5 Major Sources of Added Sugars in the American Diet
* Ref6 US Dietary guideleines
* Ref7 World Health Organization: Reduce sugars intake

Realised in the context of the course of EPFL Applied Data Analysis (CS-401) teached by Robert West. Jupyter Notebook/Sources could be founded here.

# Links
* Repo for Data Story: https://github.com/openfoodfacts2019/ADA (branch gh-pages)
* Data Story: https://openfoodfacts2019.github.io/ADA/
* Backup Data Story: http://openfoodfacts.funspirit.ch/
