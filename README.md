# Job Application Tracker

A web application for keeping track of job applications in one place. It helps users organize their job search, update application statuses, and manage their progress through a simple drag-and-drop dashboard.

## Features

- Create an account and log in securely
- Add, edit, and delete job applications
- Track applications through different stages: Wish List, Applied, Interviewing, Offer, and Rejected
- Drag and drop applications between columns
- Store application details using MongoDB
- Manage applications through a simple Kanban dashboard

## Technologies Used

- **Next.js** - Full-stack web framework
- **React & TypeScript** - Frontend development
- **Tailwind CSS** - Styling
- **MongoDB & Mongoose** - Database
- **Better Auth** - User authentication
- **dnd-kit** - Drag-and-drop functionality

## Getting Started

**1. Clone the repository**

```bash
git clone https://github.com/Ad862002/job-tracker-project.git
cd job-tracker-project
```

**2. Install dependencies**

```bash
npm install
```

**3. Set up environment variables**

Create a `.env.local` file in the main project folder and add:

```env
MONGODB_URI=your_mongodb_connection_string
BETTER_AUTH_URL=http://localhost:3000
BETTER_AUTH_SECRET=your_generated_secret
```

**4. Run the application**

```bash
npm run dev
```

Open `http://localhost:3000` in your browser.

## Project Structure

- `app/` - Pages and routes
- `components/` - Dashboard and UI components
- `lib/` - Database, authentication, and application logic
- `scripts/` - Sample data setup

## Live Demo

Coming soon.

## Project Credit

This project was set up and explored as part of my full-stack development learning, using [Pedro Machado's Job Application Tracker tutorial](https://youtu.be/vCIsrOGNhas) as a reference.
