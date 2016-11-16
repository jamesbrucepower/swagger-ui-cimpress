![screenshot](screenshot.png)

[![Build Status](https://travis-ci.org/Cimpress-MCP/swagger-ui-cimpress.svg?branch=master)](https://travis-ci.org/Cimpress-MCP/swagger-ui-cimpress)
[![NPM version](https://badge.fury.io/js/swagger-ui-cimpress.svg)](http://badge.fury.io/js/swagger-ui-cimpress)
[![Dependency Status](https://david-dm.org/Cimpress-MCP/swagger-ui-cimpress/status.svg)](https://david-dm.org/Cimpress-MCP/swagger-ui-cimpress)
[![devDependency Status](https://david-dm.org/Cimpress-MCP/swagger-ui-cimpress/dev-status.svg)](https://david-dm.org/Cimpress-MCP/swagger-ui-cimpress#info=devDependencies)

# swagger-ui-cimpress

A swagger-ui fork with an easy to read, responsive three pane view. Used on https://developer.cimpress.io.

Swagger UI uses client-side Javascript (jQuery + Backbone) to download a swagger.json resource and make "Try It" requests to the described endpoints. You can learn more about the swagger-ui project at the upstream source: https://github.com/swagger-api/swagger-ui


## License

Apache-2.0

## Acknowledgement

This is a fork of https://github.com/jensoleg/swagger-ui which is a fork of https://github.com/swagger-api/swagger-ui

## Deploying

### Integration
```yarn build && yarn deploy:integration```

### Staging
```yarn build && yarn deploy:staging```

### Production
```yarn build && yarn deploy:production```