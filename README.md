# techtest


Karhoo SDET/QA Test

Exercise 1 to 3 should take no more then 1 hour. The last exercise should be timeboxed to 2 hours.

 
## Exercise 1 (Testing Postman part 1)
The "Get Auth Token" POST call is missing data. Using the API docs located here (https://docs.karhoo.com/v1/auth#auth) complete the following exercise:
- Git Clone this repo
- Import Exercise2.postman_collection.json
- Update the postman call to include the correct post parameters with the values of "interview_test@karhoo.com". The other parameter will be given on the day of the interview


## Exercise 2 (Testing Postman part 2)
Using Exercise2 complete the following:

- Update the "Get Auth Token" to save the value for "access_token" to a value called "bearer_token"
- Update "Get_Locations" using the api docs here (https://docs.karhoo.com/v1/locations?shell#address-autocomplete) with the valid body
  - Body should json object 
  - the key will be "query"
  - the value will be "London"
- Create a test that checks for the status code and the ensures we get an array of address returned

## Exercise 3 (Testing Git)

- Export all the collections and save over the existing files
- Create a new branch
- Push
- Pull in the branch "Rebase_Test" into your branch.
- Fix any conflicts and make sure it works
- Push it to your branch
- Open a pull request and submit!

## Exercise 4

- Using the site https://flit.tech and a framework of your choice:
  - Create a test scenario that navigates from the homepage to the karhoo team page
  - Clicks the apply button
  - Checks that you are on the bamboohr vacancies page
  - Once completed push into the github branch
