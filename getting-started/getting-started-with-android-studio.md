# 💻 Getting Started with Android Studio

### Using non-Android Studio code

1. Export the code from your IDE.
2. Create an Android Studio project, and add your code into it.
3. Build the project.

### Using the sample Android Studio project

1. Clone our [GitHub repository](https://github.com/BlueJays6448/FTCSimulator).&#x20;
2. Make sure that the configuration file points to the full path of the Android Studio project.
3. Build the sample code.
4. Open Webots.

### **Using your own Android Studio project**

1. Download SimulatorSupport.jar from the [release](https://github.com/BlueJays6448/FTCSimulator/releases/tag/0.1).
2. Add SimulatorSupport.jar to the lib folder (usually found in the TeamCode folder).
3.  Edit the FTCController `simulation.properties` file (in the Webots world controllers folder): After `classpath.1=`, add the full directory to the `classes` folder in your Android Studio project. Change `opMode` to the correct Op Mode file.

    Example:

    `classpath.1=/home/gaspard/FTCSimulator/SampleAndroidStudioProject/TeamCode/build/intermediates/javac/debug/classes`

    `opMode=org.ftc6448.opmode.TestAutonomous`

