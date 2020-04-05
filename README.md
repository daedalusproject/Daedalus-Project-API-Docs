# Daedalus-Core OpenAPI Specification
[![pipeline status](https://git.daedalus-project.io/docs/Daedalus-Core-Docs/badges/master/pipeline.svg)](https://git.daedalus-project.io/docs/Daedalus-Core-Docs/commits/master)[![Build Status](https://travis-ci.org/daedalusproject/Daedalus-Core-Docs.svg?branch=master)](https://travis-ci.org/daedalusproject/Daedalus-Core-Docs)

## Links

- [Reference Documentation (ReDoc)](https://daedalusproject.github.io/Daedalus-Core-Docs/)
- OpenAPI Raw Files: [JSON](https://daedalusproject.github.io/Daedalus-Core-Docs/openapi.json) [YAML](https://daedalusproject.github.io/Daedalus-Core-Docs/openapi.yaml)

## Docker Image

Release Image [![Release Image](https://img.shields.io/badge/docker-latest-blue.svg)](https://hub.docker.com/r/daedalusproject/daedalus-core-docs)

Develop [![Develop](https://img.shields.io/badge/docker-latest-yellow.svg)](https://hub.docker.com/r/daedalusproject/daedalus-core-docs-develop)

## Manual Install

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
