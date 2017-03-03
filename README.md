# Personalized Next-Step Recommendation Framework
This repo contains the sensor code used in

Pardos, Z.A., Tang, S., Davis, D., Le, C.V. (in-press) Enabling Real-Time Adaptivity in MOOCs with a Personalized Next-Step Recommendation Framework. In *Proceedings of the fifth ACM conference on Learning @ Scale*. Cambridge, MA.

## Sensor
The sensor is plugged into the verticals of the edX course and is inputted as raw html. This code:

1. Logs relevant data to mongodb
2. Requests a recommendation from the models
3. Displays the recommendation and updates the server if the student clicks through
