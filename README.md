# EcoSentry_Cloud_Function
## Overview
The main highlight of this package is a feature that improves the process of automatically exporting function triggers in Firebase Cloud Functions. The Cloud function is designed to receive real-time data sent from IoT devices in the form of HTTP requests, and then transmit the data for storage on the Firestore system.

## Dependencies
* [nodejs.org](https://nodejs.org/) v20.10.0 or higher.
* [Firebase CLI](https://firebase.google.com/docs/cli): a command line tool that allows you to interact with Firebase services from your local machine.
* [Firebase Console](https://firebase.google.com/): Create a Firebase project.

## Installation
**Clone the Repository**
```bash
  git clone https://github.com/GDSC-EcoSentry/EcoSentry_Cloud_Function.git
  cd EcoSentry_Cloud_Function
```
**Deploy Functions**
```bash
  firebase deploy --only functions
```

