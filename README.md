# Family Tree Management System

A web-based family tree management application built with Node.js and Express, using SQLite for data storage.

## Overview

This project provides a web application for managing and viewing family-related information. It was developed as a software engineering project to practice backend development, database integration, and web application design.

## Technology Stack

- **Backend:** Node.js, Express.js
- **Database:** SQLite
- **Frontend:** HTML, CSS, JavaScript
- **Development Tools:** npm, Nodemon

## Project Structure

```text
family-tree-management-system/
├── database/       # SQLite database and sample data
├── public/         # Static assets and web pages
├── src/            # Application routes and modules
├── server.js       # Express application entry point
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

## Prerequisites

- Node.js and npm
- A web browser

## Getting Started

### 1. Install Dependencies

```bash
npm install
```

### 2. Start the Application

```bash
npm start
```

### 3. Open the Application

Visit:

```text
http://localhost:8060
```

For development with automatic server restarts:

```bash
npm run dev
```

## Database

The application uses SQLite. The database path configured in `server.js` is `database/giapha.db`.

Before publishing, ensure that the database contains only appropriate demo data and no private family information or credentials.

## License

MIT
This project uses Git and GitHub for version control.