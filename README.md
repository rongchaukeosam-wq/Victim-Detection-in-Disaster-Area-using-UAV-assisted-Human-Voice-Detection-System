# Victim-Detection-in-Disaster-Area-using-UAV-assisted-Human-Voice-Detection-System
# Graduation thesis: UAV-assisted Human Voice detection system for disasters areas (Landside, earthquake, building collapsed..)using MATLAB, VGGish model, and Microphone mounted on UAV.
Abstract: After natural disasters such, survivors are frequently hided by debris and limited
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
that the application of Wiener filtering effectively improves the Signal-to-Noise Ratio
(SNR), allowing the CNN to maintain high detection accuracy despite the operational noise
of the UAV. This research aims to contribute to the enhancement of multi-modal sensing
capabilities in modern Search and Rescue (SAR) operations.
Keywords: Unmanned Aerial Vehicles (UAV), Acoustic Signal Processing, Wiener
Filtering, Convolutional Neural Networks, Search and Rescue.
# Due to academic integrity, and intellectual property protection of this graduation thesis, the core MATLAB source code, trained VGGish weights, and custom disaster-ambient dataset are hosted in a  private repository. 
