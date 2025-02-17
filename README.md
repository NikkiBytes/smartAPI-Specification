# The OpenAPI Specification

[![Build Status](https://travis-ci.org/OAI/OpenAPI-Specification.svg?branch=master)](https://travis-ci.org/OAI/OpenAPI-Specification)

![](https://avatars3.githubusercontent.com/u/16343502?v=3&s=200)


# Note

This is not an active work branch anymore but is currently kept around. For details on how to contribute next, review our [Development Guidelines](https://github.com/OAI/OpenAPI-Specification/blob/master/DEVELOPMENT.md).



---


The OpenAPI Specification is a community driven, open specification within the [Open API Initiative](https://www.openapis.org/), a Linux Foundation Collaborative Project.

The OpenAPI Specification (OAS) defines a standard, programming language-agnostic interface description for REST APIs, which allows both humans and computers to discover and understand the capabilities of a service without requiring access to source code, additional documentation, or inspection of network traffic. When properly defined via OpenAPI, a consumer can understand and interact with the remote service with a minimal amount of implementation logic. Similar to what interface descriptions have done for lower-level programming, the OpenAPI Specification removes guesswork in calling a service.

Use cases for machine-readable API definition documents include, but are not limited to, interactive documentation; code generation for documentation, clients, and servers; and automation of test cases. OpenAPI documents describe an API's services and are represented in either YAML or JSON formats. These documents may either be produced and served statically or be generated dynamically from an application.

The OpenAPI Specification does not require rewriting existing APIs. It does not require binding any software to a service—the service being described may not even be owned by the creator of its description. It does, however, require the capabilities of the service be described in the structure of the OpenAPI Specification. Not all services can be described by OpenAPI—this specification is not intended to cover every possible style of REST APIs. The OpenAPI Specification does not mandate a specific development process such as design-first or code-first. It does facilitate either technique by establishing clear interactions with a REST API.

This GitHub project is the starting point for OpenAPI.
Here you will find the information you need about the OpenAPI Specification, simple examples of what it looks like, and some general information regarding the project.

## Current Version - 3.0

The current version of the OpenAPI specification is [OpenAPI Specification 3.0](https://github.com/SmartAPI/smartAPI-Specification/blob/OpenAPI.next/versions/3.0.0.md).

### Previous Versions

This repository also contains the [OpenAPI Specification 2.0](https://github.com/SmartAPI/smartAPI-Specification/blob/OpenAPI.next/versions/2.0), which is identical to the Swagger 2.0 specification before it was renamed to “OpenAPI Specification”, 
as well as the Swagger 1.2 and Swagger 2.0 specifications.

Each folder in this repository, such as [examples](https://github.com/SmartAPI/smartAPI-Specification/blob/OpenAPI.next/examples) and [schemas](https://github.com/SmartAPI/smartAPI-Specification/blob/OpenAPI.next/schemas), should contain folders pertaining to the current and previous versions of the specification.

## See It in Action

If you just want to see it work, check out the [list of current examples](https://github.com/SmartAPI/smartAPI-Specification/blob/OpenAPI.next/examples/v3.0).

## Tools and Libraries

Looking to see how you can create your own OpenAPI definition, present it, or otherwise use it? Check out the growing
[list of 3.0 Implementations](https://github.com/SmartAPI/smartAPI-Specification/blob/OpenAPI.next/IMPLEMENTATIONS.md).

## Participation

The current process for development of the OpenAPI Specification is described in 
[Development Guidelines](https://github.com/SmartAPI/smartAPI-Specification/blob/OpenAPI.next/DEVELOPMENT.md).
Development of the next version of the OpenAPI Specification is guided by the [Technical Developer Community](https://www.openapis.org/participate/how-to-contribute/governance#TDC). This group of committers bring their API expertise, incorporate feedback from the community, and expand the group of committers as appropriate. All development activity on the future specification will be performed as features and merged into this branch. Upon release of the future specification, this branch will be merged to master.

The Open API Initiative encourages participation from individuals and companies alike. 
If you want to participate in the evolution of the OpenAPI Specification, consider taking the following actions:

* Review the [current specification](https://github.com/SmartAPI/smartAPI-Specification/blob/OpenAPI.next/versions/3.0.0.md). The human-readable markdown file _is the source of truth_ for the specification.
* Review the [development](https://github.com/SmartAPI/smartAPI-Specification/blob/OpenAPI.next/DEVELOPMENT.md) process so you understand how the spec is evolving.
* Check the [issues](https://github.com/OAI/OpenAPI-Specification/issues) and [pull requests](https://github.com/OAI/OpenAPI-Specification/pulls) to see if someone has already documented your idea or feedback on the specification. You can follow an existing conversation by adding a comment to the existing issue or PR.
* Create an issue to describe a new concern. If possible, propose a solution.

Not all feedback can be accommodated and there may be solid arguments for or against a change being appropriate for the specification.

## License


See: [License (Apache-2.0)](https://github.com/OAI/OpenAPI-Specification/blob/master/LICENSE)


![Analytics](https://ga-beacon.appspot.com/UA-831873-42/readme.md?pixel)
