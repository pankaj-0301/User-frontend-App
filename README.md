# User Management Application

A React-based user management application that integrates with the Reqres API to perform basic user management functions.

## Features

- **Authentication**
  - Login system with token-based authentication
  - Protected routes
  - Automatic redirect to login for unauthenticated users

- **User Management**
  - View all users in a responsive grid layout
  - Search users by name or email
  - Edit user details
  - Delete users
  - Pagination support

- **UI/UX**
  - Responsive design for all screen sizes
  - Loading states
  - Toast notifications for success/error messages
  - Confirmation dialogs for destructive actions
  - Clean and modern interface

## Tech Stack

- React
- TypeScript
- Tailwind CSS
- React Router
- Axios
- React Hot Toast
- Lucide React (for icons)

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

## Login Credentials

- Email: eve.holt@reqres.in
- Password: cityslicka

## Implementation Details

- **Authentication**: Uses JWT tokens stored in localStorage
- **API Integration**: All API calls are centralized in the api.ts file
- **State Management**: Uses React hooks for local state management
- **Routing**: Implements protected routes using React Router
- **Search**: Real-time search with pagination support
- **TypeScript**: Full type safety across the application
- **Error Handling**: Comprehensive error handling with user feedback

## Build for Production

```bash
npm run build
```

This will create an optimized production build in the `dist` directory.
