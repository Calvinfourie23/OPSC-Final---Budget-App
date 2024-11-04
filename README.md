# BudgetApp

## Team Members
- **Mohlao Makhale** - St10082707
- **Calvin Fourie** - ST10121193
- **Naeem Brown** - ST10231877
- **Ben Rush** - ST10132792
- **Jaiden Charles** - ST10145509

---

## Purpose of the App
The **BudgetApp** is designed to help users manage their finances efficiently by tracking expenses, setting budgets, and visualizing spending patterns. Aimed at individuals seeking better financial control, it provides tools to categorize expenses, monitor cash flow, and make informed financial decisions.

---

## Design Considerations
The app was developed with a focus on simplicity, performance, and scalability. Key design decisions include:

- **Architecture**: The app utilizes **MVVM (Model-View-ViewModel)** architecture, ensuring a clear separation of concerns, making the codebase modular and maintainable.
- **Libraries and Dependencies**:
  - **Retrofit** for networking
  - **OkHttp** for HTTP operations
  - **Filament** for advanced graphics rendering  
  This combination offers a smooth and responsive user experience.
- **Dependency Management**:
  - **AGP (Android Gradle Plugin)**: 8.4.0
  - **Kotlin**: 1.9.0  
  Core libraries like `coreKtx`, `lifecycleRuntimeKtx`, and `activityCompose` are at their latest stable versions, ensuring compatibility and security.
- **UI Framework**: The app leverages **Jetpack Compose** for modern, declarative UI creation, providing a smooth and interactive experience for users.

---

## GitHub and GitHub Actions Usage
The project utilizes **GitHub** for version control, allowing collaborative development and tracking of changes. **GitHub Actions** are set up to automate tasks such as:

- **Continuous Integration (CI)**: Builds and tests are automatically triggered on each commit to ensure that the codebase remains stable and that no new changes introduce bugs.
- **Deployment Pipeline**: GitHub Actions workflows are configured to deploy the latest version of the app to relevant environments, streamlining the deployment process.

This setup improves efficiency and ensures a consistent, high-quality codebase.

---

## Release Notes

### Latest Version
- **Added Features**:
  - **Expense Categorization**: Users can now categorize their expenses for better tracking and reporting.
  - **Budget Alerts**: New feature to alert users when they are close to exceeding their budget.
  - **Data Sync**: Implemented data synchronization for seamless access across multiple devices.
  - **Multi-Language Support**: Added support for 2 additional languages, enhancing accessibility for a wider audience.
  - **Offline Capabilities**: Users can now access and manage their budget information without an internet connection.
  - **Notification System**: Implemented notifications to remind users of upcoming bills, budget limits, and other important events.
- **Improvements**:
  - **UI Enhancements**: Improved the layout and visual design for better usability and aesthetic appeal.
  - **Performance Optimization**: Reduced load times and optimized background processes.
  - **Bug Fixes**: Addressed issues reported in the prototype, including app crashes under specific conditions.

### Previous Versions
- **Prototype Version**:
  - Initial basic functionalities for adding expenses, viewing lists, and calculating totals.

---

## YouTube Demo
For a detailed walkthrough of the app, [watch the demo on YouTube](https://www.youtube.com/@MoneyMapMM/videos).

---

## Images and Visuals
Screenshots and diagrams are included to illustrate key features, user flows, and the structure of the application.

---

## Additional Documentation
Further details on design considerations, code structure, and future development goals are available in the additional documentation within the repository.

---

#Video Link
Youtube Demo Video Below:
https://youtu.be/wUlehHYR9s8?si=yYJ3hzmB2Vx2xBHZ