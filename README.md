# Realtime_pothole_detection
This project leverages computer vision and AI to detect potholes and road damage in real time using cameras installed on government vehicles. The system tracks, categorizes, and estimates repair costs for each detected pothole, helping streamline road maintenance efforts.


## Features
* Pothole and Damage Detection: <br>
Cameras mounted on government vehicles (e.g., trash collectors, patrol cars) capture video footage of roads. AI models analyze this footage to detect potholes and road damage in real time.
* Pothole Count Between Locations: <br>
The system counts the number of potholes detected between two specific locations (e.g., Point A to Point B), assisting in prioritizing repair efforts on critical routes.
* Location and Database Management:<br>
Each detected pothole is tagged with precise GPS coordinates and stored in a central database. The system logs the time and date of detection for future reference and easy querying.


## Technologies Used
* Computer Vision & AI for real-time pothole detection.
* GPS Integration for accurate geolocation tagging.
* Database for storing and managing pothole detection data.

## Usage
* For Detection: The system continuously analyzes video from cameras mounted on vehicles.
* For Reporting: Detected potholes are automatically uploaded to the web interface with GPS locations.

## Future enhancements
* Automated Reporting to Authorities: Detected damage is reported to the government road department via a web interface. Employees can view the data sorted by date and time, with access to interactive maps showing the damaged locations.
* Real-time Alerts: Improve the notification system to include push notifications for mobile devices.
* Advanced Analytics: Introduce advanced analytics and machine learning for better road condition predictions.
* Mobile App: Develop a mobile app for employees to manage repairs directly from the field.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Requirements 
Refer to requirements.txt to know the versions required to run the application<br>

### `pip install -r requirements.txt` <br>

is the command to install Python packages

