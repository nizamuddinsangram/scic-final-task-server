# Awesome Site - Server

This repository contains the server-side code for **Awesome Site**, a full-stack Product Filtering & Sorting Single Page Application (SPA). The server is built using Node.js, Express.js, and MongoDB, and provides the backend functionality to support product search, filtering, sorting, and pagination.

## Features

- **Product Data API:** Endpoints to fetch, filter, and sort product data.
- **Pagination:** Efficient loading of products with pagination.
- **Search:** Allows searching for products by name.
- **Categorization:** Filters products by brand name, category, and price range.
- **Sorting:** Sorts products by price (low to high, high to low) and date added (newest first).
- **Authentication:** Google and Email/Password authentication using Firebase.
- **Database:** MongoDB for storing product data.

## Tech Stack

- **Node.js** - JavaScript runtime for server-side operations.
- **Express.js** - Web framework for building APIs.
- **MongoDB** - NoSQL database for storing product and user data.
- **Mongoose** - ODM library for MongoDB.
- **Firebase** - Authentication service for user management.
- **CORS** - Middleware for handling cross-origin requests.

## Getting Started

### Prerequisites

Ensure you have the following installed on your development machine:

- **Node.js** (v14+)
- **npm** (v6+)
- **MongoDB** - Either local or a cloud instance

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/awesome-site-server.git
   cd awesome-site-server
