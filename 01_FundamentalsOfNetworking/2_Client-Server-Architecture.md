# Client - Server Architecture

### Why?
1. Machines are expensive, applications are complex
2. Seperate the application into two components
3. Expensive workload can be done on the server
4. Clients call servers to perform expensive tasks
5. REmote Procedure call (RPC) was born

### Benefits?
1. Servers have beefy hardware
2. Cleints have commodity hardware
3. Clients can still perform lightweight tasks
4. Clients no longer require dependencies
5. However, we need a communication model

## OSI Model (Open Systems Interconnection Model)
> Any SW engineer should understand this model as long as you keep interacting with networking
### Why OSI Model?
1. Agonstic application
> Apps must not have knowlege of the underlying network medium.  
> Imaginge that there should be app version for each network interface!!!
2. Network equipment management
> without a standard model, upgrading network equipments becomes difficult.

### what is the OSI model?
> 7 layers each describe a specific networking component
1. 