# API Reference

## /put
`https://api.deployboard.io/put?app={app}&env={env}&version={version}&status={status}`  
Type: GET|POST  
Updates the information for the passed `{app}` and `{env}`.

## /get
`https://api.deployboard.io/get`  
Type: GET|POST  
Header: X-API-Key (Required)  
Returns all application data for the account associated with the API Key.

## /get/logs
`https://api.deployboard.io/get/logs?app={app}&env={env}`  
Type: GET|POST  
Header: X-API-Key (Required)  
Returns all deployment log data for the passed `{app}` and `{env}` within the account associated with the API Key.

## /badge
`api.deployboard.io/badge/{id}?env={env}`
Type: GET  
Queries DynamoDB for the latest version of {id} for environment {env}.  
Forward the request with the version along to this url: `https://img.shields.io/static/v1.svg?color=blue&label=version&message={version}`
