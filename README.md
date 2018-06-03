# devchallenge.it---qa---2
Repository includes:
- JSON files with the tests OpenWeatherMapFull.postman_collection.json
- 0.Requests limits.postman_collection.json additional test for request limits
- openweathermap1.postman_environment.json file with environment
- Checklist.xlsx file with the all test cases
- Test Plan.docx file with Test Plan
- 0001.Test Summary Report.docx file with the test report
- Bugs.xlsx file with the bug reports
- test files and readme file. 

To run the tests your should set up Postman(https://www.getpostman.com/apps) After Postman run import JSON files(OpenWeatherMapFull.postman_collection.json, 0.Requests limits.postman_collection.json and openweathermap1.postman_environment.json) to it(Import as a file) Click on Runner and select a folder with the test scenarios you want to run:
- 0.Request limits. 2 tests should be run separatelly. To run "0.01No more 60 calls for free" in Runner you should select and upload "60 City.json" from test files, select file type "application/json", select "openweathermap1" environment and run the tests from this folder. Then you should repeat all activities with another test file "61 City.json" to check limit of requests for a folder "0.02More than 60 calls for free."
- To run the other tests you should select and upload Variables.json from tested files, select file type "application/json", select "openweathermap1" environment and run the tests from "OpenWeatherMapFull" folder.
