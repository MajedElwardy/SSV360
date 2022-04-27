# 4_Data_ACR_GSR

This folder holds the GSR signal recordings using the wireless Shimmer GSR biosensor with the iMotion software.

	
## File structure 

The columns contain a sequence of parameters in the following order:

	- #GSR GSR
	- TimeStamp (date)
	- TimeStamp (time)
	- MediaTime
	- Timestamp RAW (no units)
	- Timestamp CAL (mSecs)
	- System Timestamp CAL (mSecs)
	- VSenseBatt RAW (no units)
	- VSenseBatt CAL (mVolts)
	- Internal ADC A13 PPG RAW (no units)
	- Internal ADC A13 PPG CAL (mVolts)
	- GSR RAW (no units)
	- GSR CAL (kOhms)
	- Heart Rate PPG  (Beats/min)
	- IBI PPG  (mSecs)
	- GSR CAL (µSiemens)
	- Packet reception rate RAW (no units)
	- GSR Quality


## GSR recording parameters

* Devices: GSR (ShimmerDevice)
* Algorithm: Peak detection
	
	* Sliding window phasic filter
		- Phasic data averaging window: 	8000 (ms)
		- Low pass filter cutoff:			5       (Hz)
	
	* Signal peak detector
		- Peak onset/start threshold: 		0.01   (µSiemens)
		- Peak offset/stop threshold:		0        (µSiemens)
		- Signal jump threshold:			0.1     (µSiemens)
		- Peak amplitude threshold:		0.005 (Delta value)
	
	* Binning procedure that adapts to sample timestamps
		- Bin window size: 				5000  (ms)
		- Bin window overlap:				1000  (ms)