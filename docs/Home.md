# Home
This page provides a high-level overview of the Bazaarvoice Privacy API suitable for all audiences.

## Introduction

The Bazaarvoice Privacy API provides a secure HTTP interface for integrating Bazaarvoice into your General Data Protection Regulation (GDPR), California Consumer Privacy Act (CCPA), and other privacy regulations compliance workflows.

The Privacy API offers the following features:

- Request access to an end-user's personal data
- Request deletion of an end-user's personal data
- Retrieve information about pending requests

Continue reading to learn how the Privacy API helps you comply with privacy regulations.

##Privacy regulations compliance with the Privacy API

Privacy regulations require you to provide several rights to your end-users, including:

- **The right to be forgotten**
End-users have the right to request that their data be permanently deleted.
- **The right of access**
End-users have the right to request a copy of their data.
- **Data portability**
End-user’s should be able to transfer their data to other service providers.
These rights apply to the data you directly control, as well as data that Bazaarvoice processes on your behalf. The Bazaarvoice Privacy API allows you to comply with these privacy regulations requirements in the following ways:


Privacy API feature | Corresponding Right
---------|----------
 Request that Bazaarvoice delete an end-user’s personal data | Right to be forgotten 
 Request a copy of an end-user’s personal data | Right of access 
 Data provided as ZIP compressed files in JSON format | Data portability 

## Level of effort

Using an API is not the same as using a Bazaarvoice hosted application; You will be building your own application using data services provided by Bazaarvoice. The API returns data in a machine readable format, which you will incorporate into your own application which you must build, host and maintain. As result Bazaarvoice clients must have considerable technical resources and ability at their disposal to use this API.

### Technical requirements

Your team should have the following proficiencies:

- Web application development
- Client/server interaction based on the [HTTPS](https://tools.ietf.org/html/rfc2818) protocol
- The ability to process [JSON](http://www.json.org/)
- User authentication with [OAuth2](https://oauth.net/)
- Data storage and retrieval

### Team members

Your team should consist of at least the following:

- A developer familiar with the technical requirements above

Depending on the scope of your project your team may also need personnel with the following skills:

- Network engineering and administration
- Project management and planning
- Web and graphic design
- Software testing

## Next

Continue to [Getting Started](Getting-started.md).
