# STAT-240-project
STAT 240 final project

# Motivation
As the automotive industry evolves, understanding the dynamics of car pricing becomes increasingly pivotal. In our analysis, we delve into the intriguing relationship between mileage and car prices, seeking not only to discern differences between high and low mileage vehicles but also to construct a predictive model that illuminates the future trajectory of car pricing trends.

# Questions of Interest
Our project seeks to answer two questions about used car prices. First, are the mean prices for cars with high mileage(100000 km =>) equal or different from the mean prices for cars with low mileage (<100000 km)? Second, how can we predict car prices based on their mileage using regression?

# Thesis Statement
Our study asserts that mileage significantly influences used car prices, as evidenced by our analysis of data sourced from a reputable car sharing and selling platform. Through statistical inference and regression modeling, we aim to proof that there is disparities in mean prices between high and low mileage vehicles. Furthermore, we also want to be able to predict car prices based on mileage.

# Background
# Dataset description
The data was collected by Simona Cana Ungureanu and Alba Aguilar Vialata from https://www.flexicar.es/, a car sharing company which also sells and buys used car.

They obtain the data by web-scraping it from the website.

The data was posted here 1

The data have 790 rows and 10 columns.

Key variable in the data are the brand, model, price, mileage, fuel type, gearbox, engine, year and location.

# Variable description
# Key Variables:

Brand, Model, Engine, Year: These variables identify each car’s specifications and market segment.

Price: The primary variable of interest, influenced by car features and market dynamics, used in our regression analysis and group comparisons.

Mileage: Essential for grouping cars into ‘high’ or ‘low’ mileage categories for pricing analysis.

Fuel Type, Gearbox: Additional variables considered for detailed analysis.

# Background information about this project
In the context this project, understanding several terms could be useful for the comprehending the reason behind this analysis. Firstly, car mileage, often indicated by an odometer reading, denotes the total distance a vehicle has traveled since its manufacture or its last odometer reset. This metric serves as a crucial indicator of a car’s wear and tear, influencing its overall value. Secondly, car price represents the monetary worth of a vehicle, determined by various factors such as its brand, model, year of manufacture, condition, features, and notably, its mileage. The mean price for cars with high mileage and those with low mileage serves as a focal point of analysis. This comparison aims to discern whether there is a significant difference in the average prices of vehicles that have traveled considerable distances versus those with relatively minimal mileage, shedding light on the impact of mileage on pricing dynamics. Usually, car with higher mileage is deemed undesirable in the used car market as it indicate that it has been used extensively by the precious owner. We are going to see here if that will affect the pricing of the car.

# Unusual factors
It is worth noting that the unit for the mileage here is in Kilometers and the unit of the price here is in Euros (European currency)
The flow of the project
We are planning to use variable mileage to categorize the car into high mileage car and low mileage car then compare the mean using statistical inference. We will use one cut off point = 100000km, taken from 2 mileage to categorize high mileage car and low mileage car. We intend to use difference in means model here.

Next, we also want to see if we are able to predict car prices based on the car mileage. We intend to use linear regression.

