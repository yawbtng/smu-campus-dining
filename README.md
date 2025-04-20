# SMU Campus Dining Mobile App

## Overview
A cross-platform mobile application that revolutionizes the SMU dining experience by providing real-time dining hall information, calorie tracking, and AI-powered meal recognition. Built by students, for students.

### Core Features
- 🍽️ **Live Menu Updates**: Real-time menu information from both SMU dining halls
- 📱 **Cross-Platform**: Available on both iOS and Android devices
- 📊 **Calorie Tracking**: MyFitnessPal-style calorie counting for dining hall meals
- 📸 **AI Food Recognition**: Take a photo of your meal to automatically estimate calories
- 🔄 **Cloud Sync**: Save and access your meal history across devices

## Project Timeline
Development spans from May 2025 to October 2025, divided into six major phases:

### Phase 1: Foundations (May 2025)
- Learning JavaScript, React, and React Native fundamentals
- Setting up development environment and project repository
- Creating basic app skeleton and API endpoints

### Phase 2: MVP Build (June 2025)
- Implementing live menu scraping from dining halls
- Building core menu display and logging functionality
- Basic data persistence and user testing

### Phase 3: Feature Enhancement (July 2025)
- Adding camera integration and food recognition
- Implementing Firebase authentication and cloud storage
- UI/UX improvements and closed beta testing

### Phase 4: Public Launch (August 2025)
- Android Play Store beta release
- iOS TestFlight pilot program
- Analytics integration and bug fixes

### Phase 5: Feedback & Analytics (September 2025)
- Public iOS App Store release
- Push notification implementation
- Performance optimization

### Phase 6: Expansion (October 2025)
- Advanced nutrition tracking features
- Admin dashboard development
- Campus-wide marketing campaign

## Tech Stack

### Frontend
- **Framework**: React Native with Expo
- **State Management**: React Context + Hooks
- **UI Components**: Custom components with SMU theming
- **Navigation**: React Navigation

### Backend
- **Server**: Node.js + Express
- **Database**: Firebase Cloud Firestore
- **Authentication**: Firebase Auth
- **Image Analysis**: LogMeal/CalorieMama API

### DevOps
- **Version Control**: Git + GitHub
- **CI/CD**: GitHub Actions
- **Hosting**: Render/Railway
- **Analytics**: Firebase Analytics/Amplitude

## Getting Started

### Prerequisites
- Node.js (LTS version)
- npm or yarn
- Expo CLI
- Android Studio (for Android development)
- Xcode (for iOS development, macOS only)

### Installation

1. Clone the repository:
\`\`\`bash
git clone https://github.com/yawbtng/smu-campus-dining.git
cd smu-campus-dining
\`\`\`

2. Install dependencies:
\`\`\`bash
npm install
# or
yarn install
\`\`\`

3. Start the development server:
\`\`\`bash
expo start
\`\`\`

4. Run on your preferred platform:
- Press 'a' for Android
- Press 'i' for iOS
- Scan QR code with Expo Go app for physical device

### Environment Setup

Create a .env file in the root directory:
\`\`\`
FIREBASE_API_KEY=your_api_key
FIREBASE_AUTH_DOMAIN=your_auth_domain
FIREBASE_PROJECT_ID=your_project_id
FOOD_RECOGNITION_API_KEY=your_api_key
\`\`\`

## Contributing

This project is developed by Yaw and Chris as part of a learning journey in mobile app development. We welcome feedback and suggestions from the SMU community.

### Development Workflow
1. Create a feature branch
2. Implement changes
3. Submit a pull request
4. Code review
5. Merge to main



## Acknowledgments

- SMU Dining Services for menu data
- CampusDish platform
- SMU Entrepreneurship Club for support and feedback
- Our beta testers and early adopters

## Contact

For questions or feedback about the app:
- Email: [yboateng@smu.edu](mailto:your-email@smu.edu)
- GitHub Issues: [Project Issues](https://github.com/yawbtng/smu-campus-dining/issues)

