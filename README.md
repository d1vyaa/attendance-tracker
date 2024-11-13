# Geo-Location-Based Attendance Tracker

This is a web-based attendance tracking system that utilizes geo-location, face recognition, and fingerprint identification technologies to track attendance in real-time. The app ensures privacy by storing only user face IDs and not retaining any geo-location data. 

## Features

- **Geo-Fencing**: Automatically detects when a user enters or exits a predefined geographic boundary to mark attendance.
- **Face Recognition**: Uses facial recognition technology for authenticating and logging attendance.
- **Fingerprint Identification**: In addition to facial recognition, users can authenticate attendance using their fingerprint.
- **Privacy Focused**: Face IDs are stored, but geo-location data is not retained to protect user privacy.
- **Real-Time Attendance Tracking**: Admins can view attendance logs in real time.
- **User Authentication**: Secure login and sign-up process with email verification and password encryption.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python (Flask/Django), Node.js (for specific modules)
- **Database**: MySQL (or any other relational database for storing user data and attendance records)
- **Face Recognition**: OpenCV, Face Recognition library
- **Fingerprint Recognition**: Fingerprint sensor API
- **Geo-Fencing**: Google Maps API, Geo-location features
- **Cloud Hosting**: GitHub Pages (for frontend), Heroku/AWS for backend
