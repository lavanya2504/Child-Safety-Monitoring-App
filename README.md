# CHILD SAFETY MONITORING APP

This project implements a smart bicycle safety system using Android devices to monitor a child's safety during cycling activities. The system leverages embedded hardware sensors (gyroscope, accelerometer, GPS, microphone, antenna) in conjunction with mobile devices to provide real-time monitoring and alerts to parents.

# Objective of the app

**Real-time Monitoring:**

  1. Continuously monitors GPS, accelerometer, and gyroscope data to detect:
  2. Overspeeding
  3. Fall detection (minimizing false positives)
  4. Boundary crossing (geofencing)
  
**Alerts and Notifications:**
    1. Beep alarm for overspeeding and fall detection on phone A.
    2. Real-time location displayed on Phone B (parent's device) using an image of the local map.
    3. Audible alerts on Phone B for overspeeding and fall detection.
    
**Emergency Response:**
    1. If Cycle falls, Alarm on Phone A with option to disable.
    2. Real-time location sent to Phone B.
    3. Automatic activation of microphone on Phone A if alarm isn't disabled within 5 seconds.
    4. SOS transmission to Phone B with recorded sound via mobile internet.
