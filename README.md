# nestjs-aws-lambda-serverless

NestJS on AWS Lambda with Serverless Framework Template

## Getting Started

### Without Serverless

```
npm install
npm run start
```

## Test

- http://localhost:3000

### With Serverless

```
npm run start:sls
```

## Deploy

```
sls deploy
```

## Notes

### Fix sls offline error

`tscofig.json`

```
# from
"incremental": true
# to
"incremental": false

# add
"esModuleInterop": true
```
