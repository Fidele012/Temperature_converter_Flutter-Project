=🌡️ SmartTemp | Temperature Converter App
SmartTemp is a beautifully crafted, mobile-responsive Flutter application designed to help users instantly convert temperatures between Fahrenheit and Celsius. With smooth animations, intelligent input handling, and real-time conversion history, SmartTemp delivers a seamless and intuitive experience for users of all ages.

Whether you're a traveler navigating different weather standards, a student studying science, or simply someone curious about temperature metrics—SmartTemp has you covered.

🚀 Features at a Glance
🔁 Bidirectional Conversion: Instantly convert from Fahrenheit to Celsius and vice versa.

📜 Real-Time History Tracking: Keep track of recent conversions with context-aware labels.

🔄 Animated UI Elements: Engaging and responsive visuals for each interaction.

📱 Adaptive Layout: Optimized views for both portrait and landscape orientations.

🧠 Input Intelligence: Handles invalid or empty inputs gracefully with instant feedback.

🎨 Modern, Clean Interface: Intuitive layout using Material Design best practices.

🧱 Project Structure & Architecture
SmartTemp follows a modular and maintainable architecture with a clean separation of UI, logic, and data models.

pgsql
Copy
Edit
lib/
├── main.dart                        # App entry point
├── screens/
│   └── temperature_converter_screen.dart  # Main screen with responsive layout
├── widgets/
│   ├── temp_calculation_selector.dart     # Toggle between Fahrenheit and Celsius
│   ├── temperature_calculator.dart        # Input/output + conversion logic
│   └── calculation_history.dart           # Scrollable conversion history
├── models/
│   └── conversion_history.dart            # Model for storing conversion entries
└── utils/
    └── utils.dart                         # Temperature conversion logic
📐 Core Components
1. TemperatureConverterScreen
Handles user input, state changes, and renders layouts based on device orientation.

2. ConversionSelector
Toggles between conversion modes (°F → °C or °C → °F) with a clean switch UI.

3. TemperatureSection
Features:

A smart temperature input field

An animated "=" sign

A result box that updates and styles itself dynamically

4. ConversionHistorySection
Visually tracks recent conversions in a scrollable, card-based format.

5. convertTemperature() (in utils.dart)
Handles mathematical logic with high precision:

°F → °C: (F - 32) × 5/9

°C → °F: (C × 9/5) + 32

🛠️ Getting Started
Install Flutter: Ensure you have the Flutter SDK installed on your device.

Clone the Repo:

bash
Copy
Edit
git clone https://github.com/Fidele012/Temperature_converter_Flutter-Project.git
cd smarttemp
Install Dependencies:

bash
Copy
Edit
flutter pub get
Run the App:

bash
Copy
Edit
flutter run
🧪 How to Use
Choose the conversion direction using the selector (F ↔ C).

Type a numeric temperature into the input field.

Tap "CONVERT" to process and view results instantly.

Your conversion will be added to a chronological history list below.

🤖 Conversion Logic
The app uses simple but accurate formulas:

Fahrenheit → Celsius: °C = (°F - 32) × 5/9

Celsius → Fahrenheit: °F = (°C × 9/5) + 32

💡 Inspiration & Goals
This project is part of a hands-on Flutter learning journey. The primary goals are:

Enhancing state management & widget composition skills

Designing adaptive and animated UIs

Building efficient, clean, and scalable Flutter code

🤝 Contributions
Have an idea for a new feature? Found a bug?
Pull requests and suggestions are always welcome!

📩 Contact
For any inquiries, feel free to reach out:
📧 f.ndihokubw1@alustudent.com
