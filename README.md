# Network-and-Service-Operations-Project
To propose a new network architecture for a new Internet startup, Games4All (G4A) unit.

####################Task to be done##################
You have been assigned at proposing a new network architecture for a new Internet startup, Games4All (G4A). The product G4A has is an online game, similar to PUBG, but instead of 100 players, its a 1000 players per map and the map is somewhat larger. As the map is larger and has more players, the solution to handle this is to use virtualized servers, hence they can spin-up and down servers on-demand. However, they will only run one map per server. Each player needs around 256Kbps of up/down speed to the server to have a good gaming experience. 

 

Consider an network architecture that enables the company to support 200 simultaneous games (200*1000 players), while minimizing the number of physical servers. Assume that the server is limited by network capacity, not cpu/memory. Furthermore, assume a geographically distributed environment, where you would have servers in Europe (Paris, Helsinki), Asia (China-Bejing, India-Hyderabad and South Korea (Seol), North America (San Jose, New York). The games would be distributed as 50% europe, 25% Asia and 25% North America. With in each region the load is divided equally (50/50 or 33/33/33 per city). The focus here is between Servers and ISP in the City.  

 

All Cities are connected to the main-site, this to coordinate software updates, player information, etc.The traffic is proportional to the number of players in a city, and is approximately 100Kbytes per game a player participates in. I.e. for every game that starts, each player will require 100Kbytes of data to be downloaded to the server at the City where the game will execute. The average game duration is 30 minutes, the maximum is 60minutes. Hence, a player will download (on average) 100Kbytes every 30 minutes. Consider an network architecture between the Cities and the main-site, so that it can support all the anticipated games. 

 

Please propose a network architecture (draw) that meets both of these two design considerations. From the Map it should be clear to see the general architeture (Routers/Networks/Switches) and what capacities have been selected for the links (at deployment time). Furthermore, point how growth would be handled if more servers would be installed to handle more simulaneous games. 

 

Reason around challenges how to monitor the operations of this large and complex network. 

 

In your report, you need to provide a clear reasoning for you choices, discuss alternatives. Elaborate about the challenges on how to monitor, operate and maintain such a network. How does a router failiure impact the network/game play. Where are the potential single point of failiures? What is the cost of resiliency/redundancy? 

Note: Also added a clarification on why additional 5 gbps data is needed. 

