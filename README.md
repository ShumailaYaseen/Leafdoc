# LeafDoc: Crop Disease Detector

**Course:** Mobile Application Development (MAD)  
**Assignment:** Assignment 1  
**Group Name:** Team LeafDoc

## Group Members

| Name | Registration ID |
|---|---|
| Shumaila Yaseen | B24S0349CS004 |
| Mubashir Hafeez | B24S0825CS031 |
| Daud Zia | B24S0564CS014 |

## Project Description
LeafDoc is a mobile application designed to help small-scale farmers, home gardeners, and nursery workers identify plant diseases through leaf images.

Users can take a picture of a plant leaf using their phone camera or select an image from the gallery. The application analyzes the image using a deep learning model and predicts the possible plant disease. It also displays a confidence score and provides basic treatment suggestions.

The application will initially support tomato, potato, and pepper plants. It will also allow users to save previous scan results and view their scanning history.

LeafDoc is planned as an offline Android application. It will use a MobileNetV2 model trained on the PlantVillage dataset and converted into TensorFlow Lite format to perform disease detection directly on the device.

## Planned Features

### Must Have Features
- Capture a leaf image using the mobile camera.
- Select a leaf image from the phone gallery.
- Detect plant diseases using an on-device machine learning model.
- Display the predicted disease name and confidence score.
- Provide basic treatment suggestions.
- Save scan results in the application.
- View previous scan records.
- Edit and delete saved scan records.
- Search scans by crop or disease name.
- Filter scans by crop and sort them by date.

### Should Have Features
- Statistics screen showing the number of scans for each disease.
- View statistics for the last 7 days, 30 days, and all recorded scans.

### Could Have Features
- Urdu language support for treatment suggestions.
- Adjustable confidence threshold.
- Option to clear all scan history.
- Export scan history as a CSV file.
- Optional cloud backup.

## Application Screens

The application is planned to include the following seven screens:

1. Home / Scan History
2. Scan Leaf
3. Detection Result
4. Scan Details
5. Edit Scan
6. Statistics
7. Settings

## Technology Stack

| Technology | Purpose |
|---|---|
| Flutter | Mobile application framework |
| Dart | Programming language |
| Material 3 | User interface design |
| SQLite (sqflite) | Local database and scan history |
| image_picker | Camera and gallery image selection |
| TensorFlow Lite | On-device disease detection |
| MobileNetV2 | Deep learning model |
| PlantVillage | Training dataset |
| Android Studio | Development environment |
| VS Code | Code editor |
| Git and GitHub | Version control and project collaboration |
| Figma | UI design and wireframes |

## Setup Instructions

Follow these steps to set up and run the project:

### 1. Install Flutter

Download and install Flutter using the official documentation:

https://docs.flutter.dev/get-started/install

### 2. Configure Flutter

Open the terminal and run:

```bash
flutter doctor
```

Resolve any required setup issues, including Android SDK and emulator configuration.

### 3. Clone the Repository

Clone the project from GitHub:

```bash
git clone https://github.com/ShumailaYaseen/Leafdoc.git
```

Move into the project directory:

```bash
cd leafdoc
```

### 4. Install Dependencies

Run the following command:

```bash
flutter pub get
```

### 5. Run the Application

Start an Android emulator or connect an Android phone with USB debugging enabled.

Then execute:

```bash
flutter run
```

## Repository Structure

```text
leafdoc/
│
├── docs/
│   ├── project-report.pdf
│   ├── wireframes/
│   ├── diagrams/
│   └── screenshots/
│
├── lib/
├── android/
├── test/
├── pubspec.yaml
├── README.md
└── .gitignore
```

## Project Status

**Current Status:** Initial Setup and Hello World Implementation

The initial development phase includes setting up the Flutter environment, creating the project, running the default application, and uploading the initial code to GitHub.

Further application features will be developed in the upcoming stages.

## Repository Link

Add your GitHub repository link here:
https://github.com/ShumailaYaseen/Leafdoc

