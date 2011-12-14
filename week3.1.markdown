# Accuracy

* Amount of error free frames transmitted relative to the total number of frames
* Ethernet retransmits to correct errors
* BER is bit error rate
	* Analog circuits typically 1 in 100,000
	* Digital circuits error rate
		* Copper - 1 in 1,000,000
		* Fiber - 1 in 100,000,000,000
	* Rule of thumb in design is < one bad frame per 1,000,000 bytes 

# Delay 
## User's POV
* Response time
	* A function of the application and the equipment the application is running on, not just the network
	* Most users expect to see something on the screen in 100 to 200 ms

## Engineer's POV
* Propagation delay
	* A signal travels in a cable at about 2/3 the speed of light in a vacuum
* Transmission delay
	* Time to put digital data onto a transmission line
		* For example, it takes about 5ms to outut a 1,024 byte packet on a 1.544 Mbps T1 line
* Packet switching delay
* Queuing delay

## Delay variation
* The amount of time average delay varies
	* aka jitter
* Voice, video and audio are intolerant of delay variation
* Forget everything we said about maximizing packet sizes
	* Always trade-offs
	* Efficiency for high volume applications vs low and non-varying delay for multimedia

## Response Time
* What users care most about
* Delay frustrates them
* Inconsistent response frustrates them
* Beyond 100ms users notice they are waiting

# Security
* Focus on requirements first
* Detailed security planning later
* Identify network assets
	* including their value and the expected cost associated with losing them due to a security problem
* Analyze security risks

## Assets
* Hardware
* Software
* Applications
* Data
* IP
* Trade secrets
* Rep

## Risks
* Hacked network devices
	* Data can be intercepted, analyzed, altered or deleted
	* User passwords can be compromised
	* Device configurations can be changed
* Recon attacks
* DoS attacks

## Requirements
* Confidentiality
* Integrity
* System and Data Availability
* Physical security
* Control outsider access
* Detect intruder and isolate

# Manageability
* Performance mgmt
* Fault mgmt
* Config mgmt
* Sec mgmt
* Account mgmt

# Usability
* Ease of use with which network users can access the network and services
* Networks should make users' jobs easier
* Some design decisions will have a negative effect on usability
	* Strict sec

# Adaptability
* Avoid incorporating any design elements that would make it hard to implement new technologies in future
* Change can come in the form of new protocols, business practices, fiscal goals, legislation
* Flexible design can adapt to changing traffic patterns and QoS reqs

# Affordability
* Carry max amt of traffic possibly for given cost
* Especially import ant campus networks
* WANs are expected to cost more, but costs can be reduced by proper use of technologies

# Summary
* Continue to use a systematic, top-down approach
* Don't select products until you understand the goals
* Trade-offs are always necessary

# Top-Down Design

## Where are we
* Characterize existing internetwork in terms of
	* infrastructre
		* logical
		* physical
	* Addressing and naming
	* wiring and media
	* architectural and environmnetal constraints
	* health
