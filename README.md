Visualisation :- 1 User Journey 2 Physical Structure Multilevel Parking Lot:- Different Floors different kind of spots:- Small , medium, Large and EVs.

Requirement Gathering:- Multiple Floors Each Floor will have Multiple parking spots Parking spots can support multiple type of vehicles A ticket will be generated at the time of entry. A bill be generated at the time of exit. There will be multiple entry / exit gates. Each gate will have one operator. Parking spot will be assigned at the time of entry. Store the details of all the vehicles coming to the parking lot. Payments can be calculated in different ways Payment can be done in multiple ways Partial Payment :- Bill payment can be done using different ways.

Class Diagram Designing Parking Lot:- ID LIST List Status Parking Floor id number List Status Parking Spot id number List Status Status:- Full Empty Gate:- id Number Status Operators GateType Gate Type:-

Vehicle:-
	id
	number
	type
	owner
User:-
	id
	name
	phone
Ticket:-
	id
	number
	entryTime
	Vehicle
	Parking spot
Payment:-
	id
	Mode
	amount
	time
	status
Mode	
