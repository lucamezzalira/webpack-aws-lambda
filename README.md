# webpack-aws-lambda
AWS Lambda that runs webpack and output the bundle.js file

## Lambda preparation process

First thing after cloning the project you need to run `npm update` in order to get the projet dependencies.    
Remember that all the npm modules needs to be relative to the project and not global. 
After that you will be able to package your projects (only the files inside the project folder, not the parent folder) and upload to AWS Lambda.     

## AWS Lambda configuration

![alt text](https://github.com/lucamezzalira/webpack-aws-lambda/raw/master/config.png "aws lambda configuration")      

## Live example

At [this link](https://5eu0sm5p5l.execute-api.us-west-1.amazonaws.com/prod) you can find the Webpack bundle output returned from a Lambda exposed via API Gateway    

it takes a while to get the response (around 15s when Lambda is cold)    