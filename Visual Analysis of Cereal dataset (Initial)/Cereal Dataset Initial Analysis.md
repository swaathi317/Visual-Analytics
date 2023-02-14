# Cereal Dataset Analysis

## Analytics queries or questions:
● Which cereal brand is popular among kids?
● At what temperature, do most cereals in the database are expected to be
consumed?
● For 1 cup of cereal, which cereal has the lowest calories?
● What is the average shelf life of a kids’ cereal?


## Insights from the dataset:
● Healthy cereals have higher fiber content than the other types. Cereals in the
health section have an average of 8 (units) of fiber content in them, while adults’
have 3 units, and kids’ and diet’s have 1 unit in them.
● Kids’ cereals have the lowest amount of potassium whereas healthy cereals have
the highest amount.
● The potassium amount in cereals is positively correlated to the fiber content in
them. They have a correlation coefficient of 0.959, which is very high.
● The average (mean) amount of calories in the cereals is 143 units.


## Process of analysis:
I used the spreadsheet application to explore and analyze the cereals data. I identified
that the nutrient values were given for different quantities of cereal (1 cup, less than 1
cup, and more than 1 cup). In order to maintain uniformity, I changed the nutrient values
to represent 1 cup of cereal by using basic arithmetic operations. Then, I filtered the
columns based on categories (like Adult, Kids, and Health) and sorted the values to
answer the basic queries. I used several functions in the spreadsheet to derive insights
from the data. I used functions such as COUNTIF, AVERAGE, MEDIAN, MODE, and
CORREL. I calculated the standard deviation to better understand the spread of data
and chose the best average function for the particular column.

## Challenges:
I faced three challenges while analyzing this dataset. The first challenge was identifying
the inconsistency in the number of cups (representing cereal quantity) and their
associated nutrients. Each cereal had a different cup size and nutrients were given for
that particular cup size. Hence, all the nutrient data had to be converted to represent a
uniform quantity of the cereal (1 cup). Initially, I assumed the conversion was an easy
task. But while working I realized that it was time-consuming. The second challenge was
assuming the missing measurement units. The measurements were not mentioned for
several columns like shelf, weight, and nutrients. It was difficult to assume if a cereal has
3 years of shelf life or 3 months of shelf life. The third challenge was dealing with
negative nutrient values. Some nutrients had negative values. It could have been a
human error during data entry. But the analytical results may not turn out accurate. Since
we can deal with them in different ways. For example, by making them positive or by
deleting the whole record.