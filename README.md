**AI-Based Suspicious Behavior Detection and Alert System**
Traditional CCTV cameras only record video footage and require humans to continuously monitor multiple screens. This process is time-consuming, inefficient, and prone to human error. To solve this problem, this project introduces an AI-powered surveillance system capable of automatically detecting suspicious human behavior in real time.
The system uses computer vision and deep learning techniques to monitor surveillance video feeds and identify unusual activities such as loitering, aggressive movements, unauthorized access, or abnormal behavior patterns. Once suspicious activity is detected, the system generates alerts and can also trigger IoT-based alarms for faster response.
The project mainly uses YOLO for human detection and LSTM for behavior analysis. YOLO helps in identifying and tracking people from video frames, while LSTM analyzes movement patterns over time to determine whether the behavior is normal or suspicious. Based on the detected activity, the system assigns a suspicion score ranging from 0 to 1.
Different alert levels are generated according to the suspicion score:
Above 0.5 → Alert sent to user
Above 0.7 → Notification sent to nearby authorities/neighbors
Above 0.8 → Emergency alert or alarm activation
This system can be used in homes, shops, apartments, ATMs, parking areas, colleges, and public places to improve security and reduce the need for continuous manual monitoring.
