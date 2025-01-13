# Weather Dashboard

## Overview

The Weather Dashboard is a Python-based project that fetches real-time weather data for selected cities using the OpenWeather API and stores the data in an Amazon S3 bucket. This project demonstrates the integration of external APIs and AWS services to create a scalable and cloud-backed weather information application.

## Features

- Fetch real-time weather data for multiple cities using the OpenWeather API.

- Automatically create an S3 bucket if it does not already exist.

- Store weather data in JSON format in the S3 bucket with timestamped filenames.

- Gracefully handle API and AWS-related errors.