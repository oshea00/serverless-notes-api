# Serverless-built Notes Backend on AWS

## API for a simple note taking backend.

Uses AWS SDK for hosting via API Gateway, Lambda,
and DynamoDb.
* api folder

CI/CD Pipeline using AWS Code Commit, Code Build and Code Deploy.
* `buildspec.yml`

Uses Serverless.com framework to deploy to Cloudfront and
support development and local testing of API code via:
* `serverless create -t aws-nodejs -p sls-notes-backend`
  - serverless.yml
* `serverless deploy -s dev`
* `serverless offline`




