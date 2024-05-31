# Movie Library Backend

## Installation
1. Clone the repository
    ```sh
    git clone https://github.com/yourusername/movie-library-backend.git
    cd movie-library-backend
    ```
2. Install dependencies
    ```sh
    npm install
    ```
3. Set environment variables in `.env` file
    ```sh
    MONGO_URI=your_mongo_db_uri
    JWT_SECRET=your_jwt_secret
    ```
4. Run the server
    ```sh
    npm start
    ```

## Endpoints
- `POST /api/users/register` - Register a new user
- `POST /api/users/login` - Login user
- `POST /api/movies` - Create a new movie list (Protected)
- `GET /api/movies` - Get all movie lists

## Deployment
- Deployed on Heroku: [Backend URL](https://movie-library-backend.herokuapp.com)
