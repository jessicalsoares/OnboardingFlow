# OnboardingFlow

OnboardingFlow is an application designed to guide first-time users through its main features, creating a welcoming and intuitive onboarding experience.

This app was developed as part of a hands‑on study in SwiftUI, based on the official Apple tutorial.

# Features
- **Onboarding Flow**  
  Swipeable onboarding screens that introduce the app’s core functions.

- **Page Indicators**  
  Visual dots indicating the current page in the onboarding sequence.

- **"Get Started" Button**  
  Completes onboarding and transitions users to the main app content.

- **Persistent State**  
  Tracks whether onboarding has been completed using `UserDefaults`, so it only shows once.
  
# Tech Stack
🌐 SwiftUI: Apple’s modern declarative UI framework.<br>
📱 Xcode: Apple’s official development environment.

# Screenshots

<img src="https://github.com/jessicalsoares/OnboardingFlow/assets/138133901/32cd95c4-df23-448c-a41c-421d2a55a482" width="200">
<img src="https://github.com/jessicalsoares/OnboardingFlow/assets/138133901/b1984770-b797-46d5-b018-a782673084cd" width="200">

# Learnings
While building this app, I learned how to:

- Using `TabView` and `PageTabViewStyle` to build swipeable onboarding views;
- Managing first-time user state with `@AppStorage` or `UserDefaults` flags;
- Implementing simple navigation logic to switch views after onboarding;
- Working with SwiftUI state management using `@State` and `@Binding`;

# Reference
- Apple Developer – *Onboarding Flow* concept utilized in SwiftUI tutorials like the “#30DaysOfSwift” series

# Author
Feito por **Jéssica Soares**  
[github.com/jessicalsoares](https://github.com/jessicalsoares)
