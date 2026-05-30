# Travel Destinations App

A full-stack travel web application built with Node.js, Express, MongoDB, and EJS.

## Features

- **User Authentication** – Register and log in securely with username/password. Passwords are hashed using bcrypt.
- **Session Management** – Multiple users can be logged in simultaneously on different browsers using express-session.
- **Destination Browsing** – Explore travel destinations organized by category (Beaches, Mountains, etc.).
- **Destination Pages** – Each destination includes a description and an embedded video.
- **Want-to-Go List** – Users can save destinations to a personal list stored in MongoDB, with duplicate detection.
- **Search** – Search for destinations by name across all pages (substring matching supported).
- **Route Protection** – Unauthenticated users are redirected to the login page.

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Runtime | Node.js |
| Framework | Express |
| Database | MongoDB |
| Templating | EJS |
| Auth | bcrypt, express-session |
