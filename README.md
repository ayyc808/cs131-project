# cs131-project
Fall 2025 CS 131 Project

# Name of Application/Website

## Overview
Description...

### Key Features
- 

## Setup Instructions

### Prerequisites
- Node.js (v19.1.0 or higher)
- Python (v3.8 or higher)
- MySQL (v8.0 or higher)
- PNPM package manager

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   pnpm install
   ```

3. Create a `.env` file in the frontend directory with the following content:
   ```env
   NEXT_PUBLIC_API_URL=http://localhost:5000
   ```

4. Start the development server:
   ```bash
   pnpm dev
   ```
   The frontend will be available at `http://localhost:3000`

### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

2. Create and activate a Python virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Create a `.env` file based on example.env:
   ```env
   MYSQL_HOST="localhost"
   MYSQL_USER="root"
   MYSQL_PASSWORD="your_password"
   DB_NAME="es_store_db"
   ```

5. Start the Flask server:
   ```bash
   python app.py
   ```
   The backend API will be available at `http://localhost:5000`

## Testing Key Features

### User Features
1. **Account Creation and Login**
   - Visit http://localhost:3000
   - Click "Sign Up" to create a new account
   - Login with your credentials

2.


### Admin Features
1. **Access Admin Dashboard**
   - Login as an admin user by using these credentials:
     ```
     Email: alvin.cheng@sjsu.edu
     Password: aaaaaaaa
     ```
   - Navigate to http://localhost:3000/admin

2. 


## Division of Work

### Team Member 1 - []
-

### Team Member 2 - []
-

### Team Member 3 - [Alvin Cheng]
- ER Diagram
- Backend endpoints
- Help out on frontend
- Creating lots of sample data
- Ensure referential integrity between foreign keys

### Team Member 4 - []
-

### Team Member 5 - []
-

### Team Member 6 - []
-

### Team Member 7 - []
-


## Technologies Used
- **Frontend**:
  

- **Backend**:
  - Python
  - Flask

- **Database**:
  - MySQL
