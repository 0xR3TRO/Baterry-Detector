## Project Description

### Goal:

The "Battery Detector" project aims to provide users with an interactive widget to detect the charging status of their device and display the battery level in a user-friendly and clear manner in a web browser. The application allows users to monitor their device's battery level in real-time, which can be useful in various contexts such as energy management, device performance optimization, and educational applications.

### Features Description:

- **Charging Status Detection:** Users can check if the device is connected to a charger.
- **Battery Level Display:** The widget shows the current battery level as a percentage.
- **Notifications:** Users can receive notifications about low battery levels or when the battery is fully charged.
- **Customization:** Ability to customize the appearance of the widget to match the user's website style.

## Requirements Analysis:

### Functional Requirements:

- **Charging Status Detection:** The application detects whether the device is connected to a power source.
- **Battery Level Display:** The widget displays the current battery level as a percentage.
- **Notifications:** The user receives notifications about low or full battery levels.
- **Customization:** The user can customize the widget's appearance, changing colors, size, and other style elements.

### Non-functional Requirements:

- **Accuracy of Data:** Battery level and charging status must be accurately read and displayed.
- **Response Speed:** The widget should respond to battery status changes in real-time.
- **User Interface:** An intuitive and aesthetic interface that is easy to integrate into websites.

## Interface Design:

### Sketches/Visualizations of the Interface:

- _Home Page:_ A panel with a widget displaying the battery level and charging status.
- _Customization Window:_ Options for changing the widget's appearance (colors, size, font).
- _Notifications:_ Icons or dialog boxes informing about low or full battery levels.

### Site Map:

- _Home Page_
  - Main widget panel
  - Customization options
- _Customization Window_
  - Change colors
  - Change size
  - Notification settings
- _Notifications_
  - Low battery
  - Full battery

## System Architecture:

### Data Structure Description:

The application stores data related to battery status and user preferences, including:

- **Battery Level:** Information about the current battery percentage.
- **Charging Status:** Information about whether the device is charging.
- **User Preferences:** Data about widget customization (colors, size, notification settings).

### Architecture Diagrams:

The architecture is based on the MVC (Model-View-Controller) model, where:

- **Model:** Handles the logic for reading battery status and managing data.
- **View:** Displays the user interface, showing battery status and allowing customization.
- **Controller:** Manages communication between the model and the view.

## Implementation:

### Technology Description:

- **Frontend:** HTML, CSS, JavaScript (React.js).
- **Backend:** Node.js (for handling notifications, if needed).
- **Database:** Local storage of the browser (localStorage) to store user preferences.

### Code Structure:

- _Directories/Files:_ Separate files for battery status reading logic, interface, and data management.
- _Coding Styles:_ Use of modularity, readability, and comments in the code.

## Testing:

### Test Plan:

- **Unit Tests:** Check the correctness of battery status reading and widget customization functions.
- **Integration Tests:** Ensure that components work together correctly.
- **User Interface Tests:** Test user interaction on different devices and browsers.
- **Performance Tests:** Evaluate the performance of battery status reading and display in real-time.

### Testing Procedures:

- Develop a set of test cases for each function of the application.
- Establish procedures for reporting and fixing found bugs.

## Deployment and Maintenance:

### Deployment Plan:

- **Deployment Stages:** Testing, fixes, publication on platforms accessible to users (e.g., GitHub).
- **Deadlines:** Set dates for planned deployment stages.

### Maintenance Procedures:

- **Technical Support:** Establish communication channels with users to report issues.
- **Updates:** Plan regular updates based on needs and user feedback.

## Schedule:

### Project Plan:

- **Implementation Stages:** Divide tasks into specific phases (e.g., implementing charging status detection, interface, testing).
- **Deadlines:** Determine the time required for each stage.

## Budget:

### Estimated Costs:

- **Application Development:** Based on hourly work or the development team.
- **Maintenance Costs:** Servers, possible external service fees, technical support.

---

[Polish](<Documents/README(PL).md>)
