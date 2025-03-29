# Reqres React App

## Overview
This is a React application that integrates with the Reqres API to perform user management functions. It includes authentication, user listing with pagination, and user editing/deletion.

## Features
- **Authentication**: Users can log in using predefined credentials.
- **User List**: Displays paginated user data from the Reqres API.
- **Edit & Delete Users**: Allows modifying or removing user details.
- **Search & Filtering**: Client-side search functionality.
- **Protected Routes**: Ensures only authenticated users can access certain pages.
- **Deployment Ready**: Configured for deployment on Vercel or Netlify.

## Technologies Used
- React (with Context API for state management)
- Axios (for API calls)
- React Router (for navigation)
- Tailwind CSS (for styling)

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/reqres-react-app.git
   cd reqres-react-app
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm start
   ```
   The app will run at `http://localhost:3000/`

## Usage
1. Login using the following credentials:
   - **Email**: eve.holt@reqres.in
   - **Password**: cityslicka
2. Upon successful login, you will be redirected to the Users List page.
3. Click "Edit" to modify user details or "Delete" to remove a user.
4. Use the search bar to filter users by name.
5. Use pagination buttons to navigate between user pages.

## Deployment
### Deploying on Vercel
1. Install Vercel CLI:
   ```sh
   npm install -g vercel
   ```
2. Deploy the project:
   ```sh
   vercel
   ```

### Deploying on Netlify
1. Install Netlify CLI:
   ```sh
   npm install -g netlify-cli
   ```
2. Deploy the project:
   ```sh
   netlify deploy
   ```

## Repository
- GitHub: [https://github.com/Tubabasu/reqres-react-app]

## Live Demo
- [Deployed App URL]

## License
This project is open-source and available under the MIT License.

