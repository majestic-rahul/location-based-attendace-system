# Location-Based Attendance Android App (Geoloco)

This is a location-based attendance Android application developed using geofencing technology. The app automatically marks the attendance of students when they enter the class premises and stay for a minimum of 30 minutes. It utilizes geofence functionality to track the student's location and record their attendance.

## Screenshots

Here are some screenshots of the Location-Based Attendance Android App:

![image](https://github.com/majestic-rahul/location-based-attendace-system/assets/79097971/87b9d7dc-0660-4641-845d-fef6a458d281)    ![image](https://github.com/majestic-rahul/location-based-attendace-system/assets/79097971/7415c3cc-331d-49b2-97aa-9146b8ca1ebb)

![image](https://github.com/majestic-rahul/location-based-attendace-system/assets/79097971/37d6984d-0556-4ddc-aea9-72154bc60522)

![image](https://github.com/majestic-rahul/location-based-attendace-system/assets/79097971/8d82c2ff-4c74-49ac-8d24-f8b968aa0c9b)

![image](https://github.com/majestic-rahul/location-based-attendace-system/assets/79097971/2df79e5f-4ff4-4b46-a116-611a93ca9dae)

## Features

* Geofencing Technology: The app uses geofencing to create virtual boundaries around the class premises and trigger attendance when the student enters the designated area.

* Attendance Tracking: The app automatically records the student's attendance when they enter the geofenced area and stay for at least 30 minutes.

* Firebase Realtime NoSQL Database: Student information and attendance details are stored in a Firebase Realtime Database, providing a reliable and scalable solution for data storage.

* Android Studio: The app is developed using Android Studio, the official integrated development environment (IDE) for Android application development.

* Java Backend: The backend logic of the app is implemented using Java, a widely used programming language for Android development.

* XML User Interface: The app's user interface is designed using XML, a markup language that defines the layout and appearance of the app screens.

## Getting Started

To run and test the Location Based Attendance Android App on your local machine, follow these steps:

1. Clone the repository:

   git clone https://github.com/majestic-rahul/location-based-attendace-system.git

2. Open the project in Android Studio.

3. Set up Firebase Realtime Database:
   * Create a new Firebase project and enable the Realtime Database.
   * Add the necessary Firebase configuration details to the app's build.gradle file.
     
4. Build and run the app on an Android device or emulator.

## Dependencies

The following dependencies are used in this project:

* Firebase Realtime Database: Used for storing student information and attendance data.
* Google Play Services: Provides the geofencing functionality required for location-based attendance.
* Support Libraries: Various support libraries used for UI components and compatibility.
  
Make sure to include these dependencies in your project's build.gradle file.

## Contributing

Contributions to the Location Based Attendance Android App project are welcome. If you have any bug fixes, improvements, or new features to propose, please submit a pull request. For major changes, please open an issue to discuss the proposed changes beforehand.

## Acknowledgements

* Firebase: Backend and database support.
* Google Play Services: Geofencing functionality.
* Android Studio: Development environment for Android apps.
  
Please refer to the individual documentation and resources for detailed information on each technology used.
