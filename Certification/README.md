#Cerficaiton


Labs :   https://github.com/apigeekdemos/apijam


Direct link to this article: https://apigeek.page.link/learning-guide

Purpose of this Guide
The information in this guide will help you gain the knowledge necessary for design and development of APIs on Google Cloud's Apigee Edge platform. It will help you learn about API design and documentation best practices, as well as the features of the Apigee Edge platform.

API Engineer Certification
Please see the API Engineer Certification page for a description of the API Engineer Certification. The information referenced in this document will be useful if you intend to take the API Engineer Certification exam.

The certification exam will test your familiarity with and knowledge of topics related not only to the Apigee Edge platform, but also API design and documentation best practices. Google Cloud's Apigee team provides thought leadership about all of these topics via ebooks, videos, and blogs, as well as the documentation provided on our website. A study guide with a high-level list of topics can also be found on the certification page.

This community post describes the exam-taking process.

Apigee API Engineer Training
Apigee API Engineer training, whether taken via in-person developer bootcamps or the online Coursera training, will help you learn many of the topics you will need to know to develop on the Apigee Edge platform.

This training will also be useful if you intend to take the API Engineer certification. Your training will not include all topics that are tested on the Apigee API Engineer Certification exam. For example, your training may not contain Microgateway, OpenAPI Specification 2.0, and command line deployment concepts, as well as best practices learned from Apigee's eBooks, webcasts, and blogs.

Apigee API Program Excellence Course
The Apigee API Program Excellence e-learning course on Youtube teaches you about what is required to build a great API Program. This course teaches you what Apigee's Digital Engagement Lead team does, and is recommended for API Engineers who are interested in expanding beyond the technical aspects of API Management into the business and strategy aspects of API programs.

Topics
This document lists most of the important topics useful for an Apigee API Engineer, presenting links to the content with short descriptions. The information is organized by topic. At the end of this document is a List of Resources by Source, which will provide the same links organized by source. Note: Apigee API Engineer training will cover many of these topics, and some of the webcasts and eBooks will cover topics also explained in the online docs.

Getting Started
Certain resources should be viewed by every Apigee API developer. If you are just getting started with Apigee, these will give you a good foundation. Even if you are an experienced Apigee developer, you may find important concepts in these materials.

Note: Each of these documents is also listed in the topic-specific sections below.

Getting Started with Apigee API Management - Video tutorials for getting started with Apigee API management.

API Design: Third Edition - A classic webcast discussing API design patterns.

Understanding APIs and API Proxies - Overview of APIs and proxies.

Understanding organizations - Describes the components that make up an Apigee Edge organization.

Understanding routes - Overview of routes, which determine which TargetEndpoint will be used.

About Virtual Hosts - Overview of virtual hosts. Also see Virtual Host Property Reference.

Controlling how a proxy executes with flows - Explains the flow of a call through a proxy.

What is an API product?

Analytics Services overview

OAuth: The BIG Picture - Overview of when, how, and why to use OAuth.

Best practices for API proxy design and development - A great list of best practices to follow when designing API proxies. Be sure to drill down into links you find in this document.

Glossary - Glossary of Apigee Edge terms.

General Resources
Apigee Online Docs - Official documentation for Apigee.

Apigee eBooks - Free eBooks on API development topics.

Apigee Webcasts - Webcasts on all topics related to Apigee Edge and APIs.

Apigee 4 minute videos for developers (4MV4D) - Short videos on Apigee Edge and API development topics.

Apigee Community - Community for asking and answering questions related to Apigee Edge and API development.

API Jam - Repository of a one-day lab showing the full lifecycle of an API.

API Design Best Practices
API Design: Third Edition - A classic webcast discussing API design patterns.

Web API Design: The Missing Link - API design best practices - an excellent overview of API design concepts.

Pragmatic REST: The Next Generation - A webcast discussion of pragmatic REST concepts.

API Facade Pattern - Description of the façade pattern that can be implemented using Apigee Edge.

Apigee Edge Anti-Patterns - Some useful anti-patterns and solutions for Apigee Edge development. I recommend downloading the Anti-Patterns ebook that can be found at this link.

OpenAPI Specification 2.0 and API Documentation Best Practices
Create an API proxy from an OpenAPI Specification - Tutorial to create a proxy from an OpenAPI spec.

Best Practices for Defining an API Specification

Edge Policies
Policy reference overview - Top level index of all policy reference pages. Drill down into the policy-specific pages to see the options available for each Edge policy, as well as when each policy should be used.

JavaScript object model - Object model for JavaScript policies, including access to flow variables.

Comparing Quota, Spike Arrest, and Concurrent Rate Limit Policies

OAuthV2 policy

JWT policies

SAML Assertion policies

How to create a Java callout - Cookbook for creating a callout.

Policy error reference - Error messages and flow variables set when policy errors occur.

Edge Proxy Design
Getting Started with Apigee API Management - Video tutorials for getting started with Apigee API management.

Understanding APIs and API Proxies - Overview of APIs and proxies.

API proxy configuration reference - Reference of proxy structure.

Endpoint properties reference - ProxyEndpoint and TargetEndpoint configuration properties.

Variables reference - Predefined variables available within proxies.

Conditions reference - Conditions enable dynamic control of proxies.

About message templates - String substitution via variables and functions within policies and endpoint elements. Also see Message template function reference.

Understanding organizations - Describes the components that make up an Apigee Edge organization.

Best practices for API proxy design and development - A great list of best practices to follow when designing API proxies. Be sure to drill down into links you find in this document.

Understanding routes - Overview of routes, which determine which TargetEndpoint will be used.

About Virtual Hosts - Overview of virtual hosts. Also see Virtual Host Property Reference.

Controlling how a proxy executes with flows - Explains the flow of a call through a proxy.

Managing proxy state with flow variables - Description of use of flow variables in proxies.

Handling faults - Description of fault handling in Edge.

Working with key value maps - Includes encrypted and unencrypted KVMs.

Support for HTTP response header (ResponseCache) - Use of caching headers.

Working with cache keys - Cache key details.

Cache internals - Implementation of caches in Edge.

Reusable shared flows - How to create and use shared flows for code reuse. Also see Attaching a shared flow using a flow hook.

Chaining API proxies together - Tutorial on proxy chaining.

Implementing HTTP Clients in JavaScript - Describes how to use JavaScript to make http calls.

Glossary - Glossary of Apigee Edge terms.

Error Handling Pattern for Proxies - Describes a clean way to handle creation of error messages within your proxy.

API Products, Developers, and Apps
Create API products - Also see What is an API product?

Managing app developers

Register apps and manage API keys

Making sense of API product configuration

Edge Node.js (Trireme-based)
Overview of Node.js on Apigee Edge - Introduction of Node.js targets on Edge.

Node.js - Extending the Programmability of the Apigee Edge - Webcast about creating a node.js target.

npm apigee-access - Node module allows access to Apigee-specific features from within Node apps hosted in Edge.

Edge Analytics
Analytics Services overview

Analytics dashboards - List of dashboards available out-of-the-box.

Using the analytics dashboards - Use of the Edge Analytics UI. Also see

Build and Implement your API Analytics Strategy - Webcast overview of Edge Analytics.

Analytics metrics, dimensions, and filters reference

Edge Troubleshooting and Debugging
Using the Trace tool - Using the trace tool for debugging proxy issues.

Troubleshooting Playbooks - Guides for troubleshooting Edge, and troubleshooting FAQs.

Apigee Troubleshooting Videos - Videos to help with common troubleshooting scenarios.

Policy Error Playbooks - Complete error description and troubleshooting guidance for Edge runtime and deployment policy errors.

Edge Deployment and Environment Promotion
API development lifecycle - Overview of API Lifecycle using Edge environments.

npm apigeetool - Node tool for deploying proxies and other resources to Edge.

Edge Developer Portal
There are two types of developer portals: Drupal-based and integrated. The Drupal-based portal is more powerful, and the integrated portal is easier to use.

What is a developer portal? - Overview of developer portals.

Differences between the Drupal and integrated developer portals

Drupal developer portal FAQ

Integrated developer portal documentation

Edge Monetization
Understand monetization - Summary of the monetization feature available in Apigee Edge. Drill down into other monetization topics in the docs.

API Security Topics and Best Practices
OAuth2 - This is the landing page for a wealth of topics on OAuth 2. Drill down into those topics.

