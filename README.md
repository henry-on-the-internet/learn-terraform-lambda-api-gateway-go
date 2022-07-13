# Learn Terraform - Lambda functions and API Gateway

AWS Lambda functions and API gateway are often used to create serverlesss
applications.

Follow along with this [tutorial on HashiCorp
Learn](https://learn.hashicorp.com/tutorials/terraform/lambda-api-gateway?in=terraform/aws).

# For developers on Linux and macOS

## initialize a module 
go mod init example.com/m
go mod tidy

## Remember to build your handler executable for Linux!
cd hello-world
GOOS=linux GOARCH=amd64 go build -o hello hello.go
zip hello.zip hello
