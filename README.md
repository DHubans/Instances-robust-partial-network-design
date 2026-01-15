# Instances-robust-partial-network-design
This repository contains benchmarks of instances for the robust partial network design problem

Each folder contains instances of one benchmark.

Each file represent one instance, they are eye human readable. 

Instances files are built as follow, text between [] are description of what should be there :

Instance name : [name]
Category : [MC or PC]
[If MC]MaximumBudget : [C_max]
[If PC]Minimum coverage : [G_min]
Nodes: [list of node names]
Edges : 
    [for each edge :]
    name : [edge name]
        nodes : [start node] [end node]
        nominal build cost : [build cost in base scenario]
        build cost interval : [min and max value for build cost]
        nominal use cost : [use cost in base scenario]
        use cost interval : [min and max value for use cost]
Demands :
    [for each O/D pairs]
    name : [O/D pair name]
        start node : [origin node of the demand]
        end node : [destination node of the demand]
        nominal gain : [gain in base scenario]
        gain interval : [min and max possible gains]
Gain facets : 
    [for each facets of gain polytope uncertainty]
    [constraints associated to this facet]
Cost facets :
    [for each facets of cost polytope uncertainty]
    [Constraints associated to this facet]