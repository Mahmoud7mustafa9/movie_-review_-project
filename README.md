# movie_-review_-project
# what i made in this project
# As a backend developer, your task is to design and implement a Movie Review API using Django and Django REST Framework. This API will allow users to manage reviews for movies by adding, updating, deleting, and viewing reviews. You will be responsible for building a fully functional API that interacts with a database to store user-generated reviews, mimicking a real-world development environment. This project will challenge your skills in database management, API design, and authentication, and you will be required to deploy your API to a live environment.

# Functional Requirements:
# Review Management (CRUD):

# Implement the ability to Create, Read, Update, and Delete (CRUD) reviews.
# Each review should include the following attributes: Movie Title, Review Content, Rating (out of 5), User ID, and Created Date.
# Ensure validation for required fields such as Rating (1 to 5), Movie Title, and Review Content.
# Users Management (CRUD):

# Implement CRUD operations for users.
# Each user should have a unique Username, Email, and Password.
# Only authenticated users should be able to submit, update, or delete their own reviews.
# Implement permission checks to ensure users cannot modify or delete reviews submitted by other users.
# View Reviews by Movie:

# Create an endpoint to allow users to view reviews for a specific movie.
# The endpoint should filter reviews based on Movie Title.
# Include a way to sort or paginate the results, especially if a movie has many reviews.
# Review Search and Filtering:

# Allow users to search for reviews by Movie Title or Rating.
# Add an optional filter to view reviews with specific ratings (e.g., show only 4-star and 5-star reviews).
# Technical Requirements:
# Database:

# Use Django ORM to interact with the database.
# Define models for Reviews and Users.
# Ensure that the Movie Title field allows for multiple reviews for the same movie from different users.
# Authentication:

# Implement user authentication using Django’s built-in authentication system.
# Users should be required to log in before adding, updating, or deleting reviews.
# Optionally, implement token-based authentication (JWT) for a more secure API experience.
# API Design:

# Use Django Rest Framework (DRF) to design and expose the API endpoints.
# Adhere to RESTful principles by using appropriate HTTP methods (GET, POST, PUT, DELETE).
# Ensure proper error handling with relevant HTTP status codes (e.g., 400 for invalid input, 404 for not found).
# Deployment:

# Deploy the API on Heroku or PythonAnywhere.
# Ensure the API is accessible, stable, and secure in the deployed environment.
# Pagination and Sorting:

# Add pagination to the review listing and search endpoints for better performance when handling large datasets.
# Provide sorting options, such as sorting reviews by Rating or Date Created. 