# Quality analysis and strategy - Testing exercise: TestScenario_eCommerce.xlsx
LIMITATIONS:
- The test scenarios does not cover all requirements due to limited timeline

NOTE
- We had a third party payment service agreement but unfortunately they don’t have a testing environment for us to integrate with. What will be your approach to test it? Answer is at E42
- Assume we need to create an Automation test suite driven via the UI, which scenarios will you automate? Answer is at F column
- What tools and technology will you use? Answer: QMetry, probably with BDD, Java, Maven, TestNG, Selenium, TeamCity, CI/CD, GIT or any JavaScript framework

ASSUMPTION
- Assume the third party is similar to Paypal in TS_006/ D42, D43

# Quality automation (API Test): API Test.postman_collection.json and data.csv
- Use Data Driven Testing with Postman using CSV covering both positive and nagative test cases. This approach has benefits in maintenance as From, To, Service code and Cost changes are easy in the csv file.
- After importing the json file to Postman, open Collection Runner, select the csv file and Run. The last 4 iterations should be failed as negative cases. 

- An alternative is to use this public link https://www.getpostman.com/collections/87438c81090cda5b6b7b

ASSUMPTION
- Restricted to domestic postage only




