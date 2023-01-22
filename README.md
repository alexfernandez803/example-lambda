# example-lambda for rendering video from lambda function

## How to Use

1. Clone the repository

2. Install the dependencies

```bash
npm install
```

3. Create the CDK stack

```bash
npx aws-cdk deploy \
  --outputs-file ./cdk-outputs.json
```

4. Open the AWS Console and find the lambda 
  
5. Cleanup

```bash
npx exec aws-cdk destroy
```
