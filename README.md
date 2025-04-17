# Minotoring App

Minotoring App is a Flutter-based application designed to manage a list of items with monitoring capabilities. It allows users to toggle the monitoring status of items and navigate between the item list and monitored items using a bottom navigation bar.

## Features

- **Item Management**: View and manage a list of items.
- **Monitoring**: Toggle the monitoring status of items.
- **Navigation**: Seamlessly switch between the item list and monitored items using a bottom navigation bar.
- **Badge Display**: Display the count of monitored items using a badge.

## Prerequisites

- Basic knowledge of Flutter and Dart.
- Flutter SDK installed on your system.

## Getting Started

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd minotoring_app
   ```

2. Install dependencies:
   ```bash
   flutter pub get
   ```

3. Run the application:
   ```bash
   flutter run
   ```

## Project Structure

- **lib/**: Contains the main application code.
  - `item_model.dart`: Defines the `Item` class.
  - `item_monitor_provider.dart`: Manages the state using `InheritedWidget`.
  - `home_screen.dart`: Main screen with navigation and item management.
  - `item_list_screen.dart`: Displays the list of all items.
  - `item_monitoring_screen.dart`: Displays the list of monitored items.

- **test/**: Contains unit and widget tests.

## Future Improvements

- Add functionality to add, edit, and delete items.
- Integrate persistent storage using `SharedPreferences` or a database.
- Optimize performance for large item lists.
- Enhance UI with animations and custom themes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
