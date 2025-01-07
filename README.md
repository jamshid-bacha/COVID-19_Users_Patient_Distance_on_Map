# Project Overview #
This project is an advanced contact tracing and monitoring system that integrates location-based services with Google Maps to visualize and manage the spread of COVID-19. By leveraging geolocation data, it provides real-time insights into potential exposure risks for users based on their proximity to confirmed COVID-19 patients or designated "red zones."
The core goal is to enhance public health measures by alerting individuals when they enter high-risk areas, encouraging them to take necessary precautions, such as maintaining social distance or avoiding those zones entirely.


# Features #
Google Maps Integration:
Displays user locations and overlays interactive red zones indicating areas of potential exposure.
Maps patient traces with precise distance measurements to nearby users.

Dynamic Red Circles:
A 10m radius red circle represents the personal exposure zone of a user who may have been in contact with a COVID-19 patient.
A 100m radius red circle indicates a high-risk red zone where confirmed cases have been reported.

Proximity Alert System:
Tracks user movement in real-time.
Alerts the user with a notification if they enter a red zone (100m radius) or come within close proximity (10m radius) to a high-risk individual.

Distance Measurement:
Computes the distance between the user's current location and the red zones or nearby patient traces.
Visualized directly on the map to ensure transparency and informed decision-making.

User-Friendly Visualization:
Intuitive Google Maps interface that dynamically updates as users move.
Red zones and proximity alerts provide a clear indication of risk areas.


Description of Results:
In the screenshot (attached):

Red Circles:
Smaller red circles (10m radius) mark the immediate exposure zones around high-risk individuals.
Larger red circles (100m radius) represent the high-risk "red zones" identified by public health authorities.
Distance Indicators: Shows the measured distance between the user’s location and the nearest high-risk area or individual. This feature helps users understand their risk level and act accordingly.

Proximity Alerts: 
The system triggers an alert whenever the user enters a red zone or comes within a 10m radius of a high-risk individual, reminding them to take necessary precautions like wearing a mask, maintaining distance, or leaving the area.

Practical Use Cases:
Contact Tracing: Assists authorities in tracking individuals who may have come into contact with COVID-19 patients.
Real-Time Alerts: Helps users stay informed about their exposure risks and avoid red zones.
Public Health Support: Enhances community safety by providing actionable location-based data.

![IMG-20210219-WA0022](https://github.com/user-attachments/assets/82175316-1c64-477e-8f17-da78c4b5b6f2)


![IMG-20210719-WA0006](https://github.com/user-attachments/assets/67943d37-0651-442f-8eaa-8e6d5304b243)


![IMG-20210320-WA0002](https://github.com/user-attachments/assets/13bd33c0-8b03-4f7e-948b-ee6dba587ccc)
