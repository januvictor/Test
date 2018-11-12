# techtest


Karhoo SDET/QA Test

## Exercise 1
- Git Clone this repo
 
## Exercise 2
The "Get Auth Token" POST call is missing data. Using the API docs located here (https://docs.stg.karhoo.net/v1/auth#auth) complete the following exercise:

- Import Exercise2.postman_collection.json
- Update the postman call to include the correct post parameters with the values of "interview_test@karhoo.com". The other parameter will be given on the day of the interview



## Exercise 3 

Using Exercise2 complete the following:

- Update the "Get Auth Token" to save the value for "access_token" to a value called "bearer_token"
  - Use the code similar to the code that saves "refresh_token"
- Update "Get_Locations" using the api docs here (https://docs.stg.karhoo.net/v1/locations?shell#address-autocomplete) with the valid body
  - Body should json object 
  - the key will be "query"
  - the value will be "London"


## Exercise 4

Using Exercise3 complete the following:

- Update "Get a Quote ID"
  - Replace "{{destination_id}}" with a ID from exercise2
  - Add into the body the following
    - key : "origin_place_id"
    - value: "ChIJm39Ln9QEdkgR0l1-U8xXTuQ"
  - After making the call save the returned id as id
- Update "Get a Quote List"
  - Create a test to check for status code "200" is returned
  
## Exercise 5

- Export all the collections and save over the existing files
- Create a new branch
- Push