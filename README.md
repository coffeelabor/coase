# Coase - a brief description

This repository contains code related to a model I am preparing for the thesis component of my MSc in economics.
I am seeking to extend Gintis' 2007 model of decentralised bilateral exchange to include firms and associated extensions.
Specifically I am interested in the dynamics of the model: how quickly prices - including wages - converge to 'public prices' and the walrasian price vector.

The firm-inclusive model includes two stages of exchange: labour exchange and goods exchange.

## Labour exchange
Firms purchase labour from household agents at prices determined by nash-bargaining and the private prices of each agent. 
Any labour purchased by firms is used to produce output specific to that firm-type, while households collect wages. 

## Goods exchange
Agents then seek to purchase the various goods available from firm.
This is arranged in a similar way to the 2007 model - a process of stochastic, sequential exchange which allows each household agent the opportunity to buy each type of good.
Firm-household matching could be designed in a number of ways - ideally the model should allow for variation. 

## Evolutionary dynamics
The beauty of the Gintis model is the process of evolutionary adaption.
Agents 'copy' prices of more successful agents causing convergence to 'public' prices, followed by the Walrasian price vector.

Similar mechanics will be adopted for firms and households in this extension.

Firms will copy more successful firms - both their going wage rate and the price of their output. 
Households will copy the wage rates of more successful agents and their private prices for goods. 
Obviously this system is more complicated than the original Gintis model - convergence to public and Walrasian prices may be slower. 
