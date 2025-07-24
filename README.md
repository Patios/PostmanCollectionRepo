# PostmanCollectionRepo

Purpose is to create project basing on Newman and Postman tools

sample run :

npx newman run PostmanEcho.postman_collection.json -e TestEnvironment.postman_environment.json \
  --reporters cli,htmlextra,allure \
  --reporter-allure-resultsDir output/allure-results

basing on results generate new files for report:

allure generate

start local server and show results:
allure open