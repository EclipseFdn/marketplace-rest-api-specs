# Eclipse Marketplace Client API v2 OpenAPI Specification
[![Build Status](https://travis-ci.com/EclipseFdn/marketplace-rest-api-specs.svg?branch=master)](https://travis-ci.com/EclipseFdn/marketplace-rest-api-specs)

This project contains a working prototype of the next-generation REST API for the [Eclipse Marketplace](https://marketplace.eclipse.org). The Eclipse Marketplace provides thousands of plug-ins, solutions, and service offerings for the the Eclipse community. And the new REST API will provide intuitive, flexible access to essential Marketplace listings, metrics, and activity.

## Links

- [Reference Documentation (ReDoc)](https://eclipsefdn.github.io/marketplace-rest-api-specs/)
- [SwaggerUI](https://eclipsefdn.github.io/marketplace-rest-api-specs/swagger-ui/)
- OpenAPI Raw Files: [JSON](https://eclipsefdn.github.io/marketplace-rest-api-specs/openapi.json) [YAML](https://eclipsefdn.github.io/marketplace-rest-api-specs/openapi.yaml)

**Warning:** All above links are updated only after Travis CI finishes deployment

## Working on specification
### Install

1. Install [Node JS](https://nodejs.org/)
2. Clone repo and run `npm install` in the repo root

### Usage

#### `npm start`
Starts the development server.

#### `npm run build`
Bundles the spec and prepares web_deploy folder with static assets.

#### `npm test`
Validates the spec.

#### `npm run gh-pages`
Deploys docs to GitHub Pages. You don't need to run it manually if you have Travis CI configured.
