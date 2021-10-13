# AWS S3 Example
Simple Javascript Node example for uploading a text file to Amazon S3 after creating a bucket.

## Installation
1. Ensure you have programmatic access credentials set (Access Key ID & Secret Access Key) 
    - Edit the file `~/.aws/credentials` with your saved credentials. For Windows, it will be `C:\Users\<yourUserName>\.aws\credentials` or similar.
1. Fork this repository, clone and *change* into the project directory
1. Run `npm install` to install the aws-sdk.
1. Open main.js and follow the comment instructions

## Usage
1. `npm run upload`
1. Verify bucket and object creation 
    - in the AWS Management Console under S3
    - or via the AWS CLI 
      ```
      aws s3api list-buckets
      ```