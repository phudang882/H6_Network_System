# H6 Network System (Assignment 2)
In order to build a modern, friendly, and energy-saving University, HCMC University of Technology 
delivered to the Faculty of Computer Science and Engineering the research and deployment of a system 
monitoring activities of students in the buildings and including measurement devices such as temperature, 
humidity, and light in the classrooms in order to reduce energy costs. The system was piloted in building 
H6 of campus 2. For improving the quality of the service of the system operation, the Faculty needs a new 
design and deployment of the network in this building. The group of students studying computer networks.
# Request
The Consultants will provide specific designs that the construction people can rely on it to implement the 
building H6. To convince the investors to choose their solutions, the consultants should also analyze the 
data in order to demonstrate the reasonableness of solutions. Specifically:  
• Network architecture of the system in building H6 and the IP settings for this network.  
• Based on the architecture above, calculate the division of subnets for each target device or divide by 
departments.  
• Capacity needed to ensure the system operates efficiently  
• The system of switches, routers, and cost estimates  
• Line speed internet connections  
#  Hypotheses
• The cameras only transmit data to the server room and their record can only be accessed by the admin 
in the administrative office or users in the server room. Therefore, our team network design must have 
separate VLAN between normal computers, devices with cameras, and admin devices, server room.  
• In floors 6,7 will have 6 computer rooms, each room will have 32 computers.  
• The camera will be implemented in the corridor of each floor.  
• The Administrative office will have 10 computers.  
• Height of each room is 3m.  
• Maximum port when connecting to the switch is 1 GB.  
• Floors 2 to 5 will have only a normal room with 6 small rooms (Height: 3m, Width: 10m, Depth: 5m), 3 
large rooms (Height: 3m, Width: 20m, Depth: 5m). Floor 1 besides two types of rooms above will have 
1 server room (Height: 3m, Width: 10m, Depth: 5m).  
• Floors 6 and 7 will have 4 small rooms (Height: 3m, Width: 10m, Depth: 5m), 2 large rooms (Height: 
3m, Width: 20m, Depth: 5m), 3 computer room (Height: 3m, Width: 20m, Depth: 5m).  
• Each room will have an access point for devices to connect to the WIFI network through a wireless 
connection.  
• Each floor will have a switch for the camera and an access point from each room to connect.  
• Each switch from each floor then will connect to the main switch on floor 1.  
• The main switch then will connect to the final router before going out to the network.  
• Each camera will have a data transfer rate of 1 Mbps.  
• Each computer in the server room will have a data transfer rate of 10 Mbps (to prevent the bandwidth 
to balance the network even though those computers connect to the same switch at the server and 
may have data transfer rate at 100 Mbps)  
