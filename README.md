# Everydays Task

A Kotlin-based to-do list app built with Jetpack Compose, following the MVVM architecture. This app allows users to register, log in, and manage daily tasks with features like task notifications, filtering, and a persistent local database for task history.

## Features

1. *User Registration and Login*: Allows users to create accounts and log in securely.
2. add and delete task
3. cross the completed task
4. check box
5. *Task Management*: Users can create, update, delete, and mark tasks as complete.
6. *Task Notifications*: The app sends notifications to remind users about their tasks at specified times.
   

## Technologies Used

- *Jetpack Compose*: For the UI
- *ViewModel*: For MVVM architecture
- *Room Database (SQLite)*: For local task storage
- *WorkManager*: To manage task reminders and notifications
- *Navigation Component*: For handling app navigation

## How It Works

1. *User Registration and Login*: User credentials are securely stored in SQLite using Room. After registration, users can log in and access their tasks.
2. *Task Creation and Management*: Users can add tasks with details like due date, priority, and description. Tasks can be updated, marked as complete, or deleted.

## Build Manual

### Package & Software Requirements

| Component               | Version/Details          |
|-------------------------|--------------------------|
| IDE                     | Android Studio (2023 or later) |
| Jetpack Compose UI      | 1.9.1                    |
| Kotlin Coroutines       | 1.8.1                    |
| ViewModel               | 2.6.1                    |
| Room Database (SQLite)  | 2.6.1                    |
| Navigation              | 2.8.0                    |
| WorkManager             | 2.9.1                    |
| Coil Compose (optional) | 2.7.0                    |

### Installation

1. *Download & Install* the latest Android Studio IDE ([link](https://developer.android.com/studio)).
2. *Set up an Android Emulator* in the IDE.
3. *Clone the project repository* using:
   
   git clone 
   
4. *Verify Dependencies*: Ensure all necessary dependencies are added in the build file (build.gradle.kts:app).
5. *Run the Project*: Build and run the app on the emulator.
   
   Screenshots:
   https://i.ibb.co.com/LxYp73k/Screenshot-2024-10-28-173950.png
   https://i.ibb.co.com/1Gf4n8B/Screenshot-2024-10-28-174015.png
   https://i.ibb.co.com/2dMzrPG/Screenshot-2024-10-28-174003.png
