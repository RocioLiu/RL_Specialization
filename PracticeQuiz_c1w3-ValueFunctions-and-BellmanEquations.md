1. A policy is a function which maps ____ to ____.  
   => States to probability distributions over actions.
     
     
2. The term “backup” most closely resembles the term ___ in meaning.  
   => Update
   
     
3. At least one deterministic optimal policy exists in every Markov decision process.  
   => True.  
   Let’s say there is a policy $ \pi_1 $ which does well in some states, while policy \pi_2π does well in others. 
   We could combine these policies into a third policy \pi_3π , which always chooses actions according to whichever of policy \pi_1π and \pi_2π 
   has the highest value in the current state. \pi_3π will necessarily have a value greater than or equal to both \pi_1π and \pi_2π in every state! 
   So we will never have a situation where doing well in one state requires sacrificing value in another. Because of this, there always exists some 
   policy which is best in every state. This is of course only an informal argument, but there is in fact a rigorous proof showing that there must 
   always exist at least one optimal deterministic policy.
    
    
4. The optimal state-value function:   
   => Is unique in every finite Markov decision process.   
   The Bellman optimality equation is actually a system of equations, one for each state, so if there are N states, then there are N equations in 
   N unknowns. If the dynamics of the environment are known, then in principle one can solve this system of equations for the optimal value function 
   using any one of a variety of methods for solving systems of nonlinear equations. All optimal policies share the same optimal state-value function.
   
    
5. Does adding a constant to all rewards change the set of optimal policies in episodic tasks?   
   => Yes, adding a constant to all rewards changes the set of optimal policies.   
   Adding a constant to the reward signal can make longer episodes more or less advantageous (depending on whether the constant is positive or negative).  
   
   
6. Does adding a constant to all rewards change the set of optimal policies in continuing tasks?   
   => No, as long as the relative differences between rewards remain the same, the set of optimal policies is the same.   
   Since the task is continuing, the agent will accumulate the same amount of extra reward independent of its behavior.   
   
   
7. Select the equation that correctly relates $ v_{\ast} $ to q_{\ast} . Assume \piπ is the uniform random policy.

1 / 1 point

v_{\ast}(s) = max_a q_{\ast}(s, a)v 
∗
​	
 (s)=max 
a
​	
 q 
∗
​	
 (s,a)
 
 \Omega
