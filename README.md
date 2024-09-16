# Harmony Hub

Harmony Hub is a web application that combines music and movie recommendations with social features, allowing users to discover new content, connect with friends, and participate in various activities.

## Features

- User authentication (signup, login, password reset)
- Music platform integration (Spotify)
- Music recommendations
- Movie recommendations
- Concert discovery
- Friend system (add friends, view profiles)
- Real-time messaging
- Trivia games
- Profile customization

## Technologies Used

- Backend: Python with Flask
- Frontend: HTML, CSS, JavaScript
- Database: SQLite
- APIs: Spotify, TMDB (The Movie Database)

## Setup

1. Clone the repository
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Set up environment variables:
   - `OPENAI_KEY`: Your OpenAI API key
   - `TMDB_API_KEY`: Your TMDB API key
   - `MAIL_SERVER`, `MAIL_PORT`, `MAIL_USE_TLS`, `MAIL_USERNAME`, `MAIL_PASSWORD`: Email configuration for password reset functionality

4. Run the application:
   ```
   python app.py
   ```

## Project Structure

- `app.py`: Main application file
- `backend/`: Backend logic
  - `user_auth.py`: User authentication functions
  - `concert_recommendations.py`: Concert recommendation logic
  - `music_recommendation.py`: Music recommendation logic
  - `tmdb_recommendations.py`: Movie recommendation logic
  - `trivia.py`: Trivia game logic
- `templates/`: HTML templates
- `static/`: Static files (CSS, JavaScript, images)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

