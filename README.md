# AI Feedback Analyzer

An advanced Next.js application that uses AI to analyze customer feedback, extract sentiment, and provide actionable insights.

## Features

- **Sentiment Analysis**: Automatically classifies feedback as positive, neutral, or negative
- **AI-Powered Response Generation**: Creates personalized, empathetic responses to customer feedback
- **Key Insights Extraction**: Identifies important topics and actionable takeaways
- **Interactive Dashboard**: Visualizes feedback trends and sentiment distribution
- **MongoDB Integration**: Stores and retrieves feedback data for historical analysis
- **Gemini API Integration**: Leverages Google's Gemini model for enhanced analysis

## Tech Stack

- **Frontend**: Next.js 15, React 19, TailwindCSS 4
- **Backend**: Next.js API Routes
- **Database**: MongoDB with Mongoose
- **Authentication**: NextAuth.js
- **AI/ML**: Custom sentiment analysis model (Python) + Google Gemini API
- **Data Visualization**: Recharts

## Getting Started

First, set up your environment variables by creating a `.env.local` file:

```
MONGODB_URI=your_mongodb_connection_string
GEMINI_API_KEY=your_gemini_api_key
NEXTAUTH_SECRET=your_nextauth_secret
NEXTAUTH_URL=http://localhost:3000
```

Then, install dependencies and run the development server:

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the application.

## Project Structure

- `/app`: Main application code (Next.js App Router)
  - `/api`: API endpoints for feedback analysis and data retrieval
  - `/components`: Reusable React components
  - `/dashboard`: Interactive dashboard for visualizing feedback data
  - `/feedback`: Feedback submission and analysis interface
  - `/models`: MongoDB schema definitions
  - `/utils`: Utility functions for database connections and sentiment analysis
  - `/model`: Python-based sentiment analysis model

## Learn More

This project uses Next.js App Router architecture. To learn more about Next.js, check out:

- [Next.js Documentation](https://nextjs.org/docs)
- [Learn Next.js](https://nextjs.org/learn)

## Deployment

Deploy on Vercel:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fyourusername%2Fai-feedback-analyzer)
#   A I F E E D B A C K 
 
 
