# Hidromatologia-v2

Is a second iteration of a sensor capture database in the city of Bucaramanga.

## Architecture

![architecture](https://github.com/hidromatologia-v2/docs/blob/main/assets/architecture.png)

## Repositories

| Repository                                                  | Description                                                  |
| ----------------------------------------------------------- | ------------------------------------------------------------ |
| [dashboard](https://github.com/hidromatologia-v2/dashboard) | This is the user dashboard for managing and exploring sensor stations |
| [users](https://github.com/hidromatologia-v2/users)         | User's only REST API with all the necessary CRUD operations performed in the dashboard |
| [messages](https://github.com/hidromatologia-v2/messages)   | Microservice responsible of delivering Emails.               |
| [alerts](https://github.com/hidromatologia-v2/alerts)       | Microservice responsible of triggering alerts and sending notifications to users |
| [stations](https://github.com/hidromatologia-v2/stations)   | Station's only REST API isolated to only publish sensor data to the system |
| [docs](https://github.com/hidromatologia-v2/docs)           | Documentation for the entire organization                    |
| [models](https://github.com/hidromatologia-v2/models)       | Centralized database controller used by many of the micro and monolithic services present in the system |
