## Project Title: 
Loc8r: Find places to work with wifi near you!

## Project Group Members:
Simon Holmes Roll No. -------

Shamsa Abid  Roll No. -------

## About Loc8r:
Looking for wifi and a seat? Loc8r helps you find places to work when out and about. Perhaps with coffee, cake or a pint? Let Loc8r help you find the place you're looking for.

## Homepage: https://loc8rdemo-2018.herokuapp.com

## UseCases: 
1. User can view a list of locations (https://loc8rdemo-2018.herokuapp.com)
2. User can click on location name to view location details like opening hours, facilities and customer reviews (http://localhost:3000/location/5bc0734d789815a59e0fac27)
3. User can add a review (http://localhost:3000/location/5bc0734d789815a59e0fac27/review/new)

## Schema: 
Collections: locations

Nested Collections: reviews, openingTimes

locations has nested reviews and openingTimes

## Contribution:
Simon Holmes: 
1. Wrote the code for both front-end and back-end.
2. Designed the schema
3. Implemented usecases 1,2 and 3
4. Designed and coded the views
5. Implemented back-end error and exception handling for all use cases
6. Implemented front-end input form validations for all the views

Shamsa Abid:
1. Altered usecase 1 to display locations from the database rather than using the geo-location service

## Future Work

Shamsa Abid:
1. Allowing a user to login and logout, (adding session management and authentication)
2. Allowing only logged in users to "add a review"
3. Restricting users to edit their own reviews. 

