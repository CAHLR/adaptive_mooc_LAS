# Personalized Next-Step Recommendation Framework
This repo contains the sensor code used in "Enabling Real-Time Adaptivity in MOOCs with A Personalized Next-Step Recommendation Framework" paper submitted to Learning at Scale 2017.

## Sensor
The sensor is plugged into the verticals of the edX course and is inputted as raw html. This code:

1. Logs relevant data to mongodb
2. Requests a recommendation from the models
3. Displays the recommendation and updates the server if the student clicks through
