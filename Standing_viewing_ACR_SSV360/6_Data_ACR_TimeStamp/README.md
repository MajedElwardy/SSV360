# 6_Data_ACR_TimeStamp

The timestamps for each event that occurred during the recording of the data are provided for each participant.

	
## File structure 

The columns contain a sequence of parameters in the following order:


	- Type of event
		1- CALIBRATION
		2- EXPERIMENT
		3- VIDEO 
		4- RATING
		5- SURVEY
	- Event status
		1- STARTS
		2- ENDS
	- TimeStamp (date)
	- TimeStamp (time)
	- MediaTime
	
	
* If it is #RATING ENDS the file structure same as the 1_DATA_ACR_MOS
* If it is #VIDEO STARTS, the video details are attached
	