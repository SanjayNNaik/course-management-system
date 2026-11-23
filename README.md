# Course Management System

A React course management application with a local JSON Server API.

## Requirements

- Node.js and npm

## Start the API

From the repository root, copy the safe starter data to the local database file:

```powershell
Copy-Item backend/database.example.json backend/database.json
```

Then start JSON Server on port 5000:

```powershell
npx json-server backend/database.json --port 5000
```

On macOS or Linux, use `cp backend/database.example.json backend/database.json` for the copy step.

## Start the frontend

In a second terminal:

```powershell
cd course-management-frontend
npm install
npm run dev
```

The frontend expects the API at `http://localhost:5000`. Create a user through the signup page to sign in; the starter database contains no accounts or passwords.