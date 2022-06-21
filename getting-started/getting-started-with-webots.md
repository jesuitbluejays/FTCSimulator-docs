# 🎮 Getting Started with Webots

#### Using the provided Webots world

1. Clone our [GitHub repository](https://github.com/BlueJays6448/FTCSimulator).&#x20;
2. Download Webots from their [Github release](https://github.com/cyberbotics/webots/releases/tag/R2021b). The sample world we provide requires Webots 2021b or earlier and is not compatible with newer versions.
3. Rename `simulation.properties.example` to `simulation.properties` and edit the file to add the full path to your Android Studio project.
4. Open Webots and then open the sample world located at `SampleWebotsProject/worlds/gobilda - freight.wbt`.
5. Profit.

#### Using your own Webots world

1. Download Webots from their [GitHub release](https://github.com/cyberbotics/webots/releases/tag/R2021b). The sample world we provide requires Webots 2021b or earlier and is not compatible with newer versions.
2. Download FTCController.jar and SimulatorSupport.jar from the [release](https://github.com/BlueJays6448/FTCSimulator/releases/tag/0.1).
3. Download the sample webots project.
4. Add the FTCController.jar to `SampleWebotsProject/controllers/FTCController`.
5. Rename `simulation.properties.example` to `simulation.properties` and edit the file to add the full path to your Android Studio project.
6. Launch your Webots world.

#### Mapping Motors

Use the properties file to map motors and convert Webots motors to Servos and Continuos Rotation Servos.
