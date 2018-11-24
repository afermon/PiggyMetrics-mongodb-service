# Piggy Metrics (Kubernetes) - Mongo DB image

[![CircleCI](https://circleci.com/gh/afermon/PiggyMetrics-mongodb-service.svg?style=svg)](https://circleci.com/gh/afermon/PiggyMetrics-mongodb-service) [![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/afermon/PiggyMetrics-mongodb-service/blob/master/LICENCE)

Each microservice has it's own database, so there is no way to bypass API and access persistance data directly. In this project, MongoDB is used as a primary database for each service. It might also make sense to have a polyglot persistence architecture (сhoose the type of db that is best suited to service requirements).

For more information please refer to the main repository [afermon/PiggyMetrics-Kubernetes](https://github.com/afermon/PiggyMetrics-Kubernetes)

## Credits

* Forked from [sqshq/PiggyMetrics](https://github.com/sqshq/PiggyMetrics)