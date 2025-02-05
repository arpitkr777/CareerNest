# CareerNest - A Full Stack Job Portal Application

This project is a comprehensive Full Stack Job Portal Application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It provides a platform for job seekers and employers to connect, featuring user authentication and error monitoring.

## Features

- **User Authentication**: Secure login and registration for both job seekers and employers.
- **Job Listings**: Employers can post job openings with detailed descriptions.
- **Job Search**: Job seekers can search and filter job listings based on various criteria.
- **Application Management**: Job seekers can apply for jobs and track their application status.
- **Error Monitoring**: Integrated error tracking to ensure application stability.

## Technologies Used

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: Clerk Auth
- **Error Monitoring**: Sentry

## Getting Started

### Prerequisites

- Node.js installed
- MongoDB instance running

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/arpitkr777/CareerNest
   
   ```

2. **Install dependencies**:

   ```bash
   # For server
   cd server
   npm install

   # For client
   cd client
   npm install
   ```

3. **Configure environment variables**:

   - Create a `.env` file in the `backend` directory with the following variables:

     ```env
     MONGO_URI=your_mongodb_uri
     CLERK_API_KEY=your_clerk_api_key
     SENTRY_DSN=your_sentry_dsn
     ```

4. **Start the application**:

   ```bash
   # Start backend server
   cd server
   npm run dev

   # Start frontend development server
   cd client
   npm run dev
   ```

   The frontend will be accessible at `http://localhost:5173` and the backend API at `http://localhost:5000`.

## Usage

- **For Job Seekers**:
  - Register and create a profile.
  - Browse and search for job listings.
  - Apply to jobs and manage applications.

- **For Employers**:
  - Register and create a company profile.
  - Post new job listings.
  - Manage applications received for job postings.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License.

---

*Note: This project was inspired by a tutorial on building a Full Stack Job Portal Application using the MERN stack.*
