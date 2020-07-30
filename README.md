# workflow-on-premise
### Setup
1. Log into docker registry: `docker login -u <ARTIFACTORY_USER_NAME> -p <ARTIFACTORY_API_KEY> signavio-on-premise.jfrog.io`
2. Create `.env` file by copying `.env.template` and adjust it to the environment
3. Start docker-compose `docker-compose up`