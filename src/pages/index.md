---
title: Overview - Adobe Status API
description: This is the overview page of Adobe Status API
contributors:
  - https://github.com/adobe-rajat 
---

<Hero slots="heading, text"/>

# Adobe Status API Documentation

Adobe Status API's provide detailed information and real time updates about Adobe cloud products and services outage, disruption and maintenance events.

<Resources slots="heading, links"/>

#### Resources

* [Quickstart Guide](https://developer.adobe.com)
* [Adobe Status Github Repo](https://github.com/AdobeDocs/dev-site)

## Overview

This documentation provides instructions for Adobe Status 1.0 APIs. For working with Adobe Status APIs, see [Adobe Status API Documentation](https://github.com/AdobeDocs/dev-site).

Adobe Status API's provide detailed information and real time updates about Adobe cloud products and services outage, disruption and maintenance events. Use these API's to integrate into your own monitoring system or dashboards to view real time events from Adobe Status that can be filtered based on Product, Product Offering, Region, Environment(where available), Locale and Event types.

## Discover

<DiscoverBlock width="100%" slots="heading, link, text"/>

### Get Started

[Quickstart Guide](guides/)

Get started with the Adobe Status APIs.

<DiscoverBlock slots="heading, link, text"/>

### Guides

[Calculated Metrics API](guides/calculated_metrics_api/)

Returns information on the user's company that is necessary for making other Adobe Status API calls.

<DiscoverBlock slots="link, text"/>

[Segments API](guides/segments_api/)

Provides configuration guidance and best practices for the /segments endpoint.

<DiscoverBlock slots="link, text"/>

[Reporting Guide API](guides/reporting_api/)

Provides configuration guidance and best practices for the /reports endpoint.

<DiscoverBlock slots="link, text"/>

[Migrating from 1.4 to 2.0](guides/migrating/)

For help migrating from the 1.4 versions of the Status API to the newer and more capable /reports API.

<DiscoverBlock width="100%" slots="heading, link, text"/>

### API References

[Try the API](api/)

Try the Status API with Swagger UI. Explore, make calls, with full endpoint descriptions.

## Contributing

We encourage you to participate in our open documentation initiative, if you have suggestions, corrections, additions
or deletions for this documentation, check out the source from [this github repo](https://github.com/adobe/gatsby-theme-spectrum-example), and submit a pull
request with your contribution. For more information, refer to the [contributing page](support/contribute/).

## API Requests & Rate Limits

The timeout for API requests through adobe.io is currently *60 seconds*.

The default rate limit for an Adobe Status Company is *120 requests per minute*. (The limit is enforced as *12 requests every 6 seconds*).
When rate limiting is being enforced you will get `429` HTTP response codes with the following response body: `{"error_code":"429050","message":"Too many requests"}`
