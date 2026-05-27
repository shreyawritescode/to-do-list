# To-Do List App

A full-stack **To-Do List** web application built with **Node.js**, **Express**, **MongoDB**, and **EJS**. Users can create custom to-do lists, add items, and check them off. The app supports multiple named lists and persists data in MongoDB.

## Features

- Create and manage multiple named to-do lists
- Add new items to any list
- Check off / delete completed items
- Persistent storage with MongoDB
- Dynamic date display
- Deployed to **Heroku** (Procfile included)

## Tech Stack

| Technology | Purpose |
|---|---|
| Node.js | Server-side runtime |
| Express.js | Web framework |
| MongoDB + Mongoose | Database and ODM |
| EJS | Templating engine |
| Lodash | Utility functions (string formatting) |
| Body-parser | Request parsing middleware |
| Heroku (Procfile) | Cloud deployment |

## Project Structure

```
to-do-list/
├── public/css/        # Static CSS styles
├── views/             # EJS templates
├── app.js             # Main Express server
├── date.js            # Date utility module
├── index.html         # Static fallback
├── Procfile           # Heroku deployment config
├── package.json
└── README.md
```

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/shreyawritescode/to-do-list.git
   cd to-do-list
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Make sure MongoDB is running locally, then start the server:
   ```bash
   node app.js
   ```
4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Usage

- Visit the home page to see the default daily to-do list
- Navigate to `/:listName` (e.g. `/work`) to create a custom named list
- Add items using the input field and "+" button
- Click the checkbox to delete completed items

---

*A full-stack CRUD app built as part of a web development learning journey.*
