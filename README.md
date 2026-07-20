# Vacation Planner Mobile Application
A streamlined, offline‑capable Android application for organizing vacations and excursions.

## Introduction
The Vacation Planner Mobile Application is a lightweight Android solution designed to help travelers manage vacations, excursions, and important travel dates in a centralized, offline‑capable environment. The application provides structured data entry, automated date validation, and alert scheduling to support efficient trip planning without reliance on external booking systems or internet connectivity. This project was developed using Java, Android Studio, and the Room persistence library, and is compatible with Android 8.0 (Oreo) and higher.

## Application Purpose
Many travelers rely on scattered tools such as emails, screenshots, notes, and calendar reminders to track trip information. This fragmented approach often leads to missed activities, scheduling conflicts, and disorganized planning. The Vacation Planner consolidates all vacation and excursion details into a single mobile interface, improving organization, reducing errors, and providing timely alerts for key travel events.

## Key Features
The application includes a comprehensive suite of capabilities designed to simplify personal travel management.

### Vacation Management
- Add, edit, and delete vacations  
- Store hotel information and travel dates  
- Built‑in validation ensures logical date ranges  

### Excursion Management
- Add, edit, and delete excursions  
- Excursion dates must fall within the vacation date range  

### Offline Functionality
- Full offline support using the Room database  
- All data stored locally on the device  

### Alerts & Notifications
Schedule alerts for:
- Vacation start date  
- Vacation end date  
- Individual excursions  

### Sharing & Reporting
- Generate structured vacation reports  
- Share vacation summaries using Android’s native sharing features  

### User-Friendly Interface
- Clean, intuitive screens for vacations and excursions  
- Smooth navigation and organized layout

## System Requirements

### Software
- Android 8.0 (Oreo) or higher
- Android Studio (latest stable version)
- Gradle build system
- Room persistence library

### Hardware
- Android smartphone or emulator
- Minimum 2 GB RAM recommended for testing


## Setting Up the IDE (Android Studio)

1. Install Android Studio (latest stable version).
2. Open Android Studio and select **Get from VCS** (or **File → New → Project from Version Control**).
3. Enter the repository URL to clone it directly:

   https://github.com/samoyatech/D424-Vacation-Planner-App.git

4. Choose a local directory and click **Clone**.
5. Allow Android Studio to:
   - Download required SDK components
   - Sync Gradle
   - Install missing dependencies
6. Once the project loads, verify the following:
   - No Gradle sync errors
   - The app module builds successfully
   - The emulator or physical device can run the app
7. To run the application:
   - Connect an Android device or start an emulator
   - Click **Run**
   - Confirm the app launches and all features function as expected
  
   
## Installation and Using the Application

### Installing the Release APK
Download the signed release APK from the project’s GitHub Pages download link:
 
https://samoyatech.github.io/D424-Vacation-Planner-App/


1. Transfer the APK to an Android device if necessary.
2. On the device, enable installation from unknown sources:  
   Settings → Security → Install unknown apps
3. Tap the APK file to install the application.
4. Launch the app from the device’s application menu.


### Login

1. Launch the application.
2. Enter the username: `admin`.
3. Enter the password: `admin123`.
4. Tap **Log In**.
5. You will be taken to the Main screen.
6. Tap **Start Planning** to open the Vacation List screen.

### Vacation List Screen

The Vacation List screen displays vacations once saved and provides access to all major features.

Features on this screen include:

- Add Vacation
- Search
- Filter by date (start date, end date, or both)
- Generate Report via search/date filtering

### Add a New Vacation

1. Tap the **+** button at the bottom of the screen.
2. On the Vacation and Excursion Details screen, enter:
   - Vacation name
   - Hotel name
   - Start date
   - End date
3. Tap the three-dot menu, then tap **Save Vacation**.
4. The new vacation appears in the vacation list.

### View or Edit a Vacation

1. Tap any vacation in the list.
2. From the Vacation Details screen, you may:
   - Edit the vacation
   - Delete the vacation
   - Set vacation alerts
   - Share vacation details
   - Add excursions
   - View excursions

### Add an Excursion

1. From the Vacation and Excursion Details screen, tap the **+** button to add an excursion.
2. Enter:
   - Excursion Name
   - Date
3. Tap the three-dot menu, then tap **Save Excursion**.

### Search Vacations

1. Tap into the search field on the Vacation List screen.
2. Enter a keyword (vacation name or hotel name).
3. Press Enter on your keyboard.
4. Matching vacations appear in the list.

### Filter Vacations by Date

You may filter vacations using a start date, an end date, or both.

1. Tap **Filter by Date**.
2. Enter:
   - Start date to show vacations beginning on or after that date
   - End date to show vacations ending on or before that date
   - Both dates to apply both conditions
3. The list updates to show vacations matching the selected date criteria.

### Generating a Report

The application generates reports directly from the Vacation List screen. When a report is generated, the screen switches into Report Mode, displaying a report that includes a timestamp of when the report was generated and the list of vacations that match your search or date filters.

#### Generate a Report Using Search or Date Filters

1. From the Vacation List screen, apply a filter using any of the following options:
   - Enter a search term to filter by vacation name or hotel name.
   - Enter a start date to show vacations that begin on or after that date.
   - Enter an end date to show vacations that end on or before that date.
   - Enter both dates to filter by a date range.
2. The vacation report displays:
   - Vacation name
   - Start date
   - End date
   - Number of excursions
3. To exit Report Mode and return to the normal list view, tap **Clear Filter**. This removes all search and date filters and hides the report header.

### Logout

The application does not include a logout button. Closing the app returns the user to the Login screen on the next launch.



