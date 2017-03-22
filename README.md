# webpack-aws-lambda
AWS Lambda that runs webpack and output the bundle.js file

## AWS Lambda configuration

![alt text](https://github.com/lucamezzalira/webpack-aws-lambda/raw/master/config.png "aws lambda configuration")      

## Live example

At [this link](https://5eu0sm5p5l.execute-api.us-west-1.amazonaws.com/prod) you can find the Webpack bundle output returned from a Lambda exposed via API Gateway    

it takes a while to get the response (around 15s when Lambda is cold)    