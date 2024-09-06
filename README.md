# • Athom Studios | Recruitment
Develop a Flutter application for Android and iOS

[[English](https://github.com/Athom-Studios/mobile-challenge/blob/main/README.md) | [Português](https://github.com/Athom-Studios/mobile-challenge/blob/main/README.pt.md)]

## Instructions
- Fork this repository to your personal GitHub account.
- Follow the specifications below.
- Create a README with instructions on how to compile, test, and run the project.
- The repository link should be sent to the email mathuscardoso@gmail.com with the subject **Flutter Developer Test**.

## Technical Specifications
- Use Flutter's Cupertino widgets, aiming for an experience closer to iOS.
- The app must be able to generate and scan QR codes.
- Implement smooth animations for transitions between screens.
- Automated tests (Desirable).
- Responsive layout to work well on different screen sizes (smartphones and tablets).

## Functional Specifications

### Home Screen
This screen will have two main functionalities positioned at the center of the screen:

- **Generate QR Code**: A button that takes the user to a form where they can input text/URL to generate a QR code.
- **Scan QR Code**: A button that takes the user to the scan screen using the device's camera.

### QR Code Generation Feature
- The user can input text or URL, and by pressing the "Generate" button, a corresponding QR code will be displayed on the screen.
- The generated QR code should be displayed in a clean layout with options to save the QR code image on the device or share it directly.
- Use **CupertinoTextField**, **CupertinoButton**, and other Cupertino components for the interface.

### QR Code Scanning Feature
- The app must request the necessary permissions to access the device's camera.
- After scanning the QR code, the app should display the encoded content on a new screen.
- The app should allow copying the scanned content to the clipboard and redirecting to URLs if the content is a link.

### Additional Details
- If the scan fails or a valid QR code is not found, an error message should be displayed to the user.
- The application should use Flutter plugins for scanning and generating QR codes, such as **qr_flutter** and **mobile_scanner**.

### Additional Requirements:
- **Animation**: When generating the QR code or returning with the scan result, the screen should display a smooth transition between screens using Cupertino animations.
- **Validation**: The input field for generating QR codes must be validated. For example, empty input should not be accepted.
- **Code Sharing**: After generating a QR code, the user should be able to share the code directly through messaging apps or social networks.

### Wireframe
You are free to design the layout, but the main elements should be well-distributed to provide a good user experience.

## What Will Be Evaluated?
- Project organization.
- Code logic.
- Git usage.
- Componentization and widget reuse.
- Proper use of camera permissions.
- Automated tests (if applicable).
- Responsiveness and compatibility with different devices.
- Quality of animations and screen transitions.

## Instructions for Compiling and Running the Project

### Prerequisites:
- Install the Flutter SDK on your machine.
- Set up an Android/iOS emulator or connect a physical device to test the application.

### Steps:

Clone your repository:
```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

Install project dependencies:

``` bash
flutter pub get
```

Run the app on the emulator or physical device:

``` bash
flutter run
```
