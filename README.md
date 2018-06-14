# serverless-aws-lambda
Simple typescript example deploying an AWS lambda function.

### Setup
```
npm i serverless -g
serverless config credentials --provider aws --key YOUR_ACCESS_KEY --secret YOUR_SECRET_KEY
npm install
```
### Local development
```
serverless offline start
```

### Deploy to AWS
```
serverless deploy
```

### Cleanup
```
serverless remove
```