# Chatzilla - Group Chat Application

A real-time chat application built with React, Firebase Firestore, and Firebase Authentication. This app allows users to sign in using their Google account and engage in real-time chat with others.

## Features

- **Real-time Messaging:** Send and receive messages instantly.
- **User Authentication:** Sign in with Google for secure access.
- **Firestore Integration:** Store messages in Firestore for reliable and scalable data storage.
- **Responsive Design:** Optimized for both desktop and mobile devices.

## Technologies Used

- **Frontend:** React
- **Backend:** Firebase (Firestore and Authentication)

## Prerequisites

- Node.js installed (v14.x or above recommended)
- Git installed

## Getting Started

Follow these steps to set up the project on your local machine:

### 1. Clone the Repository

```bash
git clone https://github.com/precious-soda/Chatzilla
cd Chatzilla
```

### 2.Install Dependencies

```bash
npm install
```

### 3. Set Up Environment Variables

Create a .env file in the root directory and add your Firebase configuration:

```bash
REACT_APP_FIREBASE_API_KEY=your-api-key
REACT_APP_FIREBASE_AUTH_DOMAIN=your-auth-domain
REACT_APP_FIREBASE_PROJECT_ID=your-project-id
REACT_APP_FIREBASE_STORAGE_BUCKET=your-storage-bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your-messaging-sender-id
REACT_APP_FIREBASE_APP_ID=your-app-id
```

### 4.Running the Application

```bash
npm start
```

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your changes.
