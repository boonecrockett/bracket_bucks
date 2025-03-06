# Bracket Bucks (Private Repository)

A web application for anonymous buck voting competition with delayed email capture.

## Overview

Bracket Bucks is a platform where users can vote on buck matchups anonymously, with scores based on Boone and Crockett standards. Users can participate without signing up, and their votes are preserved when they eventually create an account.

## Features

- Anonymous voting with session tracking
- Delayed email capture
- Buck matchups with Boone and Crockett scoring
- Real-time leaderboard
- Mobile-friendly swipe voting

## Tech Stack

- Frontend: HTML5, CSS3, JavaScript
- Graphics: p5.js for interactive visualizations
- Backend: Supabase for authentication and database
- Hosting: GitHub Pages

## Setup

1. Request access to this private repository from the repository owner.

2. Once access is granted, clone the repository:
   ```bash
   git clone https://github.com/boonecrockett/bracket_bucks.git
   cd bracket_bucks
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Create a `config.js` file with your Supabase credentials:
   ```javascript
   export const SUPABASE_URL = 'your-url';
   export const SUPABASE_KEY = 'your-key';
   ```

5. Start the development server:
   ```bash
   npm start
   ```

## Contributing

Please follow our coding standards in `.cursorrules` when contributing to this project.

## License

MIT