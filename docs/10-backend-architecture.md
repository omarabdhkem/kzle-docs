# Backend Architecture

The backend should provide authentication, workspace management, file handling, AI orchestration, and user progress storage.

## Responsibilities
- User authentication and authorization
- Workspace CRUD operations
- File metadata storage
- AI request handling
- Quiz and flashcard generation
- Progress tracking
- Subscription and account data

## Recommended Stack
- Node.js
- Express or a modern equivalent
- PostgreSQL or MongoDB
- Object storage for uploaded files
- AI provider integration layer

## Design Notes
The backend should be modular so each major feature can evolve independently without rewriting the entire application.
