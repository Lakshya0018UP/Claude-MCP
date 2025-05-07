# Claude MCP Weather Data Fetching

This project provides a simple yet powerful weather data fetching server using the Model Context Protocol (MCP) with the `fastmcp` library. It fetches real-time weather alerts and forecasts from the National Weather Service (NWS) API, making it easy to integrate weather insights into your Claude MCP-based applications.

## Features
- Fetch active weather alerts for any US state.
- Get detailed weather forecasts for a specific location.
- Error handling for robust API interactions.
- Asynchronous design for high performance.

## Modules Used
- **httpx** - For making asynchronous HTTP requests to the NWS API.
- **mcp[cli]** - For building and running the MCP server.
- **uv** - Utility functions for various server operations.
