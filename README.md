
# Portfolio Builder

A modern, responsive portfolio builder application built with React, TypeScript, and Vite.

## Features

- **Profile Management**: Add your personal information, bio, and contact details
- **Skills Showcase**: Display your technical skills
- **Project Portfolio**: Showcase your projects with links to GitHub and live demos
- **Experience Timeline**: Add your work experience and career history
- **Achievements**: Highlight your certifications and awards
- **Theme Selection**: Choose from Classic, Modern, and Dark themes
- **Live Preview**: See your portfolio in real-time
- **Data Storage**: Uses embedded H2 in-memory database via backend (no external DB required)

## Setup

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```

### Database Configuration

The backend uses an embedded **H2 in-memory database** (configured in `backend/src/main/resources/application.properties`).

No additional database setup is required for local development.

### Running the Application

Start the development server:
```bash
npm run dev
```

Build for production:
```bash
npm run build
```

## Usage

1. Navigate to the dashboard
2. Add your profile information
3. Add skills, projects, experiences, and achievements
4. Choose a theme
5. Preview your portfolio

## Tech Stack

- **Frontend**: React 18, TypeScript, Tailwind CSS
- **UI Components**: Radix UI
- **Routing**: React Router
- **Database**: Embedded H2 (in-memory, backend)
- **Build Tool**: Vite
  