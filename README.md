# Victim-Detection-in-Disaster-Area-using-UAV-assisted-Human-Voice-Detection-System
Abstract: After natural disasters such landside, earthquake, building collapsed..., survivors are frequently hided by debris and limited
visibility, leading to conventional visual sensors inadequate. This thesis develop an
advanced acoustic sensing system integrated into an UAV platform, designed for real-time
human voice detection in high-noise environments. The hardware architecture uses an
ESP32-S3 (N16R8) microcontroller interfaced with a Sipeed 6+1 MEMS
microphone array for audio acquisition. To reduce the aero-acoustic interference generated
by the UAV’s propeller, wind, rain a real time preprocessing Band Pass filter and post
processing Wiener filtering is applied for adaptive signal enhancement. The processed
acoustic data is classified using a VGGish Convolutional Neural Network (CNN) to
identify human voice signals. System operations, including real-time signal visualization
is centralized via a custom MATLAB Graphical User Interface (GUI). Results illustrates
that the application of Wiener filtering effectively remove UAV noise, allowing the CNN to maintain high detection with validation accuracy of 84.88% and a critical recall rate of 99.2% for human voice detection, operating entirely in real-time with minimal hardware latency.
Keywords: Unmanned Aerial Vehicles (UAV), Acoustic Signal Processing, Wiener
Filtering, Convolutional Neural Networks, Band Pass Filter.
# Due to academic integrity, and intellectual property protection of this graduation thesis, the core MATLAB source code, trained VGGish weights, and custom dataset are hosted in a  private repository. 
