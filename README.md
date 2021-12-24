# insomnia-test

Using https://httpbin.org as the test API endpoint, this project demostrates some basic Insomnia REST features:

* Git Sync functionality of the `insomnia` desktop app
* Creating Insomnia Collections and Unit tests suites.
* CI automation using insomnia cli

NOTE: This project does not demostrates OpenAPI specification design features.

## Install Inso CLI

https://docs.insomnia.rest/inso-cli/install

```bash
npm install
```

## Integration Test: Insomnia "Unit" tests

https://docs.insomnia.rest/insomnia/unit-testing

Chaining requests: simulating a Login
https://github.com/Kong/insomnia/issues/2744


## Run tests

https://docs.insomnia.rest/inso-cli/cli-command-reference/inso-run-test

```bash
npm test
```

## CI config

https://docs.insomnia.rest/inso-cli/continuous-integration
