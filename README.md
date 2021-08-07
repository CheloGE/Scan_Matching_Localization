# Scan Matching Localization

The following project implements ICP to localize a vehicle throughout a given map.

The localization is based on LiDAR measurements as shown below:

![](./figures/image1.png)

The goal of the project is to localize the vehicle continuesly during 170 meters without getting a max error higher than 1.2 [m]. The speed must be an intermedium velocity which means 3 up arrows in our CARLA interface.

The final result is shown below:

![](./figures/final_result.png)