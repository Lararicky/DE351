# TribeTales

TribeTales is a collaborative storytelling platform where users can create and share imaginative, cool, and extraordinary stories. The platform allows users to contribute to ongoing storylines or start their own. It combines creativity, interactivity, and user engagement in a streamlined web application.

## Features
- **Collaborative Storytelling**: Users can create stories, and collaborate with others.
- **Tags and Categories**: Stories are categorized by tags, making it easy to discover new content.
- **Interactive Elements**: Commenting, and liking on stories to increase engagement.
- **Cover Image Upload**: Users can upload cover images for their stories and profiles.

## Technology Stack
- **Frontend**: Angular
- **Backend**: Node.js with Express.js
- **Database**: MongoDB
- **Styling**: Tailwind CSS

## Project Structure
```
project-root/
├── backend/
│   ├── db/
│   ├── handlers/
│   ├── routes/
│   │   ├── comments.js
│   │   ├── contributions.js
│   │   ├── likes.js
│   │   ├── stories.js
│   │   ├── story_tags.js
│   │   ├── tags.js
│   │   ├── users.js
│   │   ├── votes.js
│   ├── app.js
│   ├── package.json
│   ├── package-lock.json
├── frontend/
│   ├── src/
│   │   ├── app/
│   │   │   ├── app.component.html
│   │   │   ├── app.component.ts
│   │   │   ├── app.routes.ts
│   ├── angular.json
│   ├── tailwind.config.js
│   ├── tsconfig.json
│   ├── package.json
│   ├── package-lock.json
```

## Setup Instructions
### Prerequisites
- Node.js and npm
- Angular CLI
- MongoDB instance (local or cloud)

### Backend Setup
1. Navigate to the backend folder:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the server:
   ```bash
   npm start
   ```

### Frontend Setup
1. Navigate to the frontend folder:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the development server:
   ```bash
   ng serve
   ```
