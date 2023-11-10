# Serverless
Serverless web application
I have created a new cloud9 instance and EC2 instance in AWS.
In the cloud9 terminal uploaded all the backend and frontend code then checked for all the code.
Created Lambda functions for both delete details.

Step 3: Create a Lambda Function
1. Create a Lambda Function:
   - Go to the AWS Management Console and search for "Lambda".
   - Click "Create function".
   - Choose "Author from scratch".
   - Give your function a name and select the runtime .
   - Click "Create function".

2. Code Your Lambda Function:
   - In the Lambda function editor, paste the code you want to run. 
   - Configure the function handler and required permissions.
   - Save the function.

 Step 4: Create a REST API with API Gateway
1. Create an API:
   - Go to the AWS Management Console, search for "API Gateway", and open it.
   - Click "Create API".
   - Choose the type of API (REST ).
   - Select "New API" and give it a name.

2. Create a Resource and Method:
   - Define a resource and method for your API.
   - Configure the integration with your Lambda function to handle the respective method.

3. Deploy the API:
   - Deploy the API to a stage to make it live.
   - Obtain the endpoint URL.
