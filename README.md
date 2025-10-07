# College Leave Management System

A web-based leave management system for Sri Eshwar College of Engineering.

## Features

- **Multi-user login system**: Students, Faculty, HOD, and Warden
- **Student types**: Hosteller and Day-scholar with different form options
- **Leave forms**: Regular leave, outing forms, and hostel leave
- **Approval workflow**: Faculty → HOD → Warden approval chain
- **Request tracking**: View pending and accepted requests

## Setup and Installation

1. **Install dependencies**:
   ```bash
   npm install
   ```

2. **Start the server**:
   ```bash
   npm start
   ```

3. **Access the application**:
   Open your browser and go to `http://localhost:3300`

## Login Credentials

### Students
- **Hosteller**: `pranav.a2024cce@sece.ac.in` / `password1`
- **Day-scholar**: `antonyfidelcastro.a2024it@sece.ac.in` / `password2`

### Faculty
- `classfaculty1@sece.ac.in` / `password1`
- `classfaculty2@sece.ac.in` / `password2`

### HOD
- `hod1@sece.ac.in` / `password1`
- `hod2@sece.ac.in` / `password2`

### Warden
- `warden1@sece.ac.in` / `password1`
- `warden2@sece.ac.in` / `password2`

## Project Structure

- `mainserver.js` - Express server with routing
- `loginpage.html` - Main login interface
- `dayscholarformselection.html` - Day-scholar form selection
- `hostellerformselection.html` - Hosteller form selection
- `successfulsubmission.html` - Submission confirmation page
- Various approval and request tracking pages for different user roles

## Technologies Used

- **Backend**: Node.js, Express.js
- **Frontend**: HTML, CSS, JavaScript
- **Styling**: Custom CSS with Google Fonts