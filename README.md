# JetBrains (jetbrains)
JetBrains is a software development company that provides integrated development environments, CI/CD tools, issue tracking, and team collaboration platforms for software developers. Their product suite includes IntelliJ IDEA, TeamCity, YouTrack, Space, Hub, and the JetBrains Marketplace, all of which offer APIs for programmatic integration and automation of development workflows.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/jetbrains/refs/heads/main/apis.yml)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - Developer Tools, IDE, CI/CD

## Timestamps

- **Created:** 2025-01-01 
- **Modified:** 2026-04-28 

## APIs

### JetBrains Space HTTP API
The JetBrains Space HTTP API provides programmatic access to Space functionality including projects, teams, chats, documents, code reviews, packages, and automation jobs. The API uses JSON format and supports OAuth 2.0 authentication. An HTTP API playground is available within Space for interactive exploration of all available endpoints.

**Human URL:** [https://www.jetbrains.com/help/space/http-api-model.html](https://www.jetbrains.com/help/space/http-api-model.html)


#### Tags:

 - Collaboration, Developer Tools, Project Management

#### Properties

- [Documentation](https://www.jetbrains.com/help/space/http-api-model.html)
- [OpenAPI](openapi/jetbrains-space-openapi.yml)
- [JSONSchema](json-schema/project.json)
- [JSONSchema](json-schema/user.json)
- [JSONLD](json-ld/jetbrains-context.jsonld)

### JetBrains TeamCity REST API
The TeamCity REST API provides programmatic access to TeamCity CI/CD server functionality. It allows management of projects, build configurations, builds, agents, VCS roots, users, and more. The API uses locators for flexible filtering and supports both JSON and XML formats. The full Swagger specification is available via the /app/rest/swagger.json endpoint.

**Human URL:** [https://www.jetbrains.com/help/teamcity/rest/teamcity-rest-api-documentation.html](https://www.jetbrains.com/help/teamcity/rest/teamcity-rest-api-documentation.html)


#### Tags:

 - CI/CD, Build Automation, Developer Tools

#### Properties

- [Documentation](https://www.jetbrains.com/help/teamcity/rest/teamcity-rest-api-documentation.html)
- [OpenAPI](openapi/jetbrains-teamcity-openapi.yml)
- [JSONSchema](json-schema/build.json)
- [JSONSchema](json-schema/build-agent.json)
- [JSONSchema](json-schema/project.json)
- [JSONLD](json-ld/jetbrains-context.jsonld)

### JetBrains YouTrack REST API
The YouTrack REST API lets you perform programmatic actions in the issue tracker, including creating, modifying, and querying issues, managing projects, agile boards, work items, and more. The API uses JSON format and supports both permanent token and OAuth 2.0 authentication. A Postman collection is available for interactive exploration.

**Human URL:** [https://www.jetbrains.com/help/youtrack/devportal/youtrack-rest-api.html](https://www.jetbrains.com/help/youtrack/devportal/youtrack-rest-api.html)


#### Tags:

 - Issue Tracking, Project Management, Developer Tools

#### Properties

- [Documentation](https://www.jetbrains.com/help/youtrack/devportal/youtrack-rest-api.html)
- [OpenAPI](openapi/jetbrains-youtrack-openapi.yml)
- [JSONSchema](json-schema/issue.json)
- [JSONSchema](json-schema/project.json)
- [JSONSchema](json-schema/user.json)
- [JSONLD](json-ld/jetbrains-context.jsonld)

### JetBrains Hub REST API
The JetBrains Hub REST API provides programmatic access to Hub, the centralized authentication and authorization service for JetBrains tools. It allows management of users, groups, projects, roles, permissions, and OAuth 2.0 services. Hub serves as the identity provider for YouTrack, TeamCity, and other connected JetBrains services.

**Human URL:** [https://www.jetbrains.com/help/youtrack/devportal/hub-rest-api-reference.html](https://www.jetbrains.com/help/youtrack/devportal/hub-rest-api-reference.html)


#### Tags:

 - Authentication, Authorization, Identity Management

#### Properties

- [Documentation](https://www.jetbrains.com/help/youtrack/devportal/hub-rest-api-reference.html)
- [OpenAPI](openapi/jetbrains-hub-openapi.yml)
- [JSONSchema](json-schema/user.json)
- [JSONLD](json-ld/jetbrains-context.jsonld)

### JetBrains Marketplace API
The JetBrains Marketplace API provides programmatic access to the plugin marketplace for JetBrains IDEs. It allows listing plugins by IDE compatibility, searching for plugins, uploading new plugins and updates, downloading plugin files, and checking plugin licenses. The API serves both plugin developers and consumers integrating with the JetBrains plugin ecosystem.

**Human URL:** [https://plugins.jetbrains.com/docs/marketplace/api-reference.html](https://plugins.jetbrains.com/docs/marketplace/api-reference.html)


#### Tags:

 - Marketplace, Plugins, Developer Tools

#### Properties

- [Documentation](https://plugins.jetbrains.com/docs/marketplace/api-reference.html)
- [OpenAPI](openapi/jetbrains-marketplace-openapi.yml)
- [JSONSchema](json-schema/plugin.json)
- [JSONLD](json-ld/jetbrains-context.jsonld)

## Common Properties

- [Documentation](https://www.jetbrains.com/help/)
- [Blog](https://blog.jetbrains.com/)
- [Support](https://www.jetbrains.com/support/)
- [Issues](https://youtrack.jetbrains.com/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
