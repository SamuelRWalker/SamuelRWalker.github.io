---
layout: page
title: Automated Lab Feedback System - IN PROGRESS
---

## Overview
The Automated Lab Feedback System is a software tool designed to streamline lab testing and provide automated feedback for students. This system integrates hardware and software components, allowing students to run experiments, gather data, and receive immediate feedback based on pre-programmed criteria. It is being developed for **Professor Blum**, with a focus on ADC parameter testing, UI modularity, and integration with external devices like the AD2 Wavegen and ESP32.

## Key Features

### 1. Modular UI Design
The user interface (UI) is structured for ease of use and modularity:
- **Top Navigation Bar**: Tabs for "Home" and "Labs" are left-justified, while "Profile" and "Settings" are right-justified.
- **Labs Section**: Syncs with a GitHub repository to pull all lab assignments. Each lab is listed with a description, and clicking on a lab displays all sub-parts required for testing.
- **Lab Details**: Within a selected lab, users can view descriptions and interact with different experiments. Each experiment has a 'Verify/Test' button to run the test, and a progress tracking system helps students monitor which tasks are complete.

### 2. Automated Testing with AD2 and ESP32
One of the system's core capabilities is automated testing using devices such as the AD2 Wavegen and ESP32 microcontroller. The AD2 is used for generating waveforms, and the ESP32 is programmed to collect ADC data. The software provides automated feedback on key ADC parameters, including:
- **Sample Rate**
- **Bit Level**
- **Noise and Accuracy**
- **Linearity and Range**
  
The system will control both the AD2 and ESP32 to test and log data, which is then analyzed and presented to students.

### 3. User Authentication and Profiles
- **Login Screen**: Offers "Create Account," "Sign In," and "Sign In as Guest" options. Users can toggle automatic login during account creation or sign-in, with locally stored credentials for secure and efficient access.
- **Account Creation**: New users can input a username and password, stored locally, and accessible through the sign-in system.
- **Profile Management**: Users can view and manage their account details, and modify settings as needed.

### 4. Consistent Screen Size
The system automatically adjusts the window size to be consistent across all screens, providing a seamless user experience. Each UI screen is sized according to the user's screen resolution:
- **Width**: Half of the screen's width.
- **Height**: 3/4 of the screen's height.
The windows are centered to maintain a professional and uniform appearance.

### 5. Lab Progress Tracking
Each lab and experiment within the system includes progress tracking:
- **Incompleted vs. Completed Labs**: Labs and experiments have status icons (incomplete and complete). An incomplete icon is displayed to the right of each lab and experiment.
- **Automatic Updates**: When a student completes an experiment (by running the test), the icon switches from incomplete to complete. When all experiments in a lab are marked as complete, the lab’s status icon changes as well.

### 6. Visual Design and Custom Icons
The design includes icons for navigating the labs and settings:
- **Labs Icon**: A list icon without text, larger than the button itself.
- **Settings Icon**: A gear icon, similarly larger than the button.

For better aesthetics, the experiment titles are clickable, expanding to show details, while an up/down arrow (assets provided) lets the user toggle the view. Each experiment has a 'Verify/Test' button next to its title for easy access to test functions.

### 7. Responsive Testing Environment
Currently, the system is in the testing phase, and it does not yet include the device accessibility check for AD2/AD3 or the full circuit implementation. These features will be added after the UI and core feedback system are fully functional.

## Future Plans
As development progresses, there are plans to extend the system to include more complex feedback mechanisms and integrate additional devices for more advanced lab experiments. Additional features under consideration include:
- **Expanded Device Support**: Inclusion of voltmeter and impedance tools in the automated feedback system.
- **Mobile Compatibility**: Adapting the UI for use on mobile devices for easier access during labs.
- **Performance Metrics**: Logging additional performance metrics for each test to provide students with a deeper analysis of their results.

## Conclusion
This **Automated Lab Feedback System** is an ambitious project aimed at simplifying the lab testing process and providing immediate feedback for students, helping them understand their experiment results in real time. With ongoing development, this system will become a valuable tool for students and instructors alike, ensuring a more streamlined and educational lab experience.
