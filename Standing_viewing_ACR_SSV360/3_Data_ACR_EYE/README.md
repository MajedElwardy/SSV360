# 3_Data_ACR_EYE

For each participant, the eye tracking data are stored in three different files, i.e., gaze left, gaze right, and gaze combined.

	
## File structure 

The columns contain a sequence of parameters in the following order:

* GAZE_COMBINED

		- #GAZE
		- COMBINED
		- TimeStamp (date)
		- TimeStamp (time)
		- MediaTime
		- OriginX
		- OriginY
		- OriginZ
		- DirectionX
		- DirectionY
		- DirectionZ
		- Validity (true/false)

* GAZE_L

		- #GAZE
		- LEFT
		- TimeStamp (date)
		- TimeStamp (time)
		- MediaTime
		- PupilDiameter
		- PupilDiameterValidity
	
* GAZE_R

		- #GAZE
		- RIGHT
		- TimeStamp (date)
		- TimeStamp (time)
		- MediaTime
		- PupilDiameter
		- PupilDiameterValidity
