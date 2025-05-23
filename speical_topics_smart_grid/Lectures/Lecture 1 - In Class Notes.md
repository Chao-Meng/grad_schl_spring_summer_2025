### Traditional Power Generation
- Movement of electrons are generated when the potential at one end is diff from the potential at another end. Generators produce that potential difference. ✅
- Modifications need to be made over time. Power needs to be delivered and cannot be halted for changes/modifications.  ✅
- Majority of generation is converting mechanical to electrical power. ✅
- A small percentage is done via renewable. Eg. Solar uses sunlight to produce the potential difference for power generation. Hydro. Wind.✅
- Mechanical can come from water falling where potential energy is converted to electrical power as the generator rotates. Thermal generates steam. Nuclear is similar where through heat power is generated. All of these are mechanical power generation. ✅
- Always generating three phase. Balanced three phase positive sequence generated by generators.✅
- Renewables always produce DC power. It's not simple to switch to it though because the whole system is built in 3 Phase AC systems. So it's not easy to switch. ✅
- Why three phases? Why not single or two phase? Three phase induction motor was the most efficient, which is why it is the most desired. Generator creates balanced three phased power. Positive sequence ABC sequence. It can go out of phase due to other reasons but generator will always generate balanced three phase. ✅
- Generators generally produce 13.8 to 20kv range which is not great for transmission. There would be a lot of loss. We need to raise the voltage up to reduce losses. Using winding on the coils we increase the voltage. eg 20kv would lose a lot more compared to 200kv to reduce losses.✅
- Voltage gets transformed to a higher voltage level then it gets converted back to a lower level at the consumer end.✅
- One end might be three phase 500 kv system transformer but on the other end, distribution level, we may use 230 kV system transformer.✅
- Three phase 25 kv to 416 volt distribution transformer has three components for 3 phase. Each transformer is single phase, so 3 for three phases. **(maybe look this up later to understand better)**✅
- Higher voltage less losses and easier it is to transmit over long distances. It is stepped up then stepped down.✅
- 60kv to 765kv in North America. 1000kv is in service in Russia.✅
- DC is good for synchronization. Can't be done with AC since they run differently so it has to be connected with DC lines.✅
- Each stage of a line is bundled in either 1, 2, 4 conductors. It is called a bulk transmission system which transports bulk power over long distances. ✅
	- It is networked in a loop or meshed system for reliability.
	- Loss of one component will not be catastrophic.
- Transmission interconnections between neighboring companies. ✅
	- Reinforce each other for reliability.
	- Enable the trading of bulk power.
- Bulk power users (eg. industrial) may connect at transmission voltage levels.✅
- Western, eastern, and Texas are not synchronized. Power can only be transmitted via DC transmission lines between these three interconnection. NERC Interconnections.
- Urban transmission systems are high voltage cables. Not overhead lines. ✅
- Stepping down to distribution: 69kv is the voltage coming in, and going out will be either 20kv or 13.8 kv which go out on several distribution feeds. Then it will be brought down to 16 volts before usage. ✅

### Power System Operation
- Wicket gate operating mechanism: In real time power produced has to match the load. All the time. If it doesn't match, the consequences could be detrimental in the system. Both active and reactive power have to match all the time, including losses. All losses have to be accounted for. x should always = y and z for both active and reactive. If they don't match things have to be done to make them match otherwise problems will occur. Measurements and values have to be known at every point in the power system. Then it has to be controlled at every point to re-synchronize. ✅
- With a hydraulic system power can be controlled using a wicket gate using a servo motor (how much water is coming in). Water inlet gates and are adjusted by the servo connection levers. This is for active power. ✅
- The reactive power controls the voltage on the system. In order to remain synchronized, voltage and frequency must be maintained. Voltage is with reactive power. Frequency is managed by active power. ✅
- Automatic voltage regulators are used to maintain voltage for reactive power. It controls the excitation to the generator, which controls the voltage. Governors control the mechanical power.  ✅
- When connected to the system, one generator can't change many things since the system regulates a lot. So when it is not connected to a large system, governors control the speed, and avr controls the voltage. Once connected to the system, the little generator has no say since the large system is much larger which will control the speed and voltage. Therefore, genrator and avr can instead adjust the power and something else (check slide) instead. These have a limit though. Each generator has different capabilities and different devices are used to measure these limits. If generators go beyond these limits, generators are kicked out and the result is a blackout. ✅
- If real power, the load, is less than the generated power, the frequency will go up (Gens will start speeding up). Other way around if load is more generation is less the frequency will go down. Turbines are not designed within a range so it can't operate at these higher or lower frequencies. ✅
- Balance of frequency is achieved by monitoring daily and seasonal load fluctuations. The system forecasts loads 1h, 2h, some duration away. Then the load will be predicted and set ahead of time to create a proper balance. This is called load forecasting. ✅
- Generators and sometimes capacitors control reactive power in a system (voltage). AVR is used to match the reactive power. ✅
- If you are short of reactive power, some companies might provide ancillary services, which connects to the system as needed to provide the needed power. This was the old system. These days power electronics are used but with these devices there is low inertial. 
- If real power load is less than generation, the generators will speed up. Because load is less.  ✅
	- Real power: Controls the frequency which is indirectly related to the speed. In NA it maintains a freq of 60 Hz. When load and gen match freq is 60hz.
		- Speed goes down. Frequency goes down as a result.
			- Load: more
			- Generation: less
		- Speed goes up. Frequency goes up as a result.
			- Load: less
			- Generation: more
	- Reactive power: Controls the voltage. If load and generation are perfectly matched, the  votlage is maintained. Generators produce constant voltage.
		- Voltage is not enough. Need to generate more reactive power using synchronous condensers or use capacitors (they generate reactive power).
			- Load: more
			- Generation: less
		- Voltage is too high.
			- Load: less
			- Generation: more
### Smart Grid
- Built over time, not all at once. It's evolutionary. 
	- If you go to a substation you'll find technology from 1950 to 2025.
- How is it defined?
	- It is an advanced electrical grid. It's an intelligent system which uses digital communication and advanced technologies, which is the end goal (ambition) to mange the system much more efficiently and reliable way (fundamentals don't change. just the technologies used to make it more efficient). Some parts of it exist, but some don't.  
	- The goal is to better sense, monitor, and control/respond in real time, what is already being managed (frequency and voltage mgmt) going back to the fundamentals.
	- It has become a data driven energy network in a way including data analytics etc.
- What are the core components of a smart grid? (This is the end goal. Not happening everywhere but things are moving in this direction.)
	- Smart meters are installed in homes and business to monitor and record usage in real time.
		- Utility companies have no idea what's going on until the meter reading comes in. It is now done in real time.
	- Sensors and controls detect faults and enable automation. This means it will self diagnose the problems and figure out solutions for it.
	- Communication infrastructure. The system is huge so communication is crucial. There are strict requirements in terms of communication, latency, etc.
	- Control centers use data to balance supply and demand.
- What are the functionalities and benefits?
	- Responsiveness: The smart grid will be able to respond very quickly to any fluctuations in the system. Outages, changes in voltage, etc. The goal is to act proactively in real time. The traditional system lacks real-time data which makes it very difficult to be proactive.
	- Two way communication between utility and consumer to optimize the energy distribution. 
	- Eg. the utility company might provide incentives to consumers for using less energy which is communicated through some smart monitoring system. This way the company can distribute that saved power elsewhere.
	- Supports integration of renewable sources like solar wind etc.
- Smart grid is a modern approach.
	- Smart grid will be decentralized and generation will happen throughout the system. Generation could even happen at peoples houses via solar etc. which feeds back into the system.
- Traditional grid vs smart grid
	- Centralized meaning large systems. If a large system goes down, big portions of the grid are affected.
	- Distributed meaning smaller systems that are more flexible and easier to manage/reliable. 
- Challenges for the current power systems
	- Aging grid infracture, increased demand strains, extreme weather and cyberattacks.
	- Not enough power in the grid available in some areas due to the advancement in technologies. Eg. Too many Ev's can make it difficult to charge some in specific areas.
- Climate change and decarbonization is also another incentive to switch to smart grid
	- Power sector is one of the largest greenhouse gas emitters. They need to decarbonize but there are challenges. Can't be switched overnight.
	- Global goals demand cleaner energy and lower emissions. Canada has a goal of being carbon neutral by around 2035 or something close. For that to happen, smart grid is crucial.
- Enabling energy transition
	- Smart monitoring and data is all there right now. Consumers are switching to smart monitoring. It is not being utilized fully because we don't have the ideal smart grid yet.
	- In control centers people/operators have set rules for what needs to be done to adjust voltage, load, and routing. The goal with smart grid is to automate all of this. 
- Self healing capabilities
	- Smart grid concept was originally started by protection and automation people. It has been around for a long while, it just got labelled as smart grid for political reasons.
	- If one line is lost, rerouting will be done automatically very quickly. Right now it is done manually by operators who are highly skilled and know how to manage the changes.
- Consumer participation
	- Summer time, everyone turns on their AC and so on so power generators tend to hit their peak. The voltage level (reactive power) goes down as a result since the demand/load is higher so generation is not sufficient. 
	- Consumers want lower cost and reliable power.
	- Automated processes reduce cost for utilities because there can be less manual adjustments, thus less extremely skilled workers need to be paid for work that can be automated more reliably.
	- The operator needs to know how much power is being fed into the system in order to realize the benefits and compensate the end user accordingly.
- What is AMI & key benefits (one technology)
	- Almost every part of the world has some form of AMI, advanced metering infrastructure.
	- This is basically measuring your power at various intervals at businesses, homes etc. Then it communicates this information back at the control center, so that they know exactly how much power is being consumed in the area.
	- The two way communication part is not being used much even though it has the capability. This is the end goal so that we can monitor the load being used on the system and enabling two way communication to benefit both consumers and utility companies.
	- Automatically shifts consumer behavior and detects electricity theft and illegal activities. Eg. marajuana growups when energy consumption goes up suddenly in some area.
