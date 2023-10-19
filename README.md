# CompeteNow - React Native App with Firebase and Flask API

CompeteNow is a mobile app built using React Native that provides access to contest data through an API powered by Flask and backed by Firebase Realtime Database. This repository contains the source code for the React Native app, Flask API, and the Firebase Realtime Database setup.

## About

CompeteNow offers a mobile platform for accessing a wide range of contest data, including information about coding competitions, hackathons, and programming contests from various online judges. The app utilizes Firebase Realtime Database for data storage and retrieval and communicates with a Flask API to provide real-time contest updates.

## Features

- **React Native Mobile App:** CompeteNow is a cross-platform mobile app built using React Native, offering a native-like user experience for both iOS and Android users.
- **API for Contest Data:** The API allows users to retrieve contest data, including programming contest details, start and end times, hosting platforms, and more.
- **Long Contests:** The long contests are contests which are having duration > 1 day or 24hrs. Furtuhur divided in ongoing & upcoming.
- **Short Contests:** The short contests are contests which are having duration <= 1 day or 24hrs. Furtuhur divided in ongoing & upcoming.


## Technologies Used

- **React:** The frontend of CompeteNow is built using React, a popular JavaScript library for building user interfaces.

## API Endpoints

- **Resource Data :** Retrieve resource data through the API using endpoints like `https://manraj.pythonanywhere.com/resource?id=61` where id is resource id.
  ```json
   {
    "status": "success",
    "message": "Successfully fetched the data",
    "data": {
        "icon": "https://clist.by/media/sizes/64x64/img/resources/contest_yandex_ru.ico",
        "id": 61,
        "n_accounts": 483,
        "n_contests": 27,
        "name": "contest.yandex.ru",
        "short": "yac"
    }
   }
  ```
- **Long Contest Data :** Retrieve contest data through the API using endpoints like `https://manraj.pythonanywhere.com/longcontests`.
  ```json
  {
    "status": "success",
    "message": "Successfully fetched the data",
    "ongoing": [
        {
            "duration": 716400,
            "end": "2023-10-22T10:00:00",
            "event": "AtCoder Heuristic Contest 025",
            "host": "atcoder.jp",
            "href": "https://atcoder.jp/contests/ahc025",
            "id": 46298577,
            "parsed_at": "2023-10-19T08:50:07.800626",
            "resource": "atcoder.jp",
            "resource_id": 93,
            "start": "2023-10-14T03:00:00"
        },
        "more such data ........"
     ] ,
  "upcoming": [
        {
            "duration": 172800,
            "end": "2023-10-22T09:00:00",
            "event": "DefCamp Capture the Flag (D-CTF) 2023 Quals",
            "host": "ctftime.org",
            "href": "https://ctftime.org/event/2106/",
            "id": 46125429,
            "resource": "ctftime.org",
            "resource_id": 70,
            "start": "2023-10-20T09:00:00"
        },
        "more such data ........"
     ]
  }
  ```
- **Short Contest Data :** Retrieve contest data through the API using endpoints like `https://manraj.pythonanywhere.com/shortcontests`.
  ```json
  {
    "status": "success",
    "message": "Successfully fetched the data",
    "ongoing": [
        {
            "duration": 716400,
            "end": "2023-10-22T10:00:00",
            "event": "AtCoder Heuristic Contest 025",
            "host": "atcoder.jp",
            "href": "https://atcoder.jp/contests/ahc025",
            "id": 46298577,
            "parsed_at": "2023-10-19T08:50:07.800626",
            "resource": "atcoder.jp",
            "resource_id": 93,
            "start": "2023-10-14T03:00:00"
        },
        "more such data ........"
     ] ,
  "upcoming": [
        {
            "duration": 172800,
            "end": "2023-10-22T09:00:00",
            "event": "DefCamp Capture the Flag (D-CTF) 2023 Quals",
            "host": "ctftime.org",
            "href": "https://ctftime.org/event/2106/",
            "id": 46125429,
            "resource": "ctftime.org",
            "resource_id": 70,
            "start": "2023-10-20T09:00:00"
        },
        "more such data ........"
     ]
  }
  ```
     
  
## License

This project is open-source and available under the [MIT License](LICENSE). You are welcome to use, modify, and contribute to this project.

## Issues and Contributions

If you encounter any issues with CompeteNow or would like to contribute to its development, please feel free to create an issue or submit a pull request on this GitHub repository.

For questions or further assistance, please contact [Manraj Singh](mailto:mannmanraj239@gmail.com) or [Devashish Gupta](mailto:devashishgupta9822@gmail.com).

---
