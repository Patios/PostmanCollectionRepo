# PostmanCollectionRepo


npx newman run PostmanEcho.postman_collection.json -e TestEnvironment.postman_environment.json \
  --reporters cli,htmlextra,allure \
  --reporter-allure-resultsDir output/allure-results
