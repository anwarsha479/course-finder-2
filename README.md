COURSE FINDER

Course Finder is a web application designed to help users discover top-rated online courses across various platforms. It aggregates course data from multiple sources, providing a comparison to help learners make informed decisions.

FEATURES
- Multi-Platform Course Aggregation: Fetches courses from Coursera, LinkedIn Learning, Pluralsight, and YouTube.
- Dynamic Scraping: Uses headless browsers to scrape dynamic content.
- Course Comparison: Compare courses based on ratings, reviews, and duration.
- Backend Integration: Stores course data in MongoDB for efficient querying.
- Frontend Interface: User-friendly interface built with React.js and Tailwind CSS.

TECH STACK
- Frontend: React.js, Tailwind CSS
- Backend: Node.js, Express.js
- Database: MongoDB
- Scraping: Python (Selenium, BeautifulSoup), Node.js (Axios, Cheerio)
- Deployment: Vercel (backend), GitHub Pages (frontend)

INSTALLATION

Prerequisites:
- Node.js (v16 or higher)
- Python (v3.8 or higher)
- MongoDB (local or cloud instance)

Backend Setup:
1. git clone https://github.com/anwarsha479/course-finder-2.git
2. cd course-finder-2/backend
3. npm install
4. Create a .env file with:
   MONGODB_URI=your_mongodb_connection_string
   PORT=5000
5. npm start

Frontend Setup:
1. cd ../frontend
2. npm install
3. npm start
   Application runs at http://localhost:3000

USAGE
1. Open the app in your browser.
2. Enter a topic (e.g., "Python") in the search bar.
3. View aggregated courses from different platforms.
4. Filter and sort by ratings, reviews, and duration.

SCRAPING DETAILS
- Pluralsight: Python + Selenium + BeautifulSoup; handles dynamic content.
- Coursera & LinkedIn: Node.js + Axios + Cheerio for static scraping.
- YouTube: Fetches course-related videos and metadata using YouTube Data API.

DEPLOYMENT
Backend: Ngrok
Frontend: Vercel


