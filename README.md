# Photo Frame App

## Description
The Photo Frame App is a simple iOS application that allows users to display their photos in a customizable frame. Users can select photos from their library and apply different frame styles and colors to enhance their viewing experience.

## Features
- Select photos from the photo library
- Apply different frame styles
- Customize frame colors
- Save framed photos to the photo library
- Simple and intuitive user interface

## Screenshots
![Screenshot1](path_to_screenshot1.png)
![Screenshot2](path_to_screenshot2.png)

## Requirements
- iOS 14.0+
- Xcode 12.0+
- Swift 5.0+

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/PhotoFrameApp.git
    ```
2. Open the project in Xcode:
    ```sh
    cd PhotoFrameApp
    open PhotoFrameApp.xcodeproj
    ```
3. Build and run the project on your simulator or device.

## Usage
1. Open the app on your iOS device.
2. Tap on the "Select Photo" button to choose a photo from your library.
3. Choose a frame style from the available options.
4. Customize the frame color if desired.
5. Save the framed photo back to your library or share it with friends.

## Code Overview
### Main Files
- `ViewController.swift`: Contains the main logic for photo selection, frame styling, and customization.
- `Main.storyboard`: Defines the UI layout of the app.
- `PhotoFrame.swift`: A custom view class for rendering the photo with the selected frame.

### Key Functions
- `selectPhoto()`: Opens the photo library for the user to select a photo.
- `applyFrameStyle(style: FrameStyle)`: Applies the chosen frame style to the selected photo.
- `customizeFrameColor(color: UIColor)`: Changes the color of the frame.
- `savePhoto()`: Saves the framed photo to the photo library.

## Contributing
1. Fork the repository.
2. Create your feature branch:
    ```sh
    git checkout -b feature/AmazingFeature
    ```
3. Commit your changes:
    ```sh
    git commit -m 'Add some AmazingFeature'
    ```
4. Push to the branch:
    ```sh
    git push origin feature/AmazingFeature
    ```
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements
- [Unsplash](https://unsplash.com) for providing free images used in the app.
- [Hacking with Swift](https://www.hackingwithswift.com) for amazing Swift tutorials.

## Contact
- Your Name - [your.email@example.com](mailto:your.email@example.com)
- Project Link: [https://github.com/yourusername/PhotoFrameApp](https://github.com/yourusername/PhotoFrameApp)
