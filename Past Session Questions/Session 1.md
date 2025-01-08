#### What type of system is being described in the case study (e.g. embedded, real-time system, batch-processing system)?
- embedded (its embedded in the vehicles and the infrastructure of the city [[Zones]]) and real-time (see [[Ven Drive System]], [[Ven Drive Mobile Application]])
#### Is the system business critical, mission critical, safety critical or security critical?
- Safety as without the operation of the system the [[Zones]] won't work leading to people speeding and/or going into zones they should not
- Mission as without the system the vehicles *could* still function but there would be no enforcement of the policies [[Offences]]
#### What is the operational context of the system?
- The system is to be implemented in the new cities of Aruba and Meruba as a vehicle rules/regulation enforcement system
#### Who are the intended users of the system?
- The citizens of Venerabia
#### Who are the stakeholders of the system?
- The citizens of Venerabia (users)
- The government of Venerabia (investors)
- The [[Ven Drive Data Centre]] operators 
#### What would the hardware components of such a system be?
- Bespoke vehicles (see [[Tesla Models]])
- Bespoke infrastructure (see [[Zones]] and [[Layout of the city]])
- A phone, either IOS or Android
- Transponder readers in traffic lights (see [[Offences]]-traffic lights)
- A [[Ven Drive Data Centre]]
#### What would the software components of such a system be?
- Bespoke application ([[Ven Drive Mobile Application]])
- Bespoke software ([[Tesla Models]])
#### What data will the system create and store?
- It will create unique identifiers for each vehicle
- It will create user identities linked to each person's app and number
- It will create a timeline of where the user has been based on GPS data of the vehicles and phones
- It will create a log of what vehicle has passed what traffic light using the transponder
- It will create a log of performance data for each car (every 0.2 second the vehicle is in motion)
- It will create a log of seatbelt data for each car (every second)
- It will create a log of offences
- It will create a map of zones
- See [[Ven Drive System]], [[Zones]], [[Offences]] 
#### What would be the inputs of the system?
- The application [[Ven Drive Mobile Application]]
- The operators [[Ven Drive Data Centre]]
- The vehicles [[Tesla Models]]
- The traffic lights [[Offences]]
- The zones [[Zones]]
#### What would be the outputs of the system?
- Notifications to the application [[Ven Drive Mobile Application]]
- Optional email 
- Visual notifications to the vehicle [[Tesla Models]]
- Audio notifications to the vehicle
- Camera data from the vehicles 
#### What specific challenges would building the system pose for software engineers?
- Input lag as the datacentre is located in Mumbai, India [[Ven Drive Data Centre]]
- Data compression due to the sheer volume of data being transmitted
- Data transmission priority
	- as data is being sent continuously (0.2 second(s) for speed data and 1 second(s) for seatbelt data), the engineers will have to decide what gets sent first in what importance in case there is any lag and/or buffer time
- Interoperability between the apps (IOS/ANDROID), the data centre(ORACLE) and the vehicles(TESLA) (see [[Interview]])
#### What security aspects of the system would need to be considered during development?
- The datacentre operators need to be cyber security trained CONSTANTLY as they have access to private data and **REMOTE ACCESS** to the vehicles [[Ven Drive Data Centre]], [[Offences]]
- The vehicles would need to be constantly updated to the latest firmware to ensure interoperability with both the ORACLE servers and phones
- The Ven drive system should have a constantly updating encryption service since it requires the users to connect their phones to the vehicle's to then be used as a 'beacon' to transmit data to the datacentre through mobile data. Due to it being mobile data, it relies on the local network tower's ISP security to keep the data secure as well as the phone itself to ensure that there is no third party ["tapping"](https://www.avg.com/en/signal/prevent-your-phone-being-tracked#:~:text=Advertisers%20and%20companies%20can%20use,to%20keep%20tabs%20on%20you.) 
#### What safety aspects of the system would need to be considered during development?
- The infrastructure of the city *should* have a built in backup system in case anything goes awry (i.e. microcode to ensure that the traffic lights can operate without need for wireless connection to the Ven drive system) [[Ven Drive System]]
- The vehicles should have some imbedded code after a locked signal is sent to ensure that no banned driver can driver even if the whole system goes down [[Offences]]
- There should be a quicker appeals process for those driving tesla models v3-a and/or v3-b as the limitation of speed on trucks may mean that they cannot move out of the way for other vehicles, especially emergency vehicles. [[Offences]]
#### What reliability issues would need to be considered during development?
- What occurs when the server goes down?
- What occurs if the ISP goes down?
- What occurs when the phone temporarily loses connection to the network tower and/or the vehicle?
- What occurs when their phone dies?
- How does one combat the issue of seatbelts when they have placed a weight ontop of the seat mid journey (i.e. they pick something up and only have a minute due to the parking restrictions so they place it on the seat which is picked up by the vehicle as a person without their seatbelt which bans the user for 1-week. This means the user has only 4 hours to *return* the vehicle back to its home location which can cause a host of issues)
#### What legal, ethical and social factors would act as constraints on the development of the proposed system?
- legal:
	- none since the government has greenlit the program [[Introduction]]
- ethical:
	- authoritarian, can be misused by government agents for personal benefit
	- complete disregard for any personal privacy
		- everything from iris information to data location is constantly sent which can be used for analysis and also to be sold to third part companies
	- how can data be asked for as the onus is on the user to appeal any penalties WITHIN THE TIME LIMIT [[Offences]]
- social:
	- I COULDN'T THINK OF ANY