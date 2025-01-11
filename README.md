## Weather Reminder System

This Python project scrapes real-time weather data, analyzes conditions, and sends automated umbrella reminders via email. It ensures users are notified daily about weather conditions like rain or clouds to help them prepare for their day.

## Features
- Weather Data Scraping: Extracts live weather information (e.g., temperature, sky conditions) using Beautiful Soup and requests.
- Email Notifications: Sends secure, automated reminders via SMTP with customizable messages based on weather conditions.
- Task Scheduling: Utilizes the schedule library to run the program daily at a specified time.

## How It Works
Weather Data Extraction:

- Scrapes Google search results for weather data of a specified city.
- Parses HTML to extract temperature and sky conditions.

Email Alert:

- Sends an umbrella reminder if weather conditions include rain or clouds.
- Uses Gmail's SMTP server with TLS encryption for secure email transmission.

Daily Automation:

- Executes the reminder task daily at a predefined time using the schedule library.