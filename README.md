# Eclipse Marketplace Client API v2 OpenAPI Specification
[![Build Status](https://travis-ci.org/EclipseFdn/marketplace-rest-api-specs.svg?branch=master)](https://travis-ci.org/EclipseFdn/marketplace-rest-api-specs)

This project contains a working prototype of the next-generation REST API for the [Eclipse Marketplace](https://marketplace.eclipse.org). The Eclipse Marketplace provides thousands of plug-ins, solutions, and service offerings for the the Eclipse community. And the new REST API will provide intuitive, flexible access to essential Marketplace listings, metrics, and activity.

## Links

- [Reference Documentation (ReDoc)](https://eclipsefdn.github.io/marketplace-rest-api-specs/)
- [SwaggerUI](https://eclipsefdn.github.io/marketplace-rest-api-specs/swagger-ui/)
- OpenAPI Raw Files: [JSON](https://eclipsefdn.github.io/marketplace-rest-api-specs/openapi.json) [YAML](https://eclipsefdn.github.io/marketplace-rest-api-specs/openapi.yaml)

**Warning:** All above links are updated only after Travis CI finishes deployment

## Getting started
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

## Contributing

1. [Fork](https://help.github.com/articles/fork-a-repo/) the [eclipsefdn/marketplace-rest-api-specs](https://github.com/eclipsefdn/marketplace-rest-api-specs) repository
2. Clone repository: `git clone https://github.com/[your_github_username]/marketplace-rest-api-specs.git`
3. Create your feature branch: `git checkout -b my-new-feature`
4. Commit your changes: `git commit -m 'Add some feature' -s`
5. Push feature branch: `git push origin my-new-feature`
6. Submit a pull request

### Declared Project Licenses

This program and the accompanying materials are made available under the terms
of the Eclipse Public License v. 2.0 which is available at
http://www.eclipse.org/legal/epl-2.0.

SPDX-License-Identifier: EPL-2.0

## Related projects

### [EclipseFdn/solstice-assets](https://github.com/EclipseFdn/solstice-assets)

Images, less and JavaScript files for the Eclipse Foundation look and feel.

### [EclipseFdn/hugo-solstice-theme](https://github.com/EclipseFdn/hugo-solstice-theme)

Hugo theme of the Eclipse Foundation look and feel. 

## Bugs and feature requests

Have a bug or a feature request? Please search for existing and closed issues. If your problem or idea is not addressed yet, [please open a new issue](https://github.com/eclipsefdn/marketplace-rest-api-specs/issues/new).

## Author

**Christopher Guindon (Eclipse Foundation)**

- <https://twitter.com/chrisguindon>
- <https://github.com/chrisguindon>

**Martin Lowe (Eclipse Foundation)**

- <https://github.com/autumnfound>

**Ted Epstein (RepreZen)**

- <https://twitter.com/tedepstein>
- <https://github.com/tedepstein>

## Trademarks

* Eclipse® is a Trademark of the Eclipse Foundation, Inc.
* Eclipse Foundation is a Trademark of the Eclipse Foundation, Inc.

## Copyright and license

Copyright 2018 the [Eclipse Foundation, Inc.](https://www.eclipse.org) and the [marketplace-rest-api-specs authors](https://github.com/eclipsefdn/marketplace-rest-api-specs/graphs/contributors). Code released under the [Eclipse Public License Version 2.0 (EPL-2.0)](https://github.com/eclipsefdn/marketplace-rest-api-specs/blob/src/LICENSE).