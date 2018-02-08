** Check how dash works. pull info docs

# GraphQL Summit 2016

## Shopify

graphql-batch

* Ruby

### Mobile Clients

React Native => Not so possible to polish the UI yet. => Native mobile SDKs.

GraphQL Schema

=> Caching...

engineering.shopify.com

## Angular 2 with GraphQL

Mobile users are demanding => more content and fast, even without connection :-P

###Components and data

Concerns: Performance, consistency maintaninability.

GraphQL: an API query language

* Component based API
* Request per render
* graphql frst

Component based API

Single reqeust per single render

## GitHub

Platform interface team
* Interface to platform => GraphQL

Public API 1 month
* Feature gap for external developers
* Engagement => tooling documentation and on-boarding resources.

GaphiQL => GraphQL tool from GitHub

### Challenges
 * overhead of multiple schemas
 * security and privacy
 * versioning, behavioral and breaking changes.
 * instrumentation and monitoring

 github graphql-relay-walker: goes through the graphql schema, looking for ids that shouldn't be directly accessible.

 Atom integration with GraphQL GitHub API. => tools

## Designing transition to GraphQL Metheor (apolo)

First: Designing schema

Apollo client => GraphQL server => MongoDB, AWS (DB)

Backend => Generic, different type of apps, not overfit
Front End => Specific fields, computation lives on Server.

REST => update one field, you need to update all user end-points
GraphQL => udpate one field, update just one schema.

Sync between Backend and Front end is faster.

GraphQL Clients
* Plain fetch
* Apollo => Caching client

Static queries for perf and security

#### Performance monitoring with GraphQL
Know exactly wthich fields are being used and how
Field resolver Performance
Detect breaking shcma changes (break and crash :-P)

## Coursera
