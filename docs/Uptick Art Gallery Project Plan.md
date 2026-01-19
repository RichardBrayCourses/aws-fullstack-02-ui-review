# Uptick Art Gallery Project

- Review UI (optional)

- UI login to Cognito

- Deploy AWS Cognito with CDK

- Deploy UI to AWS Cloudfront

- Initial API Server

- Move API server and Cloudfront to a registered domain (optional)

- Implement RDS Aurora (serverless) PostgreSQL Database

- Cognito Signup adds user to RDS Database

- UI Profile Page -> API Server saves/retrieves user nickname

- API Server Security
  (1) some routes are public
  (2) some routes require Cognito Authentication (must be logged in)
  (3) some routes require Cognito group membership

- Upload images

- Search and display images using Cloudfront as a cache for an S3 bucket
