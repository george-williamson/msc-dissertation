# Machine Learning Methods for Fantasy Football

### Abstract:
*This dissertation looks at machine learning methods to tackle the sequential decision making problem that is the game of Fantasy Football or more specifically, Fantasy Premier League (FPL). It takes a look at the landscape of the decision making problem, one of which can be broken down into two core subproblems: (i) player performance prediction or points prediction, and (ii) team formation optimisation. The current best benchmark for an automated FPL manager was presented in the paper by Matthews et al. [25]. In this dissertation we shall explore the theory that underpins their approach, much of which is based on reinforcement learning and bayesian inference, whilst also presenting our own alternative supervised learning approach to the problem.
We take a look at the first subproblem by exploring current methods for modelling football matches, much of which has stemmed from the work of Dixon and Coles [11]. We also look at an extension of the Dixon and Coles paper, namely the Dixon- Robinson model [10] and look at how this can be utilised for points prediction in FPL. We show that one can use supervised learning methods to predict player points directly without any simulations involved, potentially circumventing the computa- tional expensiveness that comes with the Monte Carlo simulations Matthews et al. used. The second subproblem can be solved efficiently once player performance is forecasted, more precisely we can choose an optimal team once we have forecasted individual player points within FPL. This can be done by using a Mixed Integer Pro- gramming formulation by framing the team selection process as a Multidimensional Knapsack Problem. This was shown to work well in paper by Matthews et al. [25] and we present an overview of how it works. Furthermore, we then combine the the- ory for the two subproblems to tackle the grand problem of sequentially choosing an optimal team, and evaluate the results of our supervised learning model in the last section. We then swiftly conclude and wrap up the dissertation with some advice on possible directions for future work.*

### Content
1. Introduction

  1.1 Background
  
  1.2 FPL
  
  1.3 Outline

2. Reinforcement Learning

  2.1 Basic Definitions
  
  2.2 Markov Decision Processes
  
  2.3 Exploration vs. Exploitation
  
  2.4 Q-learning
 
3. Modelling Football and Predicting Performance

  3.1 Dixon-Coles Model
  
  3.2 Dixon-Robinson Model
  
  3.3 Supervised Learning Approach
  
 
4. Modelling FPL

  4.1 Conjugate Priors
  
  4.2 Belief MDP for FPL
  
  4.3 Team Formation Optimisation
  
  4.4 Bayesian Q-learning
  
  4.5 An Alternative Approach

5. Computational Experiments

6. Conclusion
