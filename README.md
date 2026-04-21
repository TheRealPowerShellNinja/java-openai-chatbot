# Java OpenAI Chatbot

Java Spring Boot chatbot application integrating the OpenAI API for conversational responses to software development questions.

## Overview

This project is based on an IBM Skills Network lab for building a chatbot with Java and OpenAI. The repository history was reinitialized so the project can be owned, developed, and maintained independently in a local workflow.

The application provides:
- a simple browser-based chat interface
- a Spring Boot backend
- integration with the OpenAI Chat Completions API
- support for environment-based API key configuration

## Tech Stack

- Java 17+ compatible build target
- Spring Boot
- Maven
- HTML, CSS, JavaScript
- OpenAI Chat Completions API

## Project Structure

- `src/main/java/com/chatbot/controller` - request handling
- `src/main/java/com/chatbot/service` - OpenAI integration and response logic
- `src/main/java/com/chatbot` - application entry point
- `src/main/resources/static` - frontend assets
- `src/main/resources/application.properties` - application configuration

## Running Locally

### Prerequisites

- Java
- Maven
- Git
- OpenAI API key

### Set the API key

In your terminal:

```bash
export OPENAI_API_KEY="your-real-openai-api-key"
```

### Run the application

```bash
mvn clean install
mvn spring-boot:run
```

Then open:

```text
http://localhost:3000
```

## Notes

- The application reads the API key from the `OPENAI_API_KEY` environment variable.
- Do not commit secrets or API keys to the repository.
- The original starter project came from IBM Skills Network coursework and was adapted for local development and GitHub-based version control.

## Status

Initial local import complete. Repository ownership and history have been rehomed for independent development.
