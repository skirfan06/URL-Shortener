# Smart URL Shortener

A full-stack URL shortening application built using **React**, **Node.js**, **Express.js**, and **MongoDB**. The application allows users to convert long URLs into short, shareable links with automatic redirection and secure URL validation.

---

## Features

- 🔗 Shorten long URLs into compact links
- ✅ URL validation before shortening
- 🚀 Fast redirection to the original URL
- 💾 MongoDB database integration
- 🌐 RESTful API using Express.js
- 📱 Responsive React user interface
- 🔒 Efficient backend architecture

---

## Tech Stack

### Frontend
- React
- React Router
- Materialize CSS

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- Nginx

---

## Project Structure

```
Smart-URL-Shortener/
│
├── client/
├── server/
├── nginx/
├── sketch/
├── .gitignore
└── README.md
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/skirfan06/URL-Shortener.git
cd URL-Shortener
```

### Install Backend Dependencies

```bash
cd server
yarn install
```

### Start Backend

```bash
yarn run server
```

### Install Frontend Dependencies

Open another terminal.

```bash
cd client
yarn install
```

### Start Frontend

```bash
yarn start
```

---

## Application Workflow

1. User enters a long URL.
2. The application validates the URL.
3. A unique short code is generated.
4. The URL is stored in MongoDB.
5. The shortened URL is displayed.
6. Visiting the short URL redirects the user to the original website.

---

## Future Enhancements

- User Authentication
- QR Code Generation
- Click Analytics Dashboard
- Custom Short URLs
- URL Expiration Support
- Dark Mode

---

## Learning Outcomes

Through this project I gained experience with:

- REST API Development
- React Frontend Development
- Express.js Backend
- MongoDB Database Integration
- Routing and URL Redirection
- Client-Server Architecture
- Git and GitHub Version Control

---

## License

This project is licensed under the MIT License.