# nosql-challenge
Module 12 - Eat Safe, Love NoSQL analysis

For the first part of the challenge, I looked up PyMongo/MongoDB documentation on how to convert string to decimal and string to integer. I also looked on StackOverflow to see how to find object type in PyMongo/MongoDB to verify that the coordinates and rating value changed to numbers. 

For the second part of the challenge, I used Xpert Learning Assistant to ask why my block of code:

"query = {"geocode.latitude": {"$lte": latitude + degree_search, "$gte": latitude - degree_search},
         "geocode.longitude": {"$lte": longitude + degree_search, "$gte": longitude - degree_search},
         "RatingValue": 5}" 
         
wasn't working and it told me I had a typo in latitude, so I was able to fix it. 
