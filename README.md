# OeVGK18 Backend OpenAPI Specification
[![Build Status](https://travis-ci.org/public-transport-quality-grades/backend-api.svg?branch=master)](https://travis-ci.org/public-transport-quality-grades/backend-api)

## Links

- Documentation(ReDoc): https://public-transport-quality-grades.github.io/backend-api/
- SwaggerUI: https://public-transport-quality-grades.github.io/backend-api/swagger-ui/
- Full spec:
    + JSON https://public-transport-quality-grades.github.io/backend-api/swagger.json
    + YAML https://public-transport-quality-grades.github.io/backend-api/swagger.yaml

**Warning:** All above links are updated only after Travis CI finishes deployment


## Working on specification
### Install

1. Install [Node JS](https://nodejs.org/)
2. `npm install -g yo`
3. `npm install -g generator-openapi-repo`
4. clone repo
5. `yo openapi-repo`

### Usage

1. start local flask server and go to http://localhost:5000/api/apispec.json
2. save apispec.json to `oevgk18-spec/`
3. delete `spec/swagger.yaml`
4. `yo generator-openapi-repo` and make sure not to override the README
5. push changes
