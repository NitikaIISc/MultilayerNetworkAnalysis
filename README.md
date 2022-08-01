# MultilayerNetworkAnalysis

In the multilayer network, each of the four social situations (aggression, trophallaxis, solid food exchange, spatial overlap) was depicted as a weighted and directed layer. Intralayer connections were as detailed above for each of the social situations. Interlayer edges in the multilayer network link the same individual across layers, with no variation in the weights of the interlayer edges
To determine whether the social network structure of R. marginata colonies can provide information about the role of different individuals in the society, we examined the degree distribution of both the multilayer and the aggregate interaction networks

To determine whether the reproductive heir in a social wasp can be identified based on her network centrality (outdegree or outstrength) in the presence of the queen,
we compared these network measures of the potential queen to those expected by chance. 
  
  To create a chance reference distribution that preserves the observed network structure but shuffles the position of each individual in the network, 
  we ran 1000 simulations in which we permuted node identities on the observed network, i.e. only node identities (IDs) were shuffled, not edges (Hobson et al., 2021). 
  For the multilayer network, we shuffled node IDs only within a layer and not across layers to account for the absence of interactions by some wasps in certain 
  social situations - agonistic or affiliative interactions. For each permuted network, we calculated the versatility/centrality measures of the potential queen. 
  If the observed network measure fell outside the 95% confidence interval of the distribution of the measure from the 1000 permuted networks, 
  we concluded that the observed network measure of the potential queen was not a result of chance alone. All analyses were conducted in R v.3.6 (R Core Team, 2013)
