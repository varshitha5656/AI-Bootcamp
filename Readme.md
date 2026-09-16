# PROJECT 1
# 🌦️ Weather Information Checker

A beginner-friendly Python project that uses the OpenWeatherMap API to fetch real-time weather information for a city.

## 📌 About the Project

This project was built as part of my AI Bootcamp while learning the fundamentals of APIs and API integration with Python.

The application takes a city name from the user, sends a request to the OpenWeatherMap API, receives the weather data in JSON format, and extracts useful information from the response.

## ✨ Features

- Enter any city name
- Fetch real-time weather information
- Display city name
- Display temperature in Celsius
- Display humidity
- Display current weather condition
- Handle invalid city names

## 🛠️ Technologies Used

- Python
- Requests Library
- OpenWeatherMap API
- JSON
- Google Colab

## 🔄 How It Works

User enters city name
        ↓
Python sends GET request
        ↓
OpenWeatherMap API
        ↓
JSON response
        ↓
Python extracts required data
        ↓
Weather information is displayed

**# PROJECT 2**
# 🎬 Movie Discovery & Information App

A beginner-friendly Python project that uses the TMDB API to search for movies and get information about them.

I built this project as part of my AI Bootcamp while learning how APIs work, how to send requests, and how to work with JSON responses.

## ✨ What can it do?

- 🔎 Search for a movie by name
- 🎬 Get movie details from TMDB
- ⭐ View the movie's rating
- 📅 View the release date
- 📝 View the movie overview
- 📦 Work with data returned in JSON format

## 🛠️ Technologies Used

- Python
- Requests
- TMDB API
- JSON
- Google Colab

## 🔄 How it works

The basic flow is:

**Enter movie name → Send API request → TMDB returns JSON → Extract movie details → Display the information**

For example, if I enter `Baahubali`, the program sends the movie name to the TMDB API and receives information about matching movies.

## 🧠 What I learned

While building this project, I learned:

- How to work with a movie API
- How API keys are used for authentication
- How to send GET requests using Python
- How to pass parameters with an API request
- How to read and navigate JSON data
- How lists and dictionaries are structured inside API responses
- How to extract specific information from nested JSON

One thing I learned the hard way was that API responses don't always have the data exactly where you expect it. For example:

python:
data["results"][0]["overview"]

Here, results contains the movies, [0] selects the first movie, and overview gets the description of that movie.

🔑 API Key

This project requires a TMDB API key.

For security, do not upload your actual API key to GitHub.

Replace it with your own key when running the project

**Project 3**
Currency Converter using Frankfurter API

A beginner-friendly Python project that converts an amount from one currency to another using real exchange-rate data from the Frankfurter API.

**Features**
Convert between currencies
Fetch current exchange rates through an API
Accept amount and currency codes from the user
Handle invalid currency requests
Display the converted amount

**Technologies**
Python
Requests
Frankfurter API
JSON
Google Colab

**What I learned**
Making API requests
Working with dynamic API URLs
Reading JSON responses
Extracting values from dictionaries
Using user input with APIs
Performing calculations using API data
Handling API errors
