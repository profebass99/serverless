# Serverless App --Reminder

you are going to implement a simple serverless application using S3, API Gateway, Lambda, Step Functions, SNS & SES.  
The application will load from an S3 bucket and run in browser

.. communicating with Lambda and Step functions via an API Gateway Endpoint

Using the application you will be able to configure reminders for 'You and others' to be send using email and SMS.



It consists of 6 stages :-

- STAGE 1 : Configure Simple Email service 
- STAGE 2 : Add a email lambda function to use SES to send emails for the serverless application 
- STAGE 3 : Implement and configure the state machine, the core of the application
- STAGE 4 : Implement the API Gateway, API and supporting lambda function
- STAGE 5 : Implement the static frontend application and test functionality
- STAGE 6 : Cleanup the account.
