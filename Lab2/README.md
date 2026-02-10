Part 2:

in this project, I use a US housing sales dataset containing property listings from multiple cities and states. Each row represents one house, with information about its location, number of bedrooms and bathrooms, floor area, lot size, year built, days on market, and property type. The goal is to build a regression model that predicts the house Price based on these features. This can help agents and buyers estimate how much a house is likely to sell for given its characteristics.

Summary:

The dataset used in this lab is a US housing sales dataset containing information about individual residential properties. Each record corresponds to a single listing, including its price, address, city, state, number of bedrooms and bathrooms, interior area in square feet, lot size, year built, days on market, and property type (e.g., townhouse, condo, single family, apartment).

The machine learning problem is to predict the sale price of a house based on its characteristics. Because the target variable Price is numeric and continuous, this is formulated as a supervised regression problem. The input features include both numerical attributes (such as Bedrooms, Bathrooms, Area (Sqft), Lot Size, Year Built, Days on Market) and categorical attributes (City, State, Property Type, Status). By training a regression model on this data, we aim to learn how these features influence house prices and to estimate the price of new properties given their characteristics.
