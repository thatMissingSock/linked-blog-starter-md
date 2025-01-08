#### Using natural language, create a set of five functional requirements for the Ven Drive System. Make sure all your requirements are: unambiguous, unitary, complete, verifiable, consistent, modifiable, feasible and succinct. 
1. The Ven drive system shall notify any driver of any offences
2. The Ven drive system shall be accessible
3. The Ven drive system users shall be given a pre-emptive warning
4. The Ven drive system shall send constant reports
5. The Ven drive system can ONLY be activated by first unlocking via the user's iris 
#### Using natural language, create a set of five non-functional requirements for the Ven Drive System. Make sure all your requirements are: unambiguous, unitary, complete, verifiable, consistent, modifiable, feasible and succinct. 
1. The Ven drive system shall NOT allow any user to have more than one account
2. The Ven drive system shall NOT allow any banned user to download the application
3. The Ven drive system shall NOT allow any speed limited vehicles to be operated at a faster speed than normal
4. The Ven drive system shall NOT allow a vehicle that is restricted from a location to access said location
5. The Ven drive system shall NOT allow a ignition-locked vehicle to start
#### Highlight any requirements that need further clarification (e.g. where there is ambiguity). 
- In functional:
	1. It shall let the user know of any offences via the application, on-board vehicle screen and optional email
	2. It should be usable and accessible by all users as the case study states there will be disabled drivers
	3. N/A
	4. The Ven drive system sends constant data in 2 different cycles:
		- 0.2 seconds for speed and location data
		- 1 second for seatbelt, battery and other data
	5. N/A
- In Non-Functional:
	1. N/A
	2. N/A
	3. N/A
	4. N/A
	5. N/A
#### Prioritize your functional requirements using the MoSCoW Method. 
- The order based on MoSCoW is:
	- Must Have:
		- 4
		- 5
	- Should Have:
		- 1
		- 2
	- Could Have:
		- 3
#### Select five of the functional requirements you have developed in (1) and re-frame them in structured (systems requirement) format. Use the following template for your systems requirements

| Function        | The Ven drive system shall notify any driver of any offences                                        |
| --------------- | --------------------------------------------------------------------------------------------------- |
| Description     | Notifies the user through multiple channels that they have just committed an offence whilst driving |
| Inputs          | GPS data; speed data; seatbelt data; traffic light data                                             |
| Source          | Vehicle sensors, phone sensors, satellite sensors and transponders from traffic lights              |
| Outputs         | Notification of offence                                                                             |
| Pre-conditions  | #####I DON'T KNOW WHAT THIS MEANS#####                                                              |
| Post-conditions | #####I DON'T KNOW WHAT THIS MEANS#####                                                              |

| Function        | The Ven drive system shall be accessible                                                                                                                                                |
| --------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Description     | The style, font and navigability of the application used within the Ven drive system should be accessible to accommodate for all disabilities ranging from colour-blindness to dyslexia |
| Inputs          | Change of modes in settings; speed data                                                                                                                                                 |
| Source          | Phone sensors, phone input and vehicle sensors                                                                                                                                          |
| Outputs         | Change in the user interface of the Ven drive application                                                                                                                               |
| Pre-conditions  | #####I DON'T KNOW WHAT THIS MEANS#####                                                                                                                                                  |
| Post-conditions | #####I DON'T KNOW WHAT THIS MEANS#####                                                                                                                                                  |

| Function        | The Ven drive system users shall be given a pre-emptive warning                                                                                                                              |
| --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Description     | The onboard vehicle system should given and audio and visual sound to remind the users within the vehicle to put on their seatbelts, drive the speed limit and adhere to zonage restrictions |
| Inputs          | Iris data; vehicle ignition data                                                                                                                                                             |
| Source          | Phone sensors and vehicle sensors                                                                                                                                                            |
| Outputs         | An audio and visual warning                                                                                                                                                                  |
| Pre-conditions  | #####I DON'T KNOW WHAT THIS MEANS#####                                                                                                                                                       |
| Post-conditions | #####I DON'T KNOW WHAT THIS MEANS#####                                                                                                                                                       |

| Function        | The Ven drive system shall send constant reports                                                                                                 |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| Description     | The Ven drive system shall send constant reports about performance data, seatbelt data and speed data from the onboard vehicle via the Ven drice |
| Inputs          | Vehicle data; phone/app data                                                                                                                     |
| Source          | Vehicle sensors and phone sensors                                                                                                                |
| Outputs         | Logs of data, what has/hasn't been done into the ORACLE servers                                                                                  |
| Pre-conditions  | #####I DON'T KNOW WHAT THIS MEANS#####                                                                                                           |
| Post-conditions | #####I DON'T KNOW WHAT THIS MEANS#####                                                                                                           |

| Function        | The Ven drive system can ONLY be activated by first unlocking via the user's iris                                    |
| --------------- | -------------------------------------------------------------------------------------------------------------------- |
| Description     | The user must first confirm their iris to unlock their vehicle's ignition and the accompanying Ven drive application |
| Inputs          | Phone data                                                                                                           |
| Source          | Phone camera                                                                                                         |
| Outputs         | Ignition unlock notification                                                                                         |
| Pre-conditions  | #####I DON'T KNOW WHAT THIS MEANS#####                                                                               |
| Post-conditions | #####I DON'T KNOW WHAT THIS MEANS#####                                                                               |
