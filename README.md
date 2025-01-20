# CommerceX Shopify

## Overview
`commercex-shopify` is a Go package designed to provide a robust interface between CommerceX and Shopify. It acts as a wrapper around Shopify’s REST and GraphQL APIs, managing authentication, request handling, and response processing in a structured and efficient way.

## Features
- **Secure Connection Handling**: Manages authentication and securely stores Shopify API credentials.
- **REST API Wrapper**: Provides Go functions for interacting with Shopify’s REST API.
- **GraphQL API Wrapper**: Enables seamless integration with Shopify’s GraphQL API.
- **Request Handling & Error Management**: Implements standardized request handling with retries and exponential backoff.
- **Rate Limiting**: Ensures compliance with Shopify’s API rate limits.
- **Webhooks Management**: Supports subscribing to and processing Shopify webhooks.
- **Data Transformation**: Converts Shopify responses into Go structs for easy processing.
- **Scalability**: Designed to be lightweight and performant for large-scale commerce applications.

---

## Installation
To install the package, run:
```sh
go get github.com/commercexio/commercex-shopify
