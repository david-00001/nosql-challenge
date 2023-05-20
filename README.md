# nosql-challenge


## Part 1 Source Code:
NoSQL_setup_actual.ipynb


## Part 2 Source Code:
NoSQL_analysis_actual.ipynb


## Part 1 Online Resources Used:
How to count how many documents exist in a collection:
https://www.geeksforgeeks.org/count-the-number-of-documents-in-mongodb-using-python/

How to retrieve what type of field by using type() with name:
https://stackoverflow.com/questions/510972/getting-the-class-name-of-an-instance

Used this to convert string to float using update_many():
https://stackoverflow.com/questions/62818451/change-the-type-of-feature-from-string-to-float-using-pymongo


## Answers to Analysis Questions
1. Which establishments have a hygiene score equal to 20?

There are 41 establishments that have a hygiene score equal to 20. The first is the business 'The Chase Rest Home'.


2. Which establishments in London have a RatingValue greater than or equal to 4?

There are 33 establishments in London that have a rating value greater than or equal to 4. The first is the business 'Charlie's'.


3. What are the top 5 establishments with a RatingValue rating value of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?

The top 5 establishments near Pengang Flavours with a rating value of 5 sorted by lowest hygiene score are Volunteer, Plumstead Manor Nursery, Atlantic Fish Bar, Iceland, and Howe and Co Fish and Chips.


4. How many establishments in each Local Authority area have a hygiene score of 0?
'Thanet', 'count': 1130}
'Greenwich', 'count': 882}
'Maidstone', 'count': 713}
'Newham', 'count': 711}
'Swale', 'count': 686}
'Chelmsford', 'count': 680}
'Medway', 'count': 672}
'Bexley', 'count': 607}
'Southend-On-Sea', 'count': 586}
'Tendring', 'count': 542}
