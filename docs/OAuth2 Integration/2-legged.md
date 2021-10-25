# OAuth2 2-legged Workflow

This tutorial explains how to use OAuth2 with the Bazaarvoice Privacy API using a two-legged workflow, which authenticates directly between the OAuth2 API and your privacy application. If you want to require that a Bazaarvoice Portal user supply credentials to complete the authentication process, refer to the 3-legged OAuth2 workflow topic.

## Introduction

Bazaarvoice has implemented 2-legged OAuth2, an open standard for access delegation. This style of OAuth is referred to as “2-legged” because it consists of two roles:

**The Client Application**
This is an application that would like to access data or interact with a Bazaarvoice service.

**The OAuth2 API**
A Bazaarvoice service that implements the OAuth2 standard and intermediates with the Client Application.

2-legged OAuth2 offers certain advantages including:

- Authentication is handled server to client and does not require an end user to manually supply credentials.
- As a well-known open standard, OAuth2 is easier to implement than a custom solution.

Continue reading to learn how to use OAuth2 to access the supported Bazaarvoice APIs.