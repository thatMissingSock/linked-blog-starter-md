#### Does the software have to interface with bespoke hardware?
- Yes, it has to link to bespoke vehicles, infrastructure and a bespoke datacentre [[Ven Drive Data Centre]],[[Tesla Models]],[[Layout of the city]]
#### Is the software part of a safety-critical system?
- Yes, it is going to be used to govern the whole cities of Aruba and Meruba. It will be used in conjunction with the law to ensure that the car accident-related injuries rate goes down [[Offences]]
#### Will the system utilise embedded software?
- Yes, the vehicles will have embedded software as well as the traffic lights in the city
#### Will the development of the software involve working with multiple stakeholders across multiple agencies?
- Yes, in the interview the head states that ORACLE, TESLA and GLOBAL SYSTEMS SOLUTIONS will be involved to provide hardware as well as bespoke software
#### Will it be possible to produce testable prototypes of the system in the early stages of development?
- No, as it requires the usage of the infrastructure of the city as well as multiple different bespoke hardware. In the 'offences' section, however, it did state that the datacentre operators had an extremely high accuracy which leads me to believe there may be a simulation?
>"Ven Drive operators have been shown in testing to be 99.9836% reliable in determining correct penalties."
#### Have similar systems already been built elsewhere? Could an existing system, or existing system components be used in the development?
- No, whole systems have not been built elsewhere but parts of the system have:
	- the system imposes a speed limit based on the zone which has been (sort-of) implemented by [EU-member countries](https://www.autotrader.co.uk/content/news/mandatory-speed-limiters-on-eu-cars-from-2024)
	- the system will keep a record of offenses to be used to increase the severity of fines [very much like Finland's day multiplier that also take's into account their income](https://www.theatlantic.com/business/archive/2015/03/finland-home-of-the-103000-speeding-ticket/387484/)
	- the system uses zones to set the speed limit, many map software does this already to *inform* the user like [free to use open street maps](https://www.openstreetmap.org/#map=6/54.91/-3.43)
#### Will it be possible to get user feedback early in the development lifecycle?
- No definitely not, this system will have to be wholly built and pushed before there is *any* user feedback
#### What level of general risk is associated with the system? High? Medium? Low?
- High due to it controlling user's access to vehicles, traffic data, user data, speed control and most importantly the ability to control vehicles remotely
#### What kind of timescale would be needed for development? Long? Medium? Short?
- Long, the head says in the [[Interview]] that it will involve multiple third party stakeholders from different countries, some of will need to come in to implement bespoke hardware
> "
> Well it continues apace. We have the proof of concept and the designs. These were created by Tesla Engineers in Austin and our in-house team here in Venerabia. The next phase is implementation. We have contracted Global Systems Solutions from Vancouver to provide and install the hardware both here and in Mumbai. The software is being developed by PilotSoft Ltd here in Venerabia. Of course, they will be working in conjunction with Tesla. It’s all very complex, but we have a great team of project managers. And fingers crossed it all goes to plan.
> "
#### Are the requirements for the project likely to change during development?
- Yes for a few reasons:
	- logical flaws:
		- the system does not take into account weight put onto seats by items, tesla engineers will note this and will request to change this requirement of either a minute drop-off time or seatbelt updates
	- technical limitations:
		- the sheer amount of data to be transmitted will be bottlenecked by either the device (phones) or network towers changing the frequency of updates for all the data
		- linked to above, the storage costs will keep increasing as time passes as all data is stored changing the requirements in regards to previous offences
		- due to the amount of information being transferred, it will limit the mileage on the vehicles changing the requirements of data being transferred by the vehicle to and from the datacentre
#### On the basis of your answers, decide the following:
##### What process model would be most appropriate to use in development: 
a. **Waterfall model** 
b. ~~Incremental development ~~
c. ~~Iterative ~~
d. ~~Software reuse~~