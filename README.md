# Evaluation Instructions

## Introduction

The purpose of this exercise is to evaluate your approach to creating a very simple Node.js or .NET backend application. We expect you to spend a couple of hours or less to complete this, and it will be used to evaluate how you approach a technical task.

The diagram below illustrates what it is that you will need to build. In simple terms, we expect you to build a very simple application that connects to a static XML API and transforms it to a JSON response. There are more detailed instructions provided below.

![Component Overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/MiddlewareNewZealand/evaluation-instructions/main/images/components.puml)

## Sequence

1. Read these instrucitons carefully.
2. Develop a simple Node.js or .NET API (see [Evaluation Details](#-Evaluation-details))
3. Publish your code to a source repository that we can access
4. Provide us with a link to this code at least a day before you come to see us

## Evaluation details

- Create an application using any libraries you wish
- When a request is received by the application, make another request to the existing static backend xml service - see curl examples below.

  ```bash
  curl https://raw.githubusercontent.com/MiddlewareNewZealand/evaluation-instructions/main/xml-api/1.xml
  ```

  ```bash
  curl https://raw.githubusercontent.com/MiddlewareNewZealand/evaluation-instructions/main/xml-api/2.xml
  ```

- Transform the backend xml response into a json format that matches the [supplied OpenAPI specification](./openapi-companies.yaml) and return it to the client
- Ensure that the application code handles errors from the xml service appropriately
- Ensure that the application code is tested appropriately

## Things to consider

When you come to see us you will need to consider the following so that we can chat about what you have done.

- You will need to tell us how you went about creating your application and why you created it in the way that you did
- Think about how you would deploy the application into a production environment
- Think about how your application is documented - remember that your audience (us) are technical and should be able to run your code

## Resources

- [Your API OpenAPI specification](./openapi-companies.yaml)
- [Existing XML API OpenAPI specification](./xml-api/openapi-xml.yaml)
- Existing XML API curl example

  ```bash
  curl https://raw.githubusercontent.com/MiddlewareNewZealand/evaluation-instructions/main/xml-api/1.xml
  ```

  ```bash
  curl https://raw.githubusercontent.com/MiddlewareNewZealand/evaluation-instructions/main/xml-api/2.xml
  ```
