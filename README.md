# Project Title

Containerizing a Web Application.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies](#technologies)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Running the Application](#running-the-application)
- [Docker](#docker)
  - [Building the Docker Image](#building-the-docker-image)
  - [Running the Docker Container](#running-the-docker-container)

## Introduction

This web application allows users to create, manage, and track their projects and tasks efficiently. It provides a simple and user-friendly interface for adding new tasks, viewing the list of tasks, and marking tasks as completed.

## Features

- Ability to add new tasks.
- View the list of tasks.
- Mark tasks as completed.

## Technologies

- HTML
- CSS
- JavaScript
- Node.js
- Docker

## Getting Started

### Prerequisites

- Node.js 

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yusufmolumo/Containerizing-a-Web-Application

2. Navigate to the project repository:

   ```bash
   cd Containerizing-a-Web-Application

3. Install dependencies:

   ```bash
   npm install

## Running the application

To run the application locally, use the following command:

  ```bash
  npm start

## Docker

### Building the Docker Image

To build the Docker image for the application, use the following command:

   ```bash
   sudo docker build -t yusufmolumo/containerizing-a-web-application:latest .

### Running the Docker Container

Once the Docker image is built, you can run a Docker container using the following command:

   ```bash
   sudo docker run -d -p 3000:3000 yusufmolumo/containerizing-a-web-application:latest
