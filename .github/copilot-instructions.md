# Copilot Instructions for Mergington High School API

## Overview
This project is a FastAPI application designed to manage extracurricular activities at Mergington High School. It allows students to view and sign up for various activities through a web interface.

## Architecture
- **Main Components**:
  - **FastAPI**: The backend framework handling API requests.
  - **Static Files**: Served from the `/static` directory, including HTML, CSS, and JavaScript files.
- **Data Flow**: The frontend communicates with the FastAPI backend to fetch and submit data related to activities.

## Developer Workflows
- **Running the Application**:
  - Use `uvicorn src.app:app --reload` to start the server in development mode.
- **Testing**:
  - Ensure to test API endpoints using tools like Postman or directly through the browser.

## Project Conventions
- **File Structure**:
  - `src/`: Contains the main application code.
  - `static/`: Contains all static assets (HTML, CSS, JS).
- **Naming Conventions**: Follow consistent naming for functions and variables to enhance readability.

## Integration Points
- **External Dependencies**: The project relies on `fastapi` and `uvicorn` as specified in `requirements.txt`.
- **API Endpoints**: Key endpoints include `/activities` for fetching activities and `/signup` for signing up for activities.

## Examples
- **Fetching Activities**: The frontend uses the `fetchActivities` function in `app.js` to retrieve activities from the API.
- **Static File Serving**: Static files are served from the `/static` directory, accessible via `/static` in the browser.

## Conclusion
This document serves as a guide for AI agents to understand the structure and workflows of the Mergington High School API project. For further details, refer to the source code and comments within the files.