# Video Summary Website

This repository contains two submodules for the **front-end** and **back-end** parts of a fullstack project. The front-end and back-end repositories are stored separately but are linked here using Git submodules.

## Getting Started

### Cloning the Repository

When cloning this repository, you need to make sure to initialize and update the submodules (front-end and back-end) to get their contents as well. Follow these steps:

1. Clone the parent repository using the `--recurse-submodules` flag to clone it along with the submodules:
   ```bash
   git clone --recurse-submodules https://github.com/EmersonFras/VideoSummary.git


# Project Description

### Project Description:

This project is a **fullstack web application** built using the **MERN stack** (MongoDB, Express, React, Node.js) with a **RESTful API backend**. The primary feature of the application is that users can upload videos, which are then transcribed and summarized using the **OpenAI API** (in development). Users can store these videos for future reference.

#### Key Features:
- **User Authentication**: 
  - Secure login authentication is implemented using **bcrypt**, where user passwords are hashed and stored securely in **MongoDB**.
  
- **Video Upload and Storage**:
  - Videos can be uploaded by users and are stored in MongoDB using **GridFS**.
  
- **Video Transcription and Summarization** (Work in Progress):
  - The OpenAI API will be used to automatically transcribe and summarize uploaded videos. This functionality is still under development.
  
- **CRUD Operations**:
  - Users can interact with their videos and other user data using **CRUD (Create, Read, Update, Delete)** operations through the RESTful API.

#### Current Status:
- **Backend**: The API is functional, and videos can be uploaded and managed. CRUD operations for users and videos are operational, tested with POSTMAN.
- **Frontend**: Basic frontend features are in place, but it is far from complete.
- **OpenAI API**: Not yet integrated.

This is a **work in progress**, with significant backend features already implemented and ongoing development of front-end features and OpenAI integration.