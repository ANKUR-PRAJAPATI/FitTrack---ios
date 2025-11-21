# 💪 FitTrack - iOS Fitness Tracking App

![Swift](https://img.shields.io/badge/swift-F54A2A?style=for-the-badge&logo=swift&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=ios&logoColor=white)
![Xcode](https://img.shields.io/badge/Xcode-007ACC?style=for-the-badge&logo=Xcode&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0D96F6?style=for-the-badge&logo=swift&logoColor=white)
![HealthKit](https://img.shields.io/badge/HealthKit-FF2D55?style=for-the-badge&logo=apple&logoColor=white)

A modern, feature-rich iOS fitness tracking application built with Swift and SwiftUI. Track workouts, monitor calories, set goals, and visualize your fitness journey with beautiful charts and insights.

---

## 📋 Table of Contents

- [Problem Statement](#-problem-statement)
- [Solution](#-solution)
- [Tech Stack](#-tech-stack)
- [Tools Used](#-tools-used)
- [Features](#-features)
- [Screenshots](#-screenshots)
- [Architecture](#-architecture)
- [Getting Started](#-getting-started)
- [Installation](#-installation)
- [Usage](#-usage)
- [Future Scope](#-future-scope)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🎯 Problem Statement

Modern fitness enthusiasts face several challenges when trying to maintain a healthy lifestyle:

- **Fragmented Tracking** 📊 - Multiple apps needed for different fitness metrics
- **Complex Interfaces** 🤯 - Overwhelming UIs that discourage daily use
- **Lack of Motivation** 😴 - No personalized goals or progress visualization
- **Manual Data Entry** ✍️ - Time-consuming manual workout logging
- **Poor Integration** 🔌 - Limited integration with Apple Health and wearables
- **Inconsistent Tracking** 📉 - Difficulty maintaining workout routines
- **No Insights** 🔍 - Missing analytics and progress trends
- **Privacy Concerns** 🔒 - Health data stored on external servers

---

## ✨ Solution

FitTrack is a comprehensive iOS fitness tracking solution that addresses these challenges:

### 🚀 Key Features

- **All-in-One Platform** - Track workouts, nutrition, sleep, and water intake in one app
- **Intuitive SwiftUI Design** - Clean, modern interface following iOS design guidelines
- **Smart Goal Setting** - Personalized goals based on user profile and activity level
- **Apple Health Integration** - Seamlessly sync with HealthKit and Apple Watch
- **Automatic Tracking** - Auto-detect workouts using Core Motion
- **Visual Analytics** - Beautiful charts showing progress over time
- **Local-First Privacy** - All data stored locally with optional iCloud sync
- **Offline Capable** - Full functionality without internet connection
- **Widget Support** - Home screen and Lock screen widgets for quick access

---

## 🛠️ Tech Stack

### Core Technologies
- **Swift 5.9** 🔶 - Primary programming language
- **SwiftUI** 🎨 - Modern declarative UI framework
- **UIKit** 📱 - Legacy components and advanced customization
- **Combine** 🔄 - Reactive programming for data flow
- **Swift Concurrency** ⚡ - async/await for asynchronous operations

### Apple Frameworks
- **HealthKit** ❤️ - Health and fitness data integration
- **Core Data** 💾 - Local data persistence
- **CloudKit** ☁️ - iCloud synchronization
- **Core Motion** 🏃 - Activity and motion tracking
- **WatchKit** ⌚ - Apple Watch companion app
- **WidgetKit** 📊 - Home screen and Lock screen widgets
- **UserNotifications** 🔔 - Local and push notifications
- **Charts Framework** 📈 - Native Swift charts (iOS 16+)

### Design & UI
- **SF Symbols** 🔣 - Apple's icon system
- **SwiftUI Animations** ✨ - Smooth transitions and effects
- **Dark Mode** 🌙 - Full dark mode support
- **Accessibility** ♿ - VoiceOver and Dynamic Type support

---

## 🔨 Tools Used

### Development Environment
- **Xcode 15+** 💻 - Official Apple IDE
- **Swift Package Manager (SPM)** 📦 - Dependency management
- **Git** 📚 - Version control
- **GitHub** 🐙 - Code repository and collaboration

### Design Tools
- **Figma** 🎨 - UI/UX design and prototyping
- **Sketch** ✏️ - Interface design
- **SF Symbols App** 🔤 - Icon browsing and customization

### Testing & Debugging
- **XCTest** 🧪 - Unit and UI testing
- **Instruments** 🔬 - Performance profiling
- **TestFlight** ✈️ - Beta testing platform
- **Firebase Crashlytics** 🔥 - Crash reporting

### Analytics & Monitoring
- **Firebase Analytics** 📊 - User behavior tracking
- **App Store Connect** 📱 - App distribution and analytics
- **Sentry** 🐛 - Error tracking and monitoring

### CI/CD
- **Fastlane** 🚀 - Automated build and deployment
- **GitHub Actions** ⚡ - CI/CD workflows
- **Bitrise** 🔧 - Mobile CI/CD platform

---

## ⚡ Features

### Core Functionality

#### 🏋️ Workout Tracking
- ✅ Pre-defined workout types (Running, Cycling, Swimming, Strength, Yoga)
- ✅ Custom workout creation
- ✅ Auto-detect workouts using motion sensors
- ✅ Real-time heart rate monitoring (with Apple Watch)
- ✅ Distance, duration, and calorie tracking
- ✅ GPS route mapping for outdoor activities
- ✅ Workout history and statistics

#### 🍎 Nutrition Tracking
- ✅ Calorie counter with extensive food database
- ✅ Macro tracking (Protein, Carbs, Fats)
- ✅ Barcode scanner for quick food entry
- ✅ Meal logging (Breakfast, Lunch, Dinner, Snacks)
- ✅ Water intake tracker
- ✅ Custom food creation
- ✅ Daily nutrition goals

#### 🎯 Goal Setting & Progress
- ✅ Personalized fitness goals
- ✅ Weekly and monthly challenges
- ✅ Streak tracking for motivation
- ✅ Achievement badges and milestones
- ✅ Progress photos comparison
- ✅ Body measurements tracking
- ✅ Weight tracking with trend analysis

#### 📊 Analytics & Insights
- ✅ Interactive charts (weekly, monthly, yearly)
- ✅ Workout duration trends
- ✅ Calorie burn analysis
- ✅ Personal records and achievements
- ✅ Activity heatmap
- ✅ Statistical summaries
- ✅ Export data to CSV/PDF

### Technical Features

#### 🔐 Privacy & Security
- ✅ Local-first data storage
- ✅ Face ID / Touch ID authentication
- ✅ Encrypted data storage
- ✅ Privacy-focused design
- ✅ No third-party data sharing

#### ⌚ Apple Watch Integration
- ✅ Standalone Apple Watch app
- ✅ Real-time workout tracking
- ✅ Heart rate monitoring
- ✅ Activity rings display
- ✅ Complications support
- ✅ Haptic feedback

#### 📱 iOS Features
- ✅ Home screen widgets (small, medium, large)
- ✅ Lock screen widgets (iOS 16+)
- ✅ Live Activities (workout tracking)
- ✅ Dynamic Island support (iOS 16+)
- ✅ Shortcuts integration
- ✅ Siri integration
- ✅ Share Sheet support

#### 🌐 Sync & Backup
- ✅ iCloud automatic sync
- ✅ Cross-device synchronization
- ✅ Data export/import
- ✅ Automatic backup
- ✅ Offline mode with queue sync

---

## 📸 Screenshots

<div align="center">

| Home Screen | Workout Tracking | Analytics |
|------------|------------------|-----------|
| ![Home](screenshots/home.png) | ![Workout](screenshots/workout.png) | ![Analytics](screenshots/analytics.png) |

| Nutrition | Goals | Profile |
|-----------|-------|---------|
| ![Nutrition](screenshots/nutrition.png) | ![Goals](screenshots/goals.png) | ![Profile](screenshots/profile.png) |

</div>

---

## 🏗️ Architecture

### MVVM Pattern

```
┌─────────────────────────────────────────────┐
│              SwiftUI Views                   │
│  (HomeView, WorkoutView, NutritionView)     │
└──────────────────┬──────────────────────────┘
                   │
                   │ @StateObject / @ObservedObject
                   │
┌──────────────────▼──────────────────────────┐
│           ViewModels                         │
│  (WorkoutViewModel, NutritionViewModel)     │
│  - @Published properties                     │
│  - Business logic                            │
└──────────────────┬──────────────────────────┘
                   │
                   │ Dependency Injection
                   │
┌──────────────────▼──────────────────────────┐
│              Services                        │
│  - HealthKitService                          │
│  - CoreDataService                           │
│  - CloudKitService                           │
└──────────────────┬──────────────────────────┘
                   │
      ┌────────────┼────────────┐
      │            │            │
┌─────▼─────┐ ┌───▼────┐ ┌────▼─────┐
│ HealthKit │ │ Core   │ │ CloudKit │
│           │ │ Data   │ │          │
└───────────┘ └────────┘ └──────────┘
```

### Project Structure

```
FitTrack/
├── App/
│   ├── FitTrackApp.swift
│   └── AppDelegate.swift
├── Models/
│   ├── Workout.swift
│   ├── Nutrition.swift
│   ├── Goal.swift
│   └── User.swift
├── Views/
│   ├── Home/
│   ├── Workout/
│   ├── Nutrition/
│   ├── Analytics/
│   └── Profile/
├── ViewModels/
│   ├── WorkoutViewModel.swift
│   ├── NutritionViewModel.swift
│   └── AnalyticsViewModel.swift
├── Services/
│   ├── HealthKitService.swift
│   ├── CoreDataService.swift
│   ├── CloudKitService.swift
│   └── NotificationService.swift
├── Utilities/
│   ├── Extensions/
│   ├── Helpers/
│   └── Constants.swift
├── Resources/
│   ├── Assets.xcassets
│   └── Localizable.strings
└── Tests/
    ├── UnitTests/
    └── UITests/
```

---

## 🚀 Getting Started

### Prerequisites

- macOS 13.0 (Ventura) or later
- Xcode 15.0 or later
- iOS 16.0+ target device or simulator
- Apple Developer Account (for device testing)
- CocoaPods or Swift Package Manager

### System Requirements

```
Minimum iOS Version: 16.0
Supported Devices: iPhone 12 and newer
Apple Watch: watchOS 9.0+
```

---

## 📥 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/ANKUR-PRAJAPATI/FitTrack-iOS.git
cd FitTrack-iOS
```

### 2. Install Dependencies

#### Using Swift Package Manager (Recommended)
```bash
# Dependencies are automatically resolved by Xcode
# Just open the project
open FitTrack.xcodeproj
```

#### Using CocoaPods
```bash
pod install
open FitTrack.xcworkspace
```

### 3. Configure Signing

1. Open `FitTrack.xcodeproj` in Xcode
2. Select the project in the navigator
3. Go to "Signing & Capabilities"
4. Select your Team
5. Update Bundle Identifier to be unique

### 4. Add Capabilities

Ensure the following capabilities are enabled:

- ✅ HealthKit
- ✅ Push Notifications
- ✅ Background Modes (Location updates, Background fetch)
- ✅ iCloud (CloudKit, Key-value storage)
- ✅ App Groups (for Watch connectivity)

### 5. Update Info.plist

Add required privacy descriptions:

```xml
<key>NSHealthShareUsageDescription</key>
<string>FitTrack needs access to read your health data to track workouts and calories.</string>

<key>NSHealthUpdateUsageDescription</key>
<string>FitTrack needs access to save workout data to your Health app.</string>

<key>NSMotionUsageDescription</key>
<string>FitTrack uses motion data to automatically detect workouts.</string>

<key>NSLocationWhenInUseUsageDescription</key>
<string>FitTrack needs your location to track outdoor workouts.</string>
```

### 6. Build and Run

```bash
# Command + R in Xcode
# Or use command line
xcodebuild -scheme FitTrack -destination 'platform=iOS Simulator,name=iPhone 15 Pro' build
```

---

## 💻 Usage

### Basic Workflow

#### 1. First Launch Setup
```swift
// User onboarding flow
- Welcome screen
- Health permissions request
- Profile setup (age, weight, height, goals)
- Notification preferences
```

#### 2. Logging a Workout
```swift
// Start workout
1. Tap "Start Workout" button
2. Select workout type
3. Grant location permission (for outdoor workouts)
4. Tap "Start" and begin exercising
5. Tap "Finish" when done
6. Review and save workout summary
```

#### 3. Tracking Nutrition
```swift
// Log a meal
1. Navigate to Nutrition tab
2. Tap "+" to add food
3. Search food database or scan barcode
4. Adjust serving size
5. Tap "Add" to log meal
```

#### 4. Setting Goals
```swift
// Create a fitness goal
1. Go to Profile > Goals
2. Tap "Add Goal"
3. Select goal type (Weight, Workout frequency, etc.)
4. Set target and deadline
5. Track progress on Analytics tab
```

---

## 🧪 Testing

### Unit Tests

```bash
# Run all tests
xcodebuild test -scheme FitTrack -destination 'platform=iOS Simulator,name=iPhone 15 Pro'

# Run specific test
xcodebuild test -scheme FitTrack -only-testing:FitTrackTests/WorkoutViewModelTests
```

### UI Tests

```bash
# Run UI tests
xcodebuild test -scheme FitTrack -destination 'platform=iOS Simulator,name=iPhone 15 Pro' -only-testing:FitTrackUITests
```

### Test Coverage

```bash
# Generate code coverage report
xcodebuild test -scheme FitTrack -enableCodeCoverage YES -destination 'platform=iOS Simulator,name=iPhone 15 Pro'
```

---

## 🔮 Future Scope

### Planned Features

- [ ] **Social Features** 👥 - Follow friends, share workouts, leaderboards
- [ ] **AI Coach** 🤖 - Personalized workout recommendations using ML
- [ ] **Meal Planning** 🍽️ - Weekly meal plans based on goals
- [ ] **Exercise Library** 📚 - Video tutorials for 500+ exercises
- [ ] **Integration APIs** 🔗 - Strava, Fitbit, Garmin Connect
- [ ] **Advanced Analytics** 📊 - Muscle group tracking, recovery metrics
- [ ] **Challenges** 🏆 - Community challenges and competitions
- [ ] **Personal Trainer** 💼 - Connect with certified trainers
- [ ] **Workout Plans** 📋 - Pre-built programs (5K training, muscle building)
- [ ] **Rest Timer** ⏱️ - Customizable rest intervals between sets
- [ ] **Plate Calculator** ⚖️ - Barbell weight calculator for strength training
- [ ] **Voice Commands** 🎤 - Siri integration for hands-free tracking
- [ ] **AR Workouts** 🥽 - ARKit-powered form checking
- [ ] **Music Integration** 🎵 - Apple Music workout playlists
- [ ] **Sleep Tracking** 😴 - Detailed sleep analysis
- [ ] **Meditation** 🧘 - Guided meditation sessions
- [ ] **Hydration Reminders** 💧 - Smart water intake reminders
- [ ] **Body Composition** 📐 - Body fat percentage tracking
- [ ] **Recipe Database** 👨‍🍳 - Healthy recipes with nutritional info
- [ ] **Supplement Tracking** 💊 - Log vitamins and supplements

### Technical Improvements

- [ ] **iPad Support** - Optimized layout for iPad
- [ ] **macOS App** - Catalyst or native macOS version
- [ ] **visionOS Support** - Apple Vision Pro compatibility
- [ ] **ML Models** - On-device ML for workout recognition
- [ ] **App Clips** - Lightweight version for quick access
- [ ] **HealthKit Sync** - Bidirectional sync improvements
- [ ] **GraphQL API** - Efficient data fetching (if backend added)
- [ ] **Localization** - Support for 20+ languages
- [ ] **Accessibility** - Enhanced VoiceOver support

---

## 🛠️ Development

### Code Style

Following Swift API Design Guidelines:

```swift
// Use clear, descriptive names
func calculateBMR(weight: Double, height: Double, age: Int) -> Double

// Prefer guard for early exits
guard let workout = currentWorkout else { return }

// Use type inference when clear
let calories = 2000 // Instead of let calories: Int = 2000

// SwiftUI naming conventions
struct WorkoutListView: View {
    @StateObject private var viewModel = WorkoutViewModel()
    
    var body: some View {
        // View code
    }
}
```

### Git Workflow

```bash
# Feature branch
git checkout -b feature/add-meal-planner

# Commit with meaningful messages
git commit -m "feat: Add meal planning feature with weekly calendar"

# Push and create PR
git push origin feature/add-meal-planner
```

---

## 🤝 Contributing

Contributions are welcome! Please follow these guidelines:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Follow Swift style guidelines
4. Write unit tests for new features
5. Update documentation
6. Commit your changes (`git commit -m 'feat: Add some AmazingFeature'`)
7. Push to the branch (`git push origin feature/AmazingFeature`)
8. Open a Pull Request

### Commit Message Convention

```
feat: Add new feature
fix: Bug fix
docs: Documentation update
style: Code style changes
refactor: Code refactoring
test: Add tests
chore: Maintenance tasks
```

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Ankur Prajapati**

💼 **LinkedIn:** [linkedin.com/in/ankur-prajapati-5618a1258](https://linkedin.com/in/ankur-prajapati-5618a1258)  
📧 **Email:** prajapatiankur37@gmail.com  
💻 **GitHub:** [@ANKUR-PRAJAPATI](https://github.com/ANKUR-PRAJAPATI)  
🔗 **Project Link:** [FitTrack iOS App](https://github.com/ANKUR-PRAJAPATI/FitTrack-iOS)

---

## 🙏 Acknowledgments

- Apple for Swift, SwiftUI, and comprehensive frameworks
- HealthKit documentation and sample code
- iOS developer community for best practices
- SF Symbols for beautiful iconography
- Beta testers and early adopters
- Open-source Swift community
- Ray Wenderlich tutorials for Swift learning
- Hacking with Swift for SwiftUI resources

---

## 📱 Download

<div align="center">

[![Download on the App Store](https://tools.applemediaservices.com/api/badges/download-on-the-app-store/black/en-us?size=250x83)](https://apps.apple.com)

*Coming soon to the App Store!*

</div>

---

<div align="center">
  
### ⭐ If you found this project helpful, please consider giving it a star!

**Made with ❤️ and lots of ☕**

📬 **Feel free to reach out for collaborations or questions!**

</div>
