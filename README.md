Pokémon Review API

This API allows users to interact with a collection of Pokémon and their reviews. It provides endpoints to retrieve information about Pokémon, add new Pokémon, and submit reviews for existing Pokémon.

Features
- Retrieve Pokémon: Get information about Pokémon including their name, type, and reviews.
- Add Pokémon: Add new Pokémon to the collection.
- Submit Reviews: Submit reviews for existing Pokémon, including content, star rating, and title.

Technologies Used
- Framework: Spring Boot
- Database: Hibernate ORM with PostgreSQL
- API Documentation: Swagger UI
- Build Tool: Maven

Getting Started

To get started with the Pokémon Review API, follow these steps:

1. Clone the Repository: git clone https://github.com/linimary/pokemon-review-api.git
2. Navigate to the Project Directory: cd pokemon-review-api
3. Build the Project: mvn clean install
4. Run the Application: mvn spring-boot:run
5. Access the API Documentation: Open your web browser and go to http://localhost:8080/swagger-ui.html to view and interact with the API endpoints.

API Endpoints
- GET /api/pokemon: Retrieve all Pokémon.
- POST /api/pokemon: Add a new Pokémon.
- GET /api/pokemon/{id}: Retrieve a Pokémon by its ID.
- POST /api/review: Submit a review for a Pokémon.
- GET /api/review/{id}: Retrieve a review by its ID.
- GET /api/pokemon/{id}/reviews: Retrieve all reviews for a Pokémon by its ID.
  
