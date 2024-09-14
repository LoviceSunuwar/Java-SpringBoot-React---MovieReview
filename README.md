# Movie API Project

This project demonstrates a full-stack application with a backend built using Java, Spring Boot, and MongoDB, and a frontend developed with React. The application allows users to view movie data, play trailers, and add reviews.

## Features

### Backend:
- Built with Java, Spring Boot, and MongoDB.
- Implements RESTful APIs to fetch movie data and manage reviews.
- Uses Spring Data MongoDB for database interactions.
- Handles async operations using `async/await` for non-blocking, efficient requests.
- APIs tested using Postman with thorough validations and error handling.

### Frontend:
- Built with React.
- Uses Axios for HTTP requests to the backend API.
- Displays movies in a carousel using Material-UI.
- Plays movie trailers using React Player.
- Allows users to add and view reviews dynamically.

## API Implementation

The backend is structured with multiple layers:
- **Controller Layer**: Manages incoming API requests.
- **Service Layer**: Contains business logic for managing movie and review data.
- **Repository Layer**: Interfaces with MongoDB using Spring Data.

**Async Operations**: APIs are designed with async processing to ensure smooth user experience, using Java’s `CompletableFuture` and async methods for optimal performance.

## Testing

- **Postman Testing**: All APIs were rigorously tested using Postman to validate functionality and ensure reliable data retrieval and storage. Below is a screenshot demonstrating testing of the APIs:

  ![Postman Testing Screenshot](link-to-postman-screenshot)

- **Frontend Testing**: React frontend components were tested with live API calls to ensure data flows seamlessly between backend and frontend.

  ![Frontend Screenshot](link-to-frontend-screenshot)

## Project Structure

- `backend/`: Contains Java Spring Boot application code.
- `frontend/`: Contains React application code.
- `api/axiosConfig.js`: Configuration for Axios with base URL settings.
- `src/components/`: React components for displaying movies, trailers, and reviews.

## Technologies Used

- **Backend**: Java, Spring Boot, MongoDB, Maven
- **Frontend**: React, Axios, Bootstrap, Material-UI, Font Awesome, React Player
