# Blog Frontend and Admin Dashboard - Svelte

A simple frontend built with Svelte that interacts with the Blog API built with Node.js, Express, MongoDB, and TypeScript. The frontend provides a user-friendly interface for blog-related actions, including signup, signin, and managing user profiles.

## Features

- User signup and signin
- Displaying blog posts
- User profile management
- Role-based access (Admin, Editor, User)
- Cookie-based Authentication using JWT (JSON Web Tokens)

## Tech Stack

- **Frontend**: Svelte
- **State Management**: Svelte Store
- **API Integration**: Fetch API for communicating with the backend
- **Authentication**: JWT (stored in localStorage or cookies)
- **Styling**: CSS/SASS or Tailwind (optional, based on your setup)

## Installation

### Prerequisites

Ensure you have the following installed:

- **Node.js** (v14.x or higher)
- **Svelte** (set up via the official template or SvelteKit)
- **API Endpoint**: Ensure the backend API is running and accessible

### Setup

1. Clone this repository:

   ```bash
   git clone https://github.com/sarfaraz187/blog-frontend.git
   cd blog-frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Configure environment variables:

   Create a `.env` file in the root of your project to configure the API URL and other settings:

   ```bash
   VITE_API_URL=http://localhost:8000
   ```

   Replace the `VITE_API_URL` with the URL of your backend API if it's running elsewhere.

4. Run the development server:

   ```bash
   npm run dev
   ```

5. Open the frontend in your browser at [http://localhost:5173](http://localhost:5173).
