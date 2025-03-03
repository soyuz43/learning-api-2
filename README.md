# React Mock Database with JSON Server

This repository serves as a mock database for a React application, providing a simple and efficient way to simulate backend data interactions during development. The database is powered by **JSON Server**, a zero-code, fully customizable tool that mimics a REST API with minimal setup.

## Purpose

The primary purpose of this mock database is to enable frontend developers to work independently of backend services. By simulating real-world data interactions, it allows for seamless testing, debugging, and development of React components and features without relying on a live backend.

## Features

- **Faux Data**: Contains realistic, structured data for users, posts, topics, and likes, mimicking a real-world application.
- **RESTful Endpoints**: JSON Server provides RESTful API endpoints for all resources, enabling CRUD operations (Create, Read, Update, Delete).
- **Scalable Structure**: The data structure is designed to be easily extendable, allowing developers to add new resources or modify existing ones as needed.
- **Development-Friendly**: Perfect for prototyping, testing, and debugging React applications without the need for a live backend.

## Data Structure

The mock database includes the following resources:

- **Users**: Contains user details such as name, email, and cohort.
- **Posts**: Includes blog-like posts with titles, bodies, dates, and associations to users and topics.
- **Topics**: Represents categories or tags for posts (e.g., JavaScript, React, CSS).
- **Likes**: Simulates user interactions by tracking likes on posts.

Each resource is interconnected, providing a realistic data model for testing React components and features.

## Usage

To use this mock database, start the JSON Server by running the appropriate command in your terminal. The server will expose RESTful endpoints for all resources, allowing your React application to interact with the data as if it were a live backend.

For example:
- Fetch all posts: `GET /posts`
- Fetch a specific user: `GET /users/1`
- Create a new post: `POST /posts`
- Update a like: `PUT /likes/3`

## Why JSON Server?

JSON Server is an excellent tool for frontend development because:
- It requires no backend knowledge or setup.
- It provides instant RESTful APIs for any JSON data.
- It supports advanced features like filtering, pagination, and relationships.
- It is lightweight and easy to integrate into any development workflow.