- Consumer empowerment thought AIM
	- Informs energy saving behavior so that users can decide when and how they want to consume power as it becomes more/less avilable.
- Role of sensors in smart grid (another technology)
	- Aids in the control of voltage and frequency.
	- Detects vibrations in the line, voltage, current, temperature, etc.
	- End goal is to have everything sensed in the power system.
	- Enable predictive maintenance well in advance. Eg. predicting maintenance required a year in advance.
		- Predicting motor maintenance could have sensors for temperature, vibrations, motion, etc. to predict what will go wrong with the generator.
		- For transformers there are infrared sensors that can measure hotspots. Image processing techniques could be used by smart monitoring systems to predict outcomes in advance.
	- Old sensors didn't really provide data. It measured and took action.
- Understand phasor measurement units PMUS (another technology)
	- Measure voltage and phasors to time synchronize using GPS systems. Back in the day time signals were synchronized using fiber optics, but now we can use GPS systems for it.
	- In the old system we only know the voltage magnitudes, but in this system we know the phase angle and voltages. This allows dynamics in real time for situational awareness.
	- Wide area monitoring is possible and quick response to disturbances.
- SCADA is supervisory control and data acquisition. (another technology)
	- Some of it is in place but not in full capability. Eg. opening and closing distribution lines by opening and closing switches but it doesn't happen automatically.
	- RTUs are remote terminal units which are being replaced by PMUs in the newer systems.
	- Some of the smart metering data is starting to go to SCADA as well.
	- Integrates AMI, PMU, DER for smart opererations. Eg. even electic vehiacle charging data is being sent to the system, to determine what level of charging each ev charging station can have. So cars will charge faster or slower depending on how many cars are drawing power in a certain area.
- Distributed energy resources (DER)
	- Wind turbines, solar panels, micro grids. 
	- All of these will be integrated in smart grid.
- Demand response technologies.
	- Empowers the consumer to change their electricity usage depending on the demands on the system. eg. if consumers can see the real time price they can adjust their behavior to shift energy consuming activities to times where costs are less which automatically stabilizes the grid.
- Communication Networks
	- At one point utilities had more fiberoptic lines than telephone companies.
	- IEC618w/e uses IP-based protocols. At one point every system will have IP for optimal communication.
- Data management and analytics
	- Big data and data analytic techniques
	- Load forecasting
	- Forecasting power generation from wind turbines and solar (by predicting weather conditions etc.)
	- Bits and pieces are already in the system. Just needs to be utilized.
- Energy storage systems
	- Battery storage is crucial for when not enough power is generated from solar, wind etc.
- Cybersecurity
	- Control systems can be hacked.
	- Computer systems controlling smart grid can be hacked.
- Issues
	- Can't shut the power system off, but it needs to be improved. So it would need to happen in stages.
	- Implementation costs are very high.
	- Technology has to be developed and must be proven via trial bases. That can take years to go from proof of concept to deployment stage. Then you have to start with the important substation, meters, and communication system upgrades before moving to other areas. 
	- New technologies need to be able to work with existing technologies.
	- Initially you have to invest a lot of money but it can be recovered over a long time.
	- Interoperability issues.
		- One tech uses one standard but another uses another standard. Then its difficult to make them operate together. There is no common standard so two systems may not be able to communicate together though they do the same thing. This makes it very challenging to implement new technologies.
		- There is a big push towards coming up with a universal standard for interoperability.
		- Risk of vendor lock in is when your stuck with a particular manufacturer because their devices communicated with only other devices made by them. So another vendors device would not be compatible.
	- Consumer awareness and participation
		- When smart meters first came about people were against them because they thought costs would go high and they wouldn't have benefits. 
- Smart cities
	- Smart gird is a part of these cities that have been developed in certain areas.
	- Can only be created if we have a smart grid. 
	- Made to improve urbal life. eg. smart street lights.
- Rural electrification
	- Micro grids are being setup for these rural areas because there might only be one line going there etc. So when one line goes out power goes out to that area. So a micro grid using wind, solar etc can power the area and can also be integrated into the smart grid for overall power distribution.
- Power plant monitoring
	- person doesn't need to be at a power plant. Can be controlled remotely, enhancing safety, making maintenance predictable, etc.
	- Ancillary service (service that provides power back to the grid) where EV's can supply power back to the grid rather than charge. (vehiacle to grid technology.)
- Case Study US smart grid pilot project
	- Pilot projects are going on throughtou the world.
		- Eg. ontario funds various projects as proof of concept which can be expanded
		- Trying to show it results in efficiency and all benefits smartgrid can bring
- Blockchain in Energy Trading (Another tech in smart grid area)
	- More for energy trading so that energy trading platforms can be created.
	- Reduces transition costs and intermediaries
- 5G and Real-Time control
	- Improves communication speeds
- Global trends and dev
	- There needs to be more international cooperation on smart grid standards.
	- There needs to be more r and d
	- More (everything else on list)
- Smart Grid and Sustainable Development Goals (SDGs)
	- Codes for goals setup by UN which contributes to the development of Smart Grid.