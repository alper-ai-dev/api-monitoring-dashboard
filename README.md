# API Monitoring Dashboard

A portfolio project for monitoring public HTTP/HTTPS services from a clean web dashboard.

## Features
- Check multiple services from one dashboard
- HTTP status code reporting
- Server-side response-time measurement
- Online/offline status
- Last-check timestamp
- Add custom public endpoints
- Browser persistence with localStorage
- Responsive interface
- Serverless monitoring endpoint
- Basic SSRF protection against private/local network targets

## Architecture
Static HTML/CSS/JavaScript frontend + Node.js serverless function (`/api/check`). The server validates target URLs, rejects private/local network addresses, applies an 8-second timeout, performs the HTTP request and returns normalized monitoring data.

## Deployment
Designed for Vercel deployment. No API key or environment variable is required.

## Stack
JavaScript, HTML5, CSS3, Node.js, Serverless Functions, Fetch API, DNS validation, Vercel.

## Portfolio
Built as a software-development portfolio project demonstrating API integration, backend/serverless development, monitoring logic, responsive UI and security-aware URL validation.