# Getting Started

This page describes the fundamental knowledge that you will need to use the Privacy API.

## Privacy API & end-user data files

To process end-user requests you will interact with the following service components:

**Privacy API**

The Privacy API presents a “REST” style HTTP interface that exposes two resources: accessRequests and forgetRequests. When an API request is made to one of these resources, the API will create the appropriate resource in our system, respond with meta-data about the resource, including the status of previous requests and, in the case of an accessRequests, the location where the end-user data files can be retrieved.

**End-user data files**

---
**Note**
All the relevant data to Curalate client would be available in the ZIP folder with the prefix Curalate
---