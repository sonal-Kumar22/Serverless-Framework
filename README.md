# Serverless Framework
Serverless Framework and AWS 

1.command to print yaml file in terminal :
  serverless print --stage dev

2.Remove your service
  serverless remove
  
3.Command to install serverless framework : npm install -g serverless
https://www.serverless.com/framework/docs/providers/fn/guide/installation#:~:text=Fn%20%2D%20Installation&text=Open%20up%20a%20terminal%20and,g%20serverless%20to%20install%20Serverless.

4.Create an IAM role which has access to create resources in AWS :
  - aws configure
  
5.Command to create a service in the current working directory : serverless create --template aws-python3
  https://www.serverless.com/framework/docs/providers/aws/cli-reference/create

6.command to create stack : serverless deploy --stage dev (stage is optional)


