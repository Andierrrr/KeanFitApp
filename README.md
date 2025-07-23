# KeanFit

# 🏋️‍♂️ KeanFit – Fitness App for the Kean University Community

**KeanFit** is a health and wellness mobile application built specifically for the Kean University community — including students, faculty, and staff. Unlike generic fitness apps, KeanFit provides personalized workout plans, step tracking, reminders, and features tailored to the unique needs and routines of Kean University members.

---

## 📱 Key Features

- 🎯 **Goal Tracking**: Set and monitor your fitness and step goals.
- 🧘‍♀️ **Workout Modules**: Access Cardio, Yoga, and Strength workouts.
- 🥗 **Meal Preferences**: Save your dietary goals and preferences.
- 📊 **User Statistics**: Visualize personal fitness progress over time.
- 🔔 **Reminders**: Get notified to stay on track with your fitness schedule.
- 👣 **Step Tracker**: Track your daily steps to stay active.
- 🧭 **Kean-Specific Design**: Designed with Kean University's unique student/staff needs in mind.
- 🔐 **Secure Authentication**: Firebase-based login system with password reset and update flows.

---

## 🔧 Tech Stack

- **Frontend**: React Native (Expo)
- **Backend Services**: Firebase Authentication, Firestore, Firebase Hosting
- **Navigation**: React Navigation
- **Other Tools**: JavaScript, Node.js, and Expo ecosystem

---

## 📁 Project Structure

```bash
KeanFitApp/
├── assets/                    # Images and static assets
├── components/               # Reusable UI components (Cardio, Strength, Yoga, etc.)
├── constants/                # Constants like category definitions
├── navigation/               # App navigation setup (AppNavigator.js)
├── screens/                  # Screens for each major view in the app
│   ├── DashboardScreen.js
│   ├── MyWorkoutScreen.js
│   ├── MealPreferencesScreen.js
│   └── ...
├── .expo/                    # Expo-specific config
├── App.js                    # Entry point
└── package.json

