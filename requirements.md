# Backend Requirements Specification

This document outlines the technical and functional requirements for core backend features of the ALX Airbnb clone project.

## 📌 1. User Authentication

### Overview

Allow users to register, log in, and authenticate using secure tokens.

### API Endpoints

#### POST `/api/auth/register`

-   **Input**:
    ```json
    {
        "name": "John Doe",
        "email": "john@example.com",
        "password": "securePassword123"
    }
    ```
