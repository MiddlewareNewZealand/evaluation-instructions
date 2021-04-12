# Evaluation Instructions

## Introduction

The purpose of this exercise is to evaluate your approach to creating a very simple Node.js backend application. We expect you to spend no more than a couple of hours or less to complete this, and it will be used to evaluate how you approach a technical task.

## Sequence

1. Clone this repo `git clone https://github.com/MiddlewareNewZealand/evaluation-instructions.git`
2. Create a simple Node.js API that accepts an HTTP request
3. In this application make an HTTP request to a public service that we have defined
4. Transform the response so that it meets the specification defined in the [supplied OpenAPI specification](../openapi/evaluation.yaml). Note that the backend API is `xml` however we require the response to the client to be `json`.
5. Ensure that your code is appropriately tested
6. Publish your code to a source repository that we can access
7. Provide us with a link to this code at least a day before you come to see us.

## Evaluation Details

Create an application using any libraries you wish.
When a request is received make a request to the provided back end xml service. Parse the response and transform it to meet the [supplied OpenAPI specification](../openapi/evaluation.yaml)

## Things to consider

- You will need to tell us how you went about creating your applicaiton and why you created it in the way that you did.
- Think about how you would deploy the application into a production environment
- Think about how your application is documented - remember that your audience (us) are technical.
