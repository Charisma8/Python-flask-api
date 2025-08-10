#  Flask REST API - User Management System

A simple and powerful REST API built with Flask for managing user data. This project demonstrates all CRUD operations (Create, Read, Update, Delete) following REST API conventions.



##  Project Overview

This Flask REST API provides a complete user management system with the following capabilities:
- Create new users with validation
- Retrieve all users or specific users by ID
- Update existing user information
- Delete users from the system
- In-memory data storage for simplicity
- Comprehensive error handling
- JSON-based request/response format



##  Features

-  **Full CRUD Operations** - Create, Read, Update, Delete users
-  **Input Validation** - Email uniqueness and required field validation
-  **JSON Responses** - Structured API responses with status codes
-  **UUID Generation** - Unique identifiers for each user
-  **Timestamps** - Track creation and update times
-  **Error Handling** - Comprehensive error responses
-  **Data Validation** - Prevents duplicate emails and missing fields
-  **Status Tracking** - Clear success/error status in all responses
-  **User-Friendly Messages** - Clear feedback for all operations

## 🛠 Technology Stack

- **Backend Framework**: Flask (Python)
- **Data Storage**: In-memory (Python dictionary)
- **Data Format**: JSON
- **HTTP Methods**: GET, POST, PUT, DELETE
- **ID Generation**: UUID4
- **Time Handling**: Python datetime
- **Development Mode**: Flask debug mode enabled

##  Installation

### Prerequisites
- Python 3.7 or higher
- pip (Python package manager)

### Step 1: Clone or Download
```bash
# Clone the repository
git clone <repository-url>
cd flask-rest-api

# Or download and extract the ZIP file
```

### Step 2: Install Dependencies
```bash
# Install Flask
pip install Flask

# Or using requirements.txt
pip install -r requirements.txt
```

### Step 3: Verify Installation
```bash
python -c "import flask; print('Flask installed successfully!')"
```

##  Usage

### Starting the Server
```bash
python app.py
```

### Expected Output
```
 Starting your Flask API...
 Your API will be available at: http://127.0.0.1:5000
 Test it by going to that URL in your browser!
  Press Ctrl+C to stop the server
--------------------------------------------------
 * Running on http://127.0.0.1:5000
 * Debug mode: on
```
