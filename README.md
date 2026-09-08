# TableView

TableView is an Android application for restaurant table reservations. Unlike traditional booking services, it lets users see the restaurant interior and choose a specific table before making a reservation.

## Core Functionality

1. User can search for restaurants by name or location.
2. User can view restaurant information, photos, and interior.
3. User can view an interactive floor plan with available tables.
4. User can select a specific table.
5. User can preview the selected table and its surroundings.
6. User can select the reservation date, time, and number of guests.
7. User can confirm and cancel a reservation.
8. User can view active and previous reservations.

## Current Project Structure

```text
TableView/
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── java/com/example/tableview/
│   │       │   └── MainActivity.kt
│   │       ├── res/
│   │       │   ├── drawable/
│   │       │   ├── mipmap/
│   │       │   ├── values/
│   │       │   └── xml/
│   │       └── AndroidManifest.xml
│   └── build.gradle.kts
├── gradle/
├── build.gradle.kts
├── settings.gradle.kts
├── gradlew
├── gradlew.bat
├── gradle.properties
├── .gitignore
└── README.md
```

## Build and Run

1. Open the project in Android Studio.
2. Let Gradle synchronize the project.
3. Select an Android emulator or connected Android device.
4. Press **Run** in Android Studio.

The project uses Kotlin and the Android Studio Empty Activity template as the initial scaffold.

## Git

Initial repository setup:

```bash
git init
git add .
git commit -m "Initial commit: project scaffold"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main
```
