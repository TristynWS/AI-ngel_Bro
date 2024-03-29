# AI-ngel Bro App

AI-ngel Bro simplifies understanding the emotional subtext of messages using advanced AI. This mobile app decodes texts filled with complex emotions, presenting them in clear, simple terms. It's built with a Flutter frontend for a seamless cross-platform user experience and a Flask backend for processing and AI model interfacing.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development, testing, and contributions.

### Prerequisites

- Git
- Python 3.8+
- Flask
- Flutter
- Android Studio (optional, for Android app development and emulation)
- iOS Simulator or Android Emulator setup for mobile app testing

### Setup

#### Clone the Repository

```bash
git clone https://github.com/yourusername/ai-ngel-bro.git
cd ai-ngel-bro
```

#### Backend Setup

1. **Navigate to the Backend Directory**:

```bash
cd backend
```

2. **Create and Activate a Virtual Environment**:

Windows:

```bash
python -m venv venv
.\venv\Scripts\activate
```

macOS/Linux:

```bash
python3 -m venv venv
source venv/bin/activate
```

3. **Install Dependencies**:

```bash
pip install -r requirements.txt
```

4. **Run the Flask Application**:

```bash
python app.py
```

Your Flask backend should now be running on `http://127.0.0.1:5000/`.

#### Frontend Setup (Mobile App with Flutter)

1. **Navigate to the Frontend Directory**:

```bash
cd ../frontend
```

2. **Run the Flutter App**:

Ensure an emulator is running or a device is connected, then:

```bash
flutter pub get
flutter run
```

### Running Tests

Explain how to run the automated tests for this system. Tests for both the backend (Flask) and frontend (Flutter) should be documented here.

### Deployment

Add additional notes about how to deploy this on a live system. Consider separate instructions for backend (possibly Heroku, AWS, or Google Cloud) and frontend (deployment to Google Play Store and Apple App Store).

## Built With

- [Flutter](https://flutter.dev/) - The cross-platform mobile framework used.
- [Flask](https://flask.palletsprojects.com/) - The backend framework.
- [Python](https://www.python.org/) - Used for backend development.
- [Android Studio](https://developer.android.com/studio) - Recommended for Android app development and emulation.
- [Git](https://git-scm.com/) - Used for version control.

## Contributing

TBD

## Versioning

TBD

- **Tristyn Eddie Watkins-Sanchez** - *Initial work* - [TristynWS](https://github.com/TristynWS)

## License

TBD

## Acknowledgments

TBD 
