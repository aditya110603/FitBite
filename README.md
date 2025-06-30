# 🥗 Fit Bite

**Fit Bite** is a machine learning–powered iOS app designed to help users track, manage, and improve their nutrition through real-time food recognition, barcode scanning, and integration with Apple Health.

---

## 📱 Key Features

- 🍽️ **Food Recognition from Images**  
  Uses a trained ML model on 200+ food classes to identify foods from photos and provide instant nutritional data.

- 📦 **Barcode Scanning**  
  Retrieves detailed nutrition info for packaged items using Nutritionix API.

- 📊 **Nutrition Dashboard**  
  Displays calories, macros (carbs, protein, fat), and micronutrients via a clean SwiftUI interface.

- 🔄 **Apple Health Integration (HealthKit)**  
  Syncs with HealthKit to match calorie intake with calories burned through physical activity.

- 📆 **Daily/Weekly Tracking**  
  Users can monitor eating trends over time and view summaries by day or week.

- 🎯 **Personalized Recommendations**  
  Suggests meals based on remaining calorie/macro goals tailored to user preferences (weight loss, muscle gain, etc.).

- ⚙️ **Settings & Preferences**  
  Allows users to set nutritional goals, toggle app features, and manage HealthKit permissions.

---

## 📸 App Screenshots

### 🏠 Home Screen
![Home](https://raw.githubusercontent.com/aditya110603/FitBite/main/App%20UI/Picture%202.jpg)

### 🔍 Food Detection
| Log history | Manual entry | Nutrition details |
|------------|-------------|-------------|
| ![Log history](https://raw.githubusercontent.com/aditya110603/FitBite/main/App%20UI/Picture%203.jpg) | ![Manual entry](https://raw.githubusercontent.com/aditya110603/FitBite/main/App%20UI/Picture%204.jpg) | ![Nutrition details](https://raw.githubusercontent.com/aditya110603/FitBite/main/App%20UI/Picture%204.jpg) |

### 📊 Nutrition Dashboard
![Dashboard](https://raw.githubusercontent.com/aditya110603/FitBite/main/App%20UI/Picture%206.jpg)

### ⚙️ Settings Screen
![Settings](https://raw.githubusercontent.com/aditya110603/FitBite/main/App%20UI/Picture%207.jpg)

---

## 💡 How It Works

1. User takes a picture of their meal or scans a barcode.
2. ML model classifies the food and fetches nutritional info.
3. Data is displayed on the dashboard and logged for tracking.
4. Apple Health data is synced to balance intake vs. activity.
5. Personalized meal suggestions guide users to stay on track.

---

## 🛠️ Tech Stack

- **iOS**: Swift, SwiftUI, HealthKit  
- **Machine Learning**: CoreML model (200+ food classes)  
- **Data Storage**: Core Data  
- **API Integration**: Nutritionix for barcode data  
- **Design**: MVVM Architecture, Custom UI components  

 
