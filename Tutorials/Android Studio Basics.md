# Android Studio Basics

## Folder Setup
An Android Studio project has a standardized folder structure that is consistent across all applications. Below is a breakdown of the key folders and their purpose:

### 1. **Java Folder**
The `java` folder contains all the code that defines the app's functionality. This code is responsible for how the user interface (UI) interacts with the user and the device.
- **Purpose**: Handles the logic and behavior of the app.
- **Structure**: There is typically at least one `.java` file associated with each `.xml` layout file.
- **Example**: A `MainActivity.java` file might handle button clicks or user inputs.

### 2. **Res (Resources) Folder**
The `res` folder contains all the UI-related files and resources that your app needs to display content to users.

#### Subfolders in the `res` Directory:
1. **drawable**
   - Contains images and graphic assets used in the app.
   - Supports different image resolutions for various screen sizes and densities.
   - Example: Logos, icons, and background images.

2. **layout**
   - Contains the XML files that define the app's user interface.
   - Each XML file represents a screen or part of a screen.
   - Example: `activity_main.xml` defines the layout for the main screen of the app.

3. **values**
   - Stores reusable resources such as colors, strings, and dimensions.
   - Helps to keep your code clean and maintainable by defining these values in one place.
   - Example:
     ```xml
     <resources>
         <color name="colorPrimary">#6200EE</color>
         <string name="app_name">MyApp</string>
     </resources>
     ```
   - You can reference these values in your layout files or Java code.

## .java vs .xml Files




