# Eclipse Marketplace REST API Specifications

This project contains a working prototype of the next-generation REST API for the [Eclipse Marketplace](https://marketplace.eclipse.org). The Eclipse Marketplace provides thousands of plug-ins, solutions, and service offerings for the the Eclipse community. And the new REST API will provide intuitive, flexible access to essential Marketplace listings, metrics, and activity. 

# OpenAPI Specification, Documentation, and Client Libraries

The API is specified in this [OpenAPI 3.0 document](/models/Eclipse%20Marketplace%20API%20Specification.yaml). 

We will be publishing complete API documentation and client libraries on a developer portal, coming soon.

# Development Environment

The core specification in the [models folder](/models) is in standard OpenAPI 3.0 YAML format, and can be edited with any [avaiable OpenAPI 3.0 editor](https://openapi.tools).

Generators in the [gentargets folder](/gentargets) are a representative sample of service implementation scaffolds, client SDK libraries,  and documentation formats. These are created using the RepreZen/GenFlow framework with open source generators from RepreZen and OpenAPI-Tools/OpenAPI-Generator. You can use the included Maven and Gradle configuration files to generate these artifacts. 

The overall project is set up using [RepreZen API Studio for Eclipse](https://marketplace.eclipse.org/content/reprezen-api-studio), available on the Eclipse Marketplace for installation into a standard Eclipse IDE, or [API Studio Desktop](http://RZen.io/InstallOptions), a self-contained Eclipse RCP distribution. 
