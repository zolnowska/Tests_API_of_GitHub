# Automation tests of GitHub API by use Postman and Newman


### Requirements:
* Windows 10
* Newman version 5.2.4
* An account on GitHub
* Personal access token to GitHub account with access to repo and delete_repo

### Pre-request
* In the file "Tests_API_of_GitHub.postman_environment.json" exchange value "YOUR_PERSONAL_TOKEN" into personal access token to GitHub acconut with access to repo and delete_repo
* In the file "Tests_API_of_GitHub.postman_environment.json" exchange value "NAME_OF_YOUR_GITHUB_ACC" into name of owner account to which belong personal access token from step above

### How to run tests
* Enter into folder where this repository is cloned and into cmd input this command: newman run "Tests_API_of_GitHub.postman_collection.json" -e "Tests_API_of_GitHub.postman_environment.json"
