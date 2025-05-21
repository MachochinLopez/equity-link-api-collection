# Equity Link API Collection

This repository contains the API collection for the Equity Link backend app. The collection is available in two formats:

1. Bruno Collection (`.bru` files)
2. Postman Collection (`.json` file)

## Getting Started

### Using Bruno

If you're familiar with Bruno, you can directly open the `.bru` files in your Bruno client. Bruno is a lightweight, fast, and modern API client that helps you test and document your APIs.

To get started with Bruno:
1. Download Bruno from [bruno.run](https://www.bruno.run)
2. Open Bruno and import the collection files

### Using Postman

If you prefer using Postman or are not familiar with Bruno, you can use the `Equity Link Api Collection.json` file:

1. Open Postman
2. Click on "Import" in the top left corner
3. Drag and drop the `Equity Link Api Collection.json` file or click "Upload Files" to select it
4. The collection will be imported with all requests and environments

## Collection Structure

The API collection is organized into different folders based on functionality. Each request includes:
- Required headers
- Request body (where applicable)
- Example responses
- Environment variables

## Environment Variables

Make sure to set up the following environment variables in your client:
- `base_url`: The base URL of your API
- `token`: Your authentication token (if required)
