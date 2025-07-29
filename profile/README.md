# NTN Expense Manager 👋

NTN Expense Manager is a comprehensive application designed to help users manage their expenses effectively. It includes features for tracking transactions, setting financial goals, and analyzing spending patterns.

## Project Structure

The project is divided into two main parts:

### Backend
The backend is responsible for handling API requests, managing the database, and implementing business logic. It is located in the `backend/` directory.

#### Key Directories and Files
- `config/`: Contains configuration files for the database and other services.
- `controllers/`: Includes controllers for handling business logic.
- `middleware/`: Contains middleware like rate limiters.
- `models/`: Defines the database models.
- `routes/`: Includes route definitions for the API.
- `src/server.js`: The entry point for the backend server.

### Frontend
The frontend is a React Native application located in the `ntn-expense-manager/` directory. It provides the user interface for interacting with the application.

#### Key Directories and Files
- `app/`: Contains the main application screens and layouts.
- `components/`: Includes reusable UI components.
- `assets/`: Stores fonts and images used in the application.
- `utils/`: Contains utility functions like API base URLs.

## Features

- **Transaction Management**: Add transactions.
- **Goal Setting**: Define financial goals and track progress.
- **Analytics**: Visualize spending patterns and trends.
- **Authentication**: Secure clerk user authentication for data privacy.

## Installation

### Prerequisites
- Node.js and npm installed on your machine.
- Expo CLI for running the React Native application.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/NTN-Expense-Tracker
   ```
2. Navigate to the backend directory and install dependencies:
   ```bash
   cd backend
   npm install
   ```
3. Start the backend server:
   ```bash
   npm run dev
   ```
4. Navigate to the frontend directory and install dependencies:
   ```bash
   cd ../ntn-expense-manager
   npm install
   ```
5. Start the Expo development server:
   ```bash
   npm start
   ```

## Contact

For any inquiries or support, please contact [Tharindu Nilan](https://tharindu.site/).
