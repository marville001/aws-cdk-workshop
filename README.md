# AWS CDK Repository

---

## What is AWS CDK? 

AWS CDK (Cloud Development Kit) is an open-source software development framework to define cloud infrastructure in code and provision it through AWS CloudFormation.

With AWS CDK, you can define your infrastructure in familiar programming languages such as TypeScript, JavaScript, Python, Java, C# and others. This allows you to create reusable components and libraries for your infrastructure, as well as apply software development best practices like version control, continuous integration and testing.

## Usage
This repository contains various examples and templates that you can use to get started with AWS CDK. The code examples cover a range of AWS services, and are organized into subdirectories based on the programming language used. Each example provides a README with instructions on how to deploy the infrastructure.


## Localstack
```bash

python3 -m pip install localstack==0.9.0

docker run --rm -it -p 4566:4566 -p 4571:4571 localstack/localstac

```