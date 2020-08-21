1. A policy is a function which maps ____ to ____.  
   => States to probability distributions over actions.
   
2. The term “backup” most closely resembles the term ___ in meaning.  
   => Update
   
3. At least one deterministic optimal policy exists in every Markov decision process.  
   => True. 
   Let’s say there is a policy \pi_{1} which does well in some states, while policy \pi_2π does well in others. 
   We could combine these policies into a third policy \pi_3π , which always chooses actions according to whichever of policy \pi_1π and \pi_2π 
   has the highest value in the current state. \pi_3π will necessarily have a value greater than or equal to both \pi_1π and \pi_2π in every state! 
   So we will never have a situation where doing well in one state requires sacrificing value in another. Because of this, there always exists some 
   policy which is best in every state. This is of course only an informal argument, but there is in fact a rigorous proof showing that there must 
   always exist at least one optimal deterministic policy.



