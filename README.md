# Kalvium Recipe API

This project is a backend API for a recipe sharing platform. It allows users to add new recipes and fetch all existing recipes. The API is built with Node.js and Express and is deployed on Render.

---

## Project Overview

- **Task 1:** Add new recipes via `POST /api/recipes`
- **Task 2:** Retrieve all recipes via `GET /api/recipes`
- Recipes are stored persistently in `data/recipes.json`
- CORS is enabled to allow frontend integration
- The API validates required fields and automatically assigns IDs and default difficulty

---

## How to Run Locally

1. **Clone the repository**

bash
git clone https://github.com/your-github-username/kalvium-recipe-api.git
cd kalvium-recipe-api

2. **Install dependencies**
npm install

3. **Start the server**
npm start


4. **Access API**

The server listens on port 3000 by default. You can access the API at:

http://localhost:3000/api/recipes

5. **Deployed API URL**
Access the live API at: https://kalvium-recipe-api-ayisha-farheen.onrender.com

6. **API Endpoint Documentation**
URL: /api/recipes
Method: POST
Headers:
Content-Type: application/json