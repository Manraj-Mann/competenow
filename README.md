# CompeteNow - React Native App with Firebase and Flask API

CompeteNow is a mobile app built using React Native that provides access to contest data through an API powered by Flask and backed by Firebase Realtime Database. This repository contains the source code for the React Native app, Flask API, and the Firebase Realtime Database setup.

## About

CompeteNow offers a mobile platform for accessing a wide range of contest data, including information about coding competitions, hackathons, and programming contests from various online judges. The app utilizes Firebase Realtime Database for data storage and retrieval and communicates with a Flask API to provide real-time contest updates.

## Features

- **React Native Mobile App:** CompeteNow is a cross-platform mobile app built using React Native, offering a native-like user experience for both iOS and Android users.
- **API for Contest Data:** The API allows users to retrieve contest data, including programming contest details, start and end times, hosting platforms, and more.
- **Long Contests:** The long contests are contests which are having duration > 1 day or 24hrs. Furtuhur divided in ongoing & upcoming.
- **Short Contests:** The short contests are contests which are having duration <= 1 day or 24hrs. Furtuhur divided in ongoing & upcoming.

## Installation and Setup

1. Clone this repository to your local machine:

   ```shell
   git clone https://github.com/yourusername/competenow.git
   cd competenow
   
## Technologies Used

- **React:** The frontend of CompeteNow is built using React, a popular JavaScript library for building user interfaces.



## Installation and Setup

1. Clone this repository to your local machine:

   ```shell
   git clone https://github.com/yourusername/competenow.git
   cd competenow
   ```

2. Install dependencies for the backend:

   ```shell
   cd backend
   npm install
   ```

3. Start the backend server:

   ```shell
   npm start
   ```

4. Install dependencies for the React frontend:

   ```shell
   cd ../frontend
   npm install
   ```

5. Start the React app:

   ```shell
   npm start
   ```

6. Access CompeteNow in your web browser at `http://localhost:3000`.

## API Endpoints

- **Contest Data**: Retrieve contest data through the API using endpoints like `/api/contests`. You can customize your requests to filter and sort contests.

## License

This project is open-source and available under the [MIT License](LICENSE). You are welcome to use, modify, and contribute to this project.

## Issues and Contributions

If you encounter any issues with CompeteNow or would like to contribute to its development, please feel free to create an issue or submit a pull request on this GitHub repository.

For questions or further assistance, please contact [Manraj Singh](mailto:mannmanraj239@gmail.com) or [Devashish Gupta](mailto:dev).

---
