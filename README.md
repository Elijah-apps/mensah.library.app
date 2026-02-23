# Mensah Library App

A modern, feature-rich library application built with Flutter and Firebase.

## Author

**Elijah Ekpen Mensah**

## About the App

This app provides a seamless reading experience with access to a vast collection of e-books. Built with Flutter for cross-platform compatibility and Firebase for real-time data storage and authentication.

## Features

- 📚 Browse and search for books
- 📖 Read books with built-in PDF viewer
- 🔍 Advanced search functionality
- 📱 Responsive design for all screen sizes
- 🔐 User authentication
- 📊 Real-time data sync
- 💾 Offline reading support
- 🌙 Dark/light mode support

## Technologies Used

- **Flutter**: Cross-platform UI toolkit
- **Firebase**: Backend-as-a-Service (BaaS)
- **PDF Viewer**: For reading e-books
- **Provider**: State management
- **Hive**: Local storage

## Getting Started

### Prerequisites

- Flutter SDK (version 3.19 or newer)
- Firebase account and project
- Android Studio or VS Code with Flutter extensions

### Installation

1. Clone the repository
   ```bash
   git clone [repository-url]
   ```

2. Navigate to the project directory
   ```bash
   cd mensah.library.app
   ```

3. Install dependencies
   ```bash
   flutter pub get
   ```

4. Set up Firebase
   - Create a new Firebase project
   - Add Android and iOS apps to your Firebase project
   - Download the `google-services.json` file and place it in the `android/app/` directory
   - Download the `GoogleService-Info.plist` file and place it in the `ios/Runner/` directory

5. Run the app
   ```bash
   flutter run
   ```

## Screenshots

![App Screenshot](https://user-images.githubusercontent.com/108933534/220394896-29764034-d289-4797-b1e6-d37da7455be1.png)

## Project Structure

```
lib/
├── main.dart                # Entry point of the app
├── components/              # Reusable UI components
├── model/                   # Data models
├── providers/               # State management
├── repositories/            # Data repositories
├── screens/                 # Screen widgets
└── utils/                   # Utility functions and constants
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or feedback, please contact:
- Email: [your-email@example.com]
- LinkedIn: [Elijah Ekpen Mensah]
- GitHub: [@yourusername]

---

Made with ❤️ by Elijah Ekpen Mensah
