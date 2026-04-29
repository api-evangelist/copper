# Copper (copper)

Copper is a CRM platform built natively for Google Workspace, designed to help teams cultivate enduring client relationships through purposeful collaboration. The Copper Developer API is a RESTful JSON API providing programmatic access to People, Companies, Leads, Opportunities, Projects, Tasks, Activities, Webhooks, and related resources.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/copper/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party
- **x-type:** company

## Tags

- Activities, Companies, Contact Relationship Management, Contacts, CRM, Customer Relationship Management, Google Workspace, Leads, Opportunities, People, Projects, Sales, Tasks

## Timestamps

- **Created:** 2025-01-07
- **Modified:** 2026-04-28

## APIs

### Copper Developer API

The Copper Developer API is a RESTful JSON API providing programmatic access to Copper CRM resources including people, companies, leads, opportunities, projects, tasks, activities, and webhooks. Authentication uses three required headers (`X-PW-AccessToken`, `X-PW-Application`, `X-PW-UserEmail`). Standard rate limit is 180 requests per minute, with 3 requests per second for bulk operations.

**Human URL:** https://developer.copper.com/
**Base URL:** `https://api.copper.com/developer_api/v1`

#### Tags

- Activities, Companies, CRM, Leads, Opportunities, People, Projects, REST, Tasks, Webhooks

#### Properties

- [Documentation](https://developer.copper.com/)
- [Authentication](https://developer.copper.com/introduction/requests.html)
- [Getting Started](https://developer.copper.com/introduction/quick-start.html)
- [OAuth](https://developer.copper.com/introduction/oauth-quickstart.html)
- [Webhooks](https://developer.copper.com/webhooks/general/list-of-webhook-events.html)
- [Postman Collection](https://developer.copper.com/introduction/postman-collection.html)
- [OpenAPI](openapi/copper-developer-api-openapi.yml)
- [Rules](rules/copper-developer-api-rules.yml)
- [Capabilities](capabilities/copper-developer-api-capabilities.yml)
- [Vocabulary](vocabulary/copper-vocabulary.yml)
- [JSON-LD Context](json-ld/copper-context.jsonld)

## Capabilities

- Search and List CRM Records
- Manage Contact Records
- Capture and Convert Leads
- Track Sales Opportunities
- Manage Tasks
- Log Activities
- Subscribe to Webhooks

## Use Cases

- Sync contacts to marketing automation
- Inbound lead capture from web forms
- Sales pipeline reporting and forecasting
- Sales activity logging from email
- Real-time CRM event streaming

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
