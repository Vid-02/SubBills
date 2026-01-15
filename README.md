# SubBills

SubBills is an Android application designed for managing bills and tracking expenses in a simple and organized manner. It allows users to record purchases, categorize spending, maintain historical records, and view summaries for better budgeting decisions.

---

## Features

### Expense Recording
Create entries for bills or purchases with information such as title, category, amount, date, and additional details.

### Category Based Tracking
Organize expenses under predefined or custom categories to make spending analysis more structured.

### Monthly and Daily Overview
View aggregated totals and explore expenses day by day or month by month.

### Local Data Storage
Stores billing and expense data locally on the device for fast access and offline capability.

### User Friendly Interface
Provides a clean and minimal UI designed with Android XML layouts for intuitive navigation.

### Secure Local Files
Uses internal storage and Android best practices to safeguard user data.

---

## Project Structure

The project follows standard Android conventions.

```
SubBills/
 └── app/
     ├── src/
     │   ├── main/
     │   │   ├── java/com/example/md_project/
     │   │   │   ├── activities
     │   │   │   ├── adapters
     │   │   │   ├── models
     │   │   │   └── utils
     │   │   ├── res/
     │   │   │   ├── layout/
     │   │   │   ├── drawable/
     │   │   │   ├── values/
     │   │   │   └── menu/
     │   │   └── AndroidManifest.xml
     │   └── test/ and androidTest/
     ├── build.gradle
     ├── google-services.json
     └── proguard-rules.pro
```

---

## Tech Stack

### Language
Java (Android)

### UI Components
XML layouts  
RecyclerView  
CardView  
Toolbar and Menu components  

### Storage
Local internal storage  
SharedPreferences  
File based data persistence  

### Build System
Gradle, AndroidX libraries

---

## Setup and Installation

1. Clone the repository
```
git clone https://github.com/your-username/SubBills.git
```

2. Open the project in Android Studio

3. Allow Gradle to sync and download required dependencies

4. Connect an Android device or start an emulator

5. Run the application

---

## Future Improvements

Possible extensions include  
Exporting reports to PDF  
Backup and restore options  
Cloud synchronization  
Advanced analytics and visual charts  
Recurring payments and reminders

---

## License

This project is an intellectual property of its creator.