API keys - An overview of API key validation for APIs.

OAuth: The BIG Picture - Overview of when, how, and why to use OAuth.

How to Integrate with Different Identity Management Systems - Identity management integration using Edge.

Advanced Security Extensions in Apigee Edge - Webcast includes discussion of JWT tokens. This webcast was created before the JWT policies were available in Edge.

OWASP Best Practices to Protect Your APIs from Security Vulnerabilities - Webcast discussing using Edge to protect against OWASP vulnerabilities.

About TLS/SSL - Description of one-way and two-way SSL/TLS terminology and flows.

Keystores and Truststores - Description of keystores and truststores used for SSL/TLS communication.

Data masking and hiding - Description of features in Edge that control visibility of data in logs and tracing.

Using Third-Party OAuth Tokens - How to use third-party OAuth tokens within Apigee.

API Lifecycle Topics and Best Practices
A Checklist for Every API Call - Topics to be considered for every API.

Digital Business Survival Guide - Guide to building an API program.

The Digital Transformation Journey - Insights into digital transformations of several companies.

Continuous Integration for API Proxies - Overview of continuous integration for APIs.

Forming an API Test Strategy - Where to Start - Getting started with API testing.

Edge Microgateway
Apigee Edge Microgateway - A webcast describing the features of and demoing Microgateway.

Developing custom plugins - Step-by-step for developing custom Microgateway plugins.

Edge Microgateway FAQ

Edge Hosted Targets (native Node.js targets)
Hosted Targets overview

Hosted Targets tutorials

Hosted Targets reference

Hosted Targets FAQ

List of Resources by Source
Apigee Online Docs
Understanding APIs and API Proxies
API proxy configuration reference
Endpoint properties reference
Variables reference
Conditions reference
About message templates
Message template function reference
Policy error reference
Understanding organizations
Best practices for API proxy design and development
Policy reference overview
JavaScript object model
About TLS/SSL
Keystores and Truststores
Understanding routes
About Virtual Hosts
Virtual Host Property Reference
Controlling how a proxy executes with flows
Managing proxy state with flow variables
Handling faults
Working with key value maps
Support for HTTP response header (ResponseCache)
Working with cache keys
Cache internals
Reusable shared flows
Attaching a shared flow using a flow hook
Chaining API proxies together
OAuth2
API keys
Create API products
What is an API product?
Managing app developers
Register apps and manage API keys
Comparing Quota, Spike Arrest, and Concurrent Rate Limit Policies
OAuthV2 policy
JWT policies
SAML Assertion policies
Data masking and hiding
Implementing HTTP Clients in JavaScript
How to create a Java callout
Create an API proxy from an OpenAPI Specification
API development lifecycle
Using the Trace tool
Troubleshooting Playbooks
Analytics metrics, dimensions, and filters reference
Analytics Services overview
Analytics dashboards
Using the analytics dashboards
What is a developer portal?
Understand monetization
Edge Microgateway FAQ
Hosted Targets overview
Hosted Targets tutorials
Hosted Targets reference
Hosted Targets FAQ
Developing custom plugins
Policy Error Playbooks
Differences between the Drupal and integrated developer portals
Integrated developer portal documentation
Apigee Edge Anti-Patterns
Using Third-Party OAuth Tokens
Apigee eBooks
Web API Design: The Missing Link
OAuth: The BIG Picture
A Checklist for Every API Call
Digital Business Survival Guide
The Digital Transformation Journey
API Facade Pattern
Apigee Webcasts
Getting Started with Apigee API Management
How to Integrate with Different Identity Management Systems
Advanced Security Extensions in Apigee Edge
OWASP Best Practices to Protect Your APIs from Security Vulnerabilities
Build and Implement your API Analytics Strategy
Apigee Edge Microgateway
API Design: Third Edition
Pragmatic REST: The Next Generation
Node.js - Extending the Programmability of the Apigee Edge
Apigee Community
Making sense of API product configuration
Continuous Integration for API Proxies
Forming an API Test Strategy - Where to Start
Best Practices for Defining an API Specification
Error Handling Pattern for Proxies

Github
API Jam
Youtube videos
4 minute videos for developers
Apigee Troubleshooting Videos
Apigee API Program Excellence Course
Other links
npm apigeetool
npm apigee-access


