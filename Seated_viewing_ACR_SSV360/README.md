# Seated_viewing_ACR_SSV360

All data files provided in these folders are in `.csv` format with additional information on the file structure given in each file.

## Participants order

The participants ordered in our paper in the same order as the seated viewing as follows:

```
P001 —> Participant 1
P002 —> Participant 2
P003 —> Participant 3
P004 —> Participant 4
P005 —> Participant 5
```
  
## 1_Data_ACR_MOS

* This folder provides the opinion scores and rating times of the scenes for each participant.
* Four different `.csv` files are associated with each participant containing the opinion scores and rating times of the 30 videos for each scene.  
* Additional information of the videos for each scene are included as follows: Resolution, QP, duration, frame rate (fps), and bitrate (Mbps).
   

## 2_Data_ACR_HMD

* This folder includes the recordings of the head movements of each participant for the entire duration of the HMD exposure.
* The head movements were sampled with a rate of 90 Hz.
* The recorded data is stored in a file including the head positions and rotations for each participant.
* The transformation of the head movements to Euler angles was also performed with Unity during the recording and are provided as yaw, pitch, and roll angles.  
    

## 3_Data_ACR_EYE

* Eye tracking data of each participant has been recorded and sampled with a rate of 120 Hz.
* For each participant, the eye tracking data are stored in three different files, i.e., gaze left, gaze right, and gaze combined.
* The gaze left and gaze right data is given in terms of the pupil dilation and pupil dilation validity (true/false).
* The gaze combined data capturing information for both eyes provides the origin and direction for eye tracking along with its validity.
    
    
## 4_Data_ACR_GSR

* This folder holds the GSR signal recordings using the wireless Shimmer GSR biosensor with the iMotion software which are stored in a file for each participant.
* An GSR file includes the GSR signal in micro-Siemens, GSR quality (valid/not-valid), and heart rate (beats/min.).
    
    
## 5_Data_ACR_SSQ

* The scores given by each participant to the 16 symptoms of the SSQ are given in this folder.
* Two files are associated with each participant, i.e., one for the Pre-SSQ and the other for the Post-SSQ.
    

## 6_Data_ACR_TimeStamp

* The timestamps for each event that occurred during the recording of the data are provided for each participant.
* Timestamps mark the starting and ending time for each event such as the different components of the subjective test including calibration, video, rating, and SSQs.

## Participants_Information.csv

* This file contains demographic information about the participants, i.e., age, gender, occupation, and level of experience with immersive media.



