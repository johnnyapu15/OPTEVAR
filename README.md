# OPTEVAR
OPTEVAR: OPTimal EVAcuating Route

# 1. Read nodes, edges from environment json
## It contains values for calculating RSET/ASET - for example area of a room(node)
## Initiate edges weigths with calculating distances between nodes

# 2. Read scenerio parameters - maximum number of people, avg velocity of movement, ...

# 3. Read realtime environment data from json - sensor data(number of people on a room, fire on/off ...)

# 4. Calculate weights of nodes

# 5. Calculate the optimal evacuation route using dijkstra's algorithm
## using networkx.
