
#HACK CLOUD HACKATHON

#TABLES OF CONTENTS
-Problem statement
-Description
-Features 
-Working of wearable sensor


##PROBLEM STATEMENT
Early detection of epilepsy using bio-inspired algorithms with the help of google cloud.

##DESCRIPTION: 
We are creating a wearable sensor that can detect epileptic signals before 10 mins of the actual attack happens.
This detects epileptic attack in the preictal state and sends an emergency message to the nearby hospital and family members. 

##FEATURES
The google cloud features we have used are 
1.Google cloud storage - to help with latency problem and to securely store EEG signals.
2.Google cloud Dataflow - to prepare the data for analysis, I'd leverage Google Cloud Dataflow for real-time preprocessing. This ensures that the incoming EEG data is cleaned, transformed, and made suitable for further analysis. 
3.Google cloud IoT - integrate IoT devices through Google Cloud IoT to collect data directly from patients' wearable EEG monitors. 

##WORKING OF WEARABLE SENSOR
1. Research and Understanding:
We initiated our project by conducting thorough research on epilepsy, its symptoms, and the specific signals associated with preictal states. Collaborating with medical professionals was essential to gain the necessary insights.

2. Sensor Selection:
After careful consideration, we selected EEG (Electroencephalogram) sensors as the primary means of monitoring brain activity, as they are instrumental in detecting epilepsy-related signals. Additionally, we incorporated accelerometers and heart rate monitors to gather supplementary data.

3. Data Acquisition:
To collect data from our sensors, we designed custom circuitry and selected microcontrollers to ensure accurate data sampling.

4. Signal Processing:
Implementing advanced signal processing algorithms, we preprocess the collected data, extract relevant features, and employ machine learning techniques for preictal signal detection. Google Cloud's machine learning services play a vital role in this phase.

5. Data Storage and Communication:
Our system efficiently stores and communicates data with a Google Cloud platform, ensuring data privacy and integrity through secure protocols.

6. Cloud Platform Setup:
We set up a Google Cloud environment, utilising services such as Cloud Storage, Cloud Functions, and Cloud Messaging for effective data management and alerting.

7. Alerting System:
An integral component of our solution is an alerting system that sends emergency messages to nearby hospitals and family members once epileptic signals are detected. This system integrates with SMS, email, and push notification services.

8. User Interface:
For user-friendliness, we created an intuitive interface for the wearable device, enabling the wearer to receive alerts and information about detected signals.

9. Power Management:
Our design includes an efficient power management system to prolong battery life and minimize the need for frequent recharging.

10. Testing and Validation:
Rigorous testing, including real-world trials with epilepsy patients, ensures the accuracy of our detection and minimizes false alarms. Collaboration with medical professionals is essential for clinical validation.

11. Regulatory Compliance:
We are committed to adhering to all relevant medical device regulations and standards, including FDA requirements if applicable.

12. Privacy and Security:
Robust privacy and security measures safeguard sensitive patient data stored on Google Cloud.

13. Clinical Trials:
As part of our commitment to safety and effectiveness, we are planning to conduct clinical trials and studies to validate our wearable sensor's performance.

14. Deployment and Scaling:
Once validated, our wearable sensor will be ready for deployment in hospitals and for personal use, with scalability options in place as needed.

15. Continuous Improvement:
Ongoing enhancements will be made based on user feedback and advancements in technology and medical research.

