# vehicle-apps-images
Repository to store container images created for Vehicle Applications. \
**Usage**: in Eclipse Velocitas (VSCode DevContainer) and Eclipse Leda

This repository contains the following container packages:
* Seat Adjuster Example application provided by Eclipse Velocitas
* Speed Limiter Application as a demonstrator.
* Mock Service provided by Eclipse KUKSA, to trigger actuators and sensors in the SDV using a configuration file.

Note: 
1. Open Velocitas Python project template in VSCode DevContainer. 
2. Use the Dockerfile in Eclipse Velocitas /app directory.
3. Generate vehicle model.
4. Copy vehicle_model directory manually from root dir to /app dir.
5. Change directory to /app
6. Run in devcontainer CLI: **docker build -t <repository_tag_name> .**
