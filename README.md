# Shipwreck Report

## Overview

This project is a comprehensive tool designed for creating a report to help rescue people from shipwrecks by giving marine and general weather forecasts, route prediction, and potential medical diagnosis based on weather conditions and route of the ship. The project integrates weather data retrieval from the Open-Meteo API, route prediction, and health risk assessments due to weather impacts.

## Features

-   **Marine Weather Forecasting**: Fetches hourly wave height data using the Open-Meteo Marine API.
-   **General Weather Forecasting**: Fetches hourly temperature and wind speed data using the Open-Meteo Forecast API.
-   **Data Merging**: Combines marine and general weather data into a single DataFrame for comprehensive analysis.
-   **Route Prediction**: Predict possible marine routes that could have been taken by the ship based on last seen coordinates.
-   **Medical Diagnosis**: Provides potential medical diagnoses based on weather conditions, and route taken.
-   **Error Handling**: Utilizes caching and retry mechanisms to handle API request errors efficiently.

## Tools and Libraries Used

-   `requests-cache`: For caching API requests to improve performance and reduce redundant calls.
-   `retry-requests`: To handle retries and ensure robust API request handling.
-   `pandas`: For data manipulation and analysis.
-   `openmeteo-requests`: For interacting with the Open-Meteo API.
-   `numpy`: For numerical operations and data handling.
-   `matplotlib`: For visualizing data and results.
