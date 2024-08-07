# Cross-Platform Scheduling Application

## Overview

This project involves creating a cross-platform scheduling application that will run on Android and Windows platforms. The application will help users manage their daily schedules by allowing them to create, edit, and view tasks. It will utilize React Native for the frontend and Firebase for the backend services.

## Tech Stack

- **Frontend**: React Native
  - For building mobile applications compatible with Android.
  - Extensible to support Windows using tools like `react-native-windows`.

- **Backend**: Firebase
  - Provides real-time data syncing, authentication, and data storage.
  - Features used:
    - **Firebase Authentication**: For user authentication.
    - **Firestore**: For real-time data storage and synchronization.
    - **Firebase Cloud Messaging (FCM)**: For sending notifications.

## Features

- **User Authentication**: Register, log in, and manage user accounts.
- **Task Management**: Create, edit, and delete tasks.
- **Real-Time Sync**: Sync tasks across devices in real-time.
- **Notifications**: Receive notifications for upcoming tasks or deadlines.

## Project Setup

### Prerequisites

- **Node.js**: Ensure Node.js is installed to manage packages.
- **React Native CLI**: Install React Native CLI globally.
- **Android Studio**: Required for Android development and emulation.
- **Windows Development Tools**: Install necessary tools for Windows development with `react-native-windows`.
- **Firebase Account**: Set up a Firebase project for backend services.

### Installation

1. **Clone the Repository**

    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2. **Install Dependencies**

    For React Native:

    ```bash
    npm install
    ```

    For Android:

    - Open Android Studio and set up the Android SDK.

    For Windows:

    - Follow instructions for setting up React Native for Windows from [React Native Windows Documentation](https://microsoft.github.io/react-native-windows/docs/getting-started).

3. **Configure Firebase**

    - Create a Firebase project and add Firebase configuration files to your project.
    - Update Firebase settings in the project as necessary.

4. **Run the Application**

    For Android:

    ```bash
    npx react-native run-android
    ```

    For Windows:

    ```bash
    npx react-native run-windows
    ```

## Development

### Directory Structure

- **`/android`**: Contains Android-specific build files and configurations.
- **`/windows`**: Contains Windows-specific build files and configurations.
- **`/src`**: Contains the source code for React Native components.
- **`/firebase`**: Contains Firebase configuration and setup files.

### Common Commands

- **Start Development Server**

    ```bash
    npx react-native start
    ```

- **Build and Run Application**

    ```bash
    npx react-native run-android
    npx react-native run-windows
    ```

## Testing

- **Unit Tests**: Write and run unit tests to verify individual components.
- **Integration Tests**: Test the integration between frontend and backend services.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please follow the standard GitHub workflow for contributions, including forking the repository, making changes, and submitting pull requests.

## Contact

For any inquiries, please contact:

- **Email**: <rmor760@WGU.edu>
- **GitHub**: [Morganiron](https://github.com/morganiron)
