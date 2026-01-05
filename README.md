# Bitasmbl-Weather-Dashboard-6ac4be-

## Description
Build a web application that displays current weather, multi-day forecasts, and visualizes trends with charts. The project focuses on integrating APIs, dynamic front-end updates, and data visualization for an interactive user experience.

## Tech Stack
- GraphQL
- ASP.NET Core
- React

## Requirements
- Fetch real-time weather data from a public API
- Display multi-day weather forecasts with clear UI elements
- Visualize temperature, humidity, or other metrics with charts
- Support user interactions, such as searching by city
- Optionally cache API responses to improve performance

## Installation
bash
git clone https://github.com/MrBitasmblTester/Bitasmbl-Weather-Dashboard-6ac4be-.git
cd Bitasmbl-Weather-Dashboard-6ac4be-
 
(backend)
bash
dotnet restore

(frontend)
bash
cd client
npm install


## Usage
Backend:
bash
dotnet run

Frontend:
bash
cd client
npm start


## Implementation Steps
1. Set up ASP.NET Core project and configure GraphQL schema for weather queries.
2. Integrate public weather API in ASP.NET Core and expose data through GraphQL resolvers.
3. Implement optional caching for API responses in the ASP.NET Core layer.
4. Create React app and configure GraphQL client to query ASP.NET Core endpoint.
5. Build React components for current weather and multi-day forecast display.
6. Add chart components in React to visualize temperature, humidity, or other metrics.
7. Implement city search UI in React and hook it to GraphQL queries.
8. Connect all views with dynamic updates based on GraphQL responses.

## API Endpoints
- GraphQL endpoint exposed by ASP.NET Core for weather data queries.