---
title: Projects
layout: small_title
---

## In Active Development

### YouTube Party
- **March 2021 - Present**
- **Built with Node.js, React, Socket.io, and the YouTube iFrame API**
- A full stack web application that allows any number of users to stream any YouTube video synchronously using web sockets and a YouTube iFrame instance.

## Completed or Archived

### ML-Enabled Spotify Curator
- **December 2020 - January 2021**
- **Collaborated with [Steve Li](https://steve-li.com)**
- **Built with Flask, React, Celery, Redis, Scikit-Learn, and the Spotify Web API**
- A full-stack web application leveraging machine learning to help users discover new songs they love. Spotify Curator calls the Spotify API to securely authenticate users and store their liked songs’ attributes as training data. It then performs k-means clustering to determine the probability that the user will like any new song or playlist. Model training and predictions are stored in a distributed task queue and picked up asynchronously by Celery workers. Redis serves as both a message broker and result store for the queue.

### OCaml Interpreter
- **April 2020 - May 2020** (CS 51 Final Project)
- **Written in OCaml**
- A series of metacircular interpreters for a Turing-complete subset of the OCaml programming language. Users are prompted with a graphical REPL and commands are executed based on three distinct semantic models: the substitution model, the dynamically-scoped environment model, and the lexically-scoped environment model.

### FoodSpace
- **December 2019 - January 2020**
- **Built with Node.js, React, Redux, Firebase, and the Yelp Fusion API**
- A full-stack web app that streamlines the process of ordering food. Integrating the Yelp Fusion API, users can find restaurants based on various criteria and schedule meal times on their calendar based on the hours for that specific place and time.

### RoommateHub
- **November 2019 - December 2019** (CS 50 Final Project)
- **Collaborated with [Geena Kim](https://github.com/gnakim)**
- **Built with Swift and Firebase**
- An iOS application enhancing the shared living experience for roommates. Features include secure user authentication with Firebase Authentication; synchronized task lists, interactive roommate profiles, and anonymized message forums with Firebase Realtime Database; and integrated iMessage options with MessageUI.

### Personal Site v1
- **July 2019 - March 2021**
- **Built with React and Firebase**
- A full frontend site that showcases a bit of my life. I wrote and maintained this site for over a year before finally deciding to switch to Jekyll. It was a good run.

### Automated Course Scheduling
- **January 2019 - March 2019**
- **Collaborated with [Arjun Patrawala](https://github.com/arjunpat)**
- **Built with Node.js and Firebase**
- A full-stack web app that digitizes and automates various components of the course scheduling process.
