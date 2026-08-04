# JetBrains (jetbrains)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

JetBrains is a software development company that provides integrated development environments, CI/CD tools, issue tracking, and team collaboration platforms for software developers. Their product suite includes IntelliJ IDEA, TeamCity, YouTrack, Space, Hub, and the JetBrains Marketplace, all of which offer APIs for programmatic integration and automation of development workflows.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/jetbrains/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/jetbrains/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- CI/CD
- Developer Tools
- IDE

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### JetBrains Space HTTP API

The JetBrains Space HTTP API provides programmatic access to Space functionality including projects, teams, chats, documents, code reviews, packages, and automation jobs. The API uses JSON format and supports OAuth 2.0 authentication. An HTTP API playground is available within Space for interactive exploration of all available endpoints.

- **Human URL:** [https://www.jetbrains.com/help/space/http-api-model.html](https://www.jetbrains.com/help/space/http-api-model.html)

#### Tags

- Collaboration
- Developer Tools
- Project Management

#### Properties

- [Documentation](https://www.jetbrains.com/help/space/http-api-model.html)
- [OpenAPI](openapi/jetbrains-space-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jetbrains-space.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jetbrains-space.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/project.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/user.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/jetbrains-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### JetBrains TeamCity REST API

The TeamCity REST API provides programmatic access to TeamCity CI/CD server functionality. It allows management of projects, build configurations, builds, agents, VCS roots, users, and more. The API uses locators for flexible filtering and supports both JSON and XML formats. The full Swagger specification is available via the /app/rest/swagger.json endpoint.

- **Human URL:** [https://www.jetbrains.com/help/teamcity/rest/teamcity-rest-api-documentation.html](https://www.jetbrains.com/help/teamcity/rest/teamcity-rest-api-documentation.html)

#### Tags

- Build Automation
- CI/CD
- Developer Tools

#### Properties

- [Documentation](https://www.jetbrains.com/help/teamcity/rest/teamcity-rest-api-documentation.html)
- [OpenAPI](openapi/jetbrains-teamcity-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jetbrains-teamcity.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jetbrains-teamcity.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/build.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/build-agent.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/project.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/jetbrains-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### JetBrains YouTrack REST API

The YouTrack REST API lets you perform programmatic actions in the issue tracker, including creating, modifying, and querying issues, managing projects, agile boards, work items, and more. The API uses JSON format and supports both permanent token and OAuth 2.0 authentication. A Postman collection is available for interactive exploration.

- **Human URL:** [https://www.jetbrains.com/help/youtrack/devportal/youtrack-rest-api.html](https://www.jetbrains.com/help/youtrack/devportal/youtrack-rest-api.html)

#### Tags

- Developer Tools
- Issue Tracking
- Project Management

#### Properties

- [Documentation](https://www.jetbrains.com/help/youtrack/devportal/youtrack-rest-api.html)
- [OpenAPI](openapi/jetbrains-youtrack-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jetbrains-youtrack.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jetbrains-youtrack.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/issue.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/project.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/user.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/jetbrains-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### JetBrains Hub REST API

The JetBrains Hub REST API provides programmatic access to Hub, the centralized authentication and authorization service for JetBrains tools. It allows management of users, groups, projects, roles, permissions, and OAuth 2.0 services. Hub serves as the identity provider for YouTrack, TeamCity, and other connected JetBrains services.

- **Human URL:** [https://www.jetbrains.com/help/youtrack/devportal/hub-rest-api-reference.html](https://www.jetbrains.com/help/youtrack/devportal/hub-rest-api-reference.html)

#### Tags

- Authentication
- Authorization
- Identity Management

#### Properties

- [Documentation](https://www.jetbrains.com/help/youtrack/devportal/hub-rest-api-reference.html)
- [OpenAPI](openapi/jetbrains-hub-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jetbrains-hub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jetbrains-hub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/user.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/jetbrains-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### JetBrains Marketplace API

The JetBrains Marketplace API provides programmatic access to the plugin marketplace for JetBrains IDEs. It allows listing plugins by IDE compatibility, searching for plugins, uploading new plugins and updates, downloading plugin files, and checking plugin licenses. The API serves both plugin developers and consumers integrating with the JetBrains plugin ecosystem.

- **Human URL:** [https://plugins.jetbrains.com/docs/marketplace/api-reference.html](https://plugins.jetbrains.com/docs/marketplace/api-reference.html)

#### Tags

- Developer Tools
- Marketplace
- Plugins

#### Properties

- [Documentation](https://plugins.jetbrains.com/docs/marketplace/api-reference.html)
- [OpenAPI](openapi/jetbrains-marketplace-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jetbrains-marketplace.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jetbrains-marketplace.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/plugin.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/jetbrains-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Common Properties

- [GitHub Organization](https://github.com/jetbrains)
- [LinkedIn](https://www.linkedin.com/company/jetbrains)
- [Documentation](https://www.jetbrains.com/help/)
- [Blog](https://blog.jetbrains.com/)
- [Support](https://www.jetbrains.com/support/)
- [Issues](https://youtrack.jetbrains.com/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
