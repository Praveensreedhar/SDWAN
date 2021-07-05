## CISCO SDWAN Components

### V-Bond : ZTP  and orchastration PLane
    1.    Used for Device on boarding
    2.    Orchestrates connectivity b/w Management, Control and Data plane
    3.    First Point of authentication.
    4.    All Other components used to know the vBond IP or DNS information.connect
    5.    Authorizes all control connections
    6.    Distribute list of all vSmart to all vEdges.
    
### vEdge : Dataplane
    1	  Wan edge routers.
    2	  Provides secure data plane with remote vEdge routers
    3	  Establishes secure control plane with vSmart controllers(OMP)
    4	  Exports performance statistics
    5	  Leverages traditional routing protocols like ospf BGP and VRRP
    6	  Physical or vrtual form factor
    
### vSmart : The control Plane
    1    Centralized brain of teh solution.
    2	 Establishes OMP peering with all vEdges.
    3	 Implement control plane policies, such as service chaing, traffic engineering and per VPN topology
    4	 Distributes connectivity information between vEdges.
    5	 Orchestrates secure data plane connectivity between vEdges.
    
### OMP  : Overlay Managemt Protocol
  
    1   Runs between vEdge routers and vSmart controllers and between the vSmart controllers.
	         - inside TLS/DTLS connections
    2	  Advertises control plane context.



