# Creative Hub - A Freelancing Platform

## Overview
Creative Hub is a modern, user-centric freelancing platform tailored to bridge the gap between clients seeking high-quality creative and technical services, and freelancers eager to showcase their talents and earn independently.

Creative Hub offers a dynamic digital marketplace where clients—individuals or businesses—can discover, connect with, and hire freelancers across a wide range of categories such as Graphic Designing, Web Development, UI/UX Design, Writing & Translation, Video Editing, Photography, Audio & Music Production, 3D & CAD, and many more.

## Tech Stack
- **Frontend**: NextJS, JavaScript
- **Backend**: FastAPI, Python
- **Database**: SQLite

## Requirements

### Backend Dependencies
- `fastapi`: FastAPI framework for building APIs.
- `uvicorn`: ASGI server to run the FastAPI application.
- `sqlalchemy`: SQL toolkit and Object-Relational Mapping (ORM) for Python.
- `databases`: Async database support for SQLAlchemy.
- `passlib[bcrypt]`: Password hashing with bcrypt.
- `pydantic[email]`: Data validation and settings management with email support.
- `python-multipart`: Support for multipart/form-data requests.
- `python-jose`: JSON Object Signing and Encryption for JWT support.

### Frontend Dependency
- `nextjs`: React framework for server-side rendering and static site generation.

## Installation

### Backend Setup
1. Ensure you have Python 3.8+ installed.
2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use venv\Scripts\activate
   ```
3. Install the required Python packages:
   ```bash
   pip install fastapi uvicorn sqlalchemy databases passlib[bcrypt] pydantic[email] python-multipart python-jose
   ```
4. Set up the SQLite database (configure as per your project structure).

### Frontend Setup
1. Ensure you have Node.js and npm installed.
2. Navigate to the frontend directory and install dependencies:
   ```bash
   cd frontend
   npm install
   ```

## Running the Project

### Backend
1. Activate the virtual environment (if not already activated):
   ```bash
   source venv/bin/activate  # On Windows use venv\Scripts\activate
   ```
2. Run the FastAPI application using uvicorn:
   ```bash
   uvicorn main:app --reload --host 0.0.0.0 --port 8000
   ```
- Replace `main` with your main FastAPI file name if different.
- Access the API at `http://localhost:8000`.

### Frontend
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Start the NextJS development server:
   ```bash
   npm run dev
   ```
- Access the application at `http://localhost:3000`.

## Copyright and Author
© 2025 Mohammad Wasi and Sanya Sinha
