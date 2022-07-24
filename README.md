# Hello, App Runner VPC Connector!

This is the code project for the [Hello, App Runner VPC Connector](https://davidpallmann.hashnode.dev/hello-app-runner-vpc-connector) blog post. 

This episode: AWS App Runner and VPC Connectors. In this Hello, Cloud blog series, we're covering the basics of AWS cloud services for newcomers who are .NET developers. If you love C# but are new to AWS, or to this particular service, this should give you a jumpstart.

In this post we'll introduce App Runner's VPC Connector feature and use it in a "Hello, Cloud" .NET program to access a DynamoDB table. We'll do this step-by-step, making no assumptions other than familiarity with C# and Visual Studio. We're using Visual Studio 2022 and .NET 6.

## Our Hello, App Runner VPC Connector Project

Our Hello, Cloud project uses App Runner and DynamoDB. We're going to create a .NET web API project, which generates a mock weather forecast API. We'll then upgrade that to read weather data from a DynamoDB table. We'll create our App Runner service with a VPC connector, and a VPC endpoint for our DynamoDB table, allowing them to connect. 

See the blog post for the tutorial to create this project and run it on AWS.

