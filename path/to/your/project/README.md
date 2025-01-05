# Stock Market Prediction and Analysis System

## Overview

This project is a comprehensive Stock Market Prediction and Analysis System developed as a major project for the 7th semester. It leverages machine learning techniques to predict and analyze stock market trends, providing investors with accurate predictions and insights to make informed decisions.

## Tech Stack

- **Frontend:**
  - Next.js (React framework for server-rendered applications)
  - React
  - Tailwind CSS (for styling)

- **Backend:**
  - Node.js
  - Next.js API Routes

- **Database:**
  - Neon Database (Serverless Postgres)
  - Drizzle ORM

- **Authentication:**
  - Firebase Authentication

- **AI/ML:**
  - Google's Generative AI

- **API Integration:**
  - Axios for HTTP requests

- **Version Control:**
  - Git

## Features

- Real-time stock market data visualization
- Machine learning-based stock price prediction
- User authentication and personalized dashboards
- Historical data analysis and trend identification
- Interactive charts and graphs for data representation
- Customizable alerts and notifications
- Portfolio management and performance tracking

## Prerequisites

- Node.js (v14 or later)
- npm (v6 or later)
- Git

## Installation

1. Clone the repository: git clone https://github.com/janakjocee/major-project.git
   cd major-project

2. Install dependencies:
npm install

3. Set up environment variables:
Create a `.env.local` file in the root directory and add the necessary environment variables:
NEXT_PUBLIC_FIREBASE_API_KEY=your_firebase_api_key
   NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
   NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_firebase_project_id
   DATABASE_URL=your_neon_database_url
   GOOGLE_AI_API_KEY=your_google_ai_api_key

4. Set up the database:
   npm run db:push
   
## Usage

1. Start the development server:
npm run dev

2. Open your browser and navigate to `http://localhost:3000`

3. To build for production:
npm run build

4. To start the production server:
 npm start

 
## Project Structure

- `/app`: Main application components and pages
- `/components`: Reusable UI components
- `/configs`: Configuration files for various services
- `/lib`: Utility functions and shared libraries
- `/public`: Static assets

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Next.js](https://nextjs.org/)
- [React](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Firebase](https://firebase.google.com/)
- [Neon Database](https://neon.tech/)
- [Drizzle ORM](https://orm.drizzle.team/)
- [Google AI](https://ai.google/)

## Contact

For any queries or suggestions, please contact:

Janak Joshi - janakjocee@gmail.com

Project Link: [https://github.com/janakjocee/major-project](https://github.com/janakjocee/major-project)