# Mini Course in Dynamic Structural Econometrics, UAB, September 12-16, 2022

This repository contains teaching materials for lectures in a short PhD course in **Dynamic Structural Econometrics** to be held in Barcelona September 12-16, 2022. Repository will be updated as we go a along. 

## Course description 
The overall purpose of the course is to provide a fundamental understanding of dynamic programming models and their empirical application. 

The dynamic programming framework has been extensively used in economic modeling because it is sufficiently rich to model almost any problem involving sequential decision making over time and under uncertainty. Prominent examples are saving/consumption decisions, retirement behavior, investment, labor supply/demand, occupational choice, housing decisions. 

The course will mainly focus on introducing participants to the basic numerical tools, solution algorithms and estimation methods nessesary to carry out structural estimation of single agent discrete and continuous decision problems. The focus is primarily on helping students develop the skills for programming solution algorithms and estimators.  
 

## [Part 0:  Theory and tools](https://github.com/bschjerning/dp_uab/tree/main/0_theory_tools)      
- We start by introducin the Markov decision processes (MDP) and show how dynamic programming (DP) can be sused to solve these models for both finite and infitive horizons. This gives a basict introduction to the Bellman operator and it's contraction properties and how to find fixed points using for example Value Function Iterations.  

## [Part 1:  Structural estimation of dynamic discrete choice models](https://github.com/bschjerning/dp_uab/tree/main/1_dynamic_discrete_choice)      
- In the first part of lectures on dynamic discrete choice models we will consider a variety of methods to structurally estimate dynamic discrete choice models (NFXP, MPEC, NPL, CCP type estimators). As a testbed for comparison we will use the canonical Bus Engine Replacement model in Rust's 1987 *Econometrica* paper.

## [Part 2: Structural estimation of models with continuous and discrete choices](https://github.com/bschjerning/dp_uab/tree/main/2_discrete_continuous_choice)
- In the second series of lectures on dynamic discrete-continuous choice models we will consider state of the art solution methods for models that combine continuous and discrete choices. We start with a simple consumption savings model, and then move on to models that combine discrete and continuous choices and show how state of the art methods (DC-EGM) can be used to solve and estimate a class of Discrete-Continuous Dynamic Choice Model fast and accurately. 

## [Part 3: Solving and estimating dynamic games](https://github.com/bschjerning/dp_uab/tree/main/0_theory_tools)   

- In this last series of lectures (which we will actially cover as the third one) we consider the cahlenges of estimation of dymnamic games of incomplete information. We wiil start with the simplest possible game. A static enrty game with two players, and show how we can estimate the model using NFXP, MPEC, NPL, and 2-step CCPs. A special focus will be on the issue taht arise from mutiple equilibria. We the move on to dynamic games.     

# Tentative lecture plan [slides in brackets]
**Monday Sept 12 2022: class 11:00 -14:00 ( Room: AULA Seminari A)**

- Introduction to Markov decision processes (MDP) and dynamic programming (DP) [[0_theory_tools/01_dp_intro.ipynb](https://github.com/bschjerning/dp_uab/blob/main/0_theory_tools/01_dp_intro.ipynb)]
- Numerical implementation of simple deterministic DP problem: The cake eating problem [[0_theory_tools/02_cake_eating_example.ipynb](https://github.com/bschjerning/dp_uab/blob/main/0_theory_tools/02_cake_eating_example.ipynb)]

**Tuesday Sept 13 2022: seminar  15:00 -17:00 (Room: AULA Seminari A)**

-  Equilibrium Trade in Automobiles [[1_dynamic_discrete_choice/4_eqbtrade.pdf](https://github.com/bschjerning/dp_uab/blob/main/1_dynamic_discrete_choice/4_eqbtrade.pdf)]

**Wednesday Sept 14 2022: class 10:00 -13:00  ( Room: AULA Seminari A)**

-  The Nested Fixed Point Algorithm and Constrained Optimization Approaches to Structural Estimation (MPEC) [[1_dynamic_discrete_choice/1_nfxp_mpec.pdf]](https://github.com/bschjerning/dp_uab/blob/main/1_dynamic_discrete_choice/1_nfxp_mpec.pdf)
-  Sequential Estimation in Discrete Decision Problems: Nested Pseudo Likelihood (NPL) and CCP estimators [[1_dynamic_discrete_choice/3_npl_ccp.pdf]](https://github.com/bschjerning/dp_uab/blob/main/1_dynamic_discrete_choice/3_npl_ccp.pdf)

**Thusday Sept 15 2022: class 10:00 - 13:00 ( Room: AULA Seminari A)**

-  Solving and Estimating STATIC Games of
Incomplete Information [[3_dynamic_discrete_games/1_sgame.pdf]](https://github.com/bschjerning/dp_uab/blob/main/3_dynamic_discrete_games/1_sgame.pdf)

- Solving and Estimating DYNAMIC Games of
Incomplete Information [[3_dynamic_discrete_games/2_dgame.pdf]](https://github.com/bschjerning/dp_uab/blob/main/3_dynamic_discrete_games/2_dgame.pdf)
- Solving and estimating DIRECTIONAL dynamic games
and Multiplicity of equilibria [[3_dynamic_discrete_games/3_ddg.pdf]](https://github.com/bschjerning/dp_uab/blob/main/3_dynamic_discrete_games/3_ddg.pdf)

- AFTER CLASS: A dynamic equilibrium model of commuting, residential and work location choices [[1_dynamic_discrete_choice/3_urban.pdf]](https://github.com/bschjerning/dp_uab/blob/main/1_dynamic_discrete_choice/3_urban.pdf)

**Friday Sept 16 2022 : class 10:00 -13:00 ( Room: AULA Seminari A)**
- Stochastic DP, 1-d Numerical Integration, Deaton's model [[0_theory_tools/03_deaton_1d_integration.ipynb](https://github.com/bschjerning/dp_uab/blob/main/0_theory_tools/03_deaton_1d_integration.ipynb)]
- Time iterations and the Endogenous gridpoint method (EGM) [[2_discrete_continuous_choice/1_euler_egm.ipynb](https://github.com/bschjerning/dp_uab/blob/main/2_discrete_continuous_choice/1_euler_egm.ipynb)]
- Discrete-Continuous Choice Models  (DC-EGM) [[2_dcegm.pdf]](https://github.com/bschjerning/dp_uab/blob/main/2_discrete_continuous_choice/2_dcegm.pdf)
- Empirical application of DC-EGM (Iskhakov and Keane, JoE 2021): [[4_aupens_dc_egm.pdf]](https://github.com/bschjerning/dp_uab/blob/main/2_discrete_continuous_choice/4_aupens_dc_egm.pdf)              

## Videotaped lectures
Previsously recorded lectures are available at the [Lectures in Dynamic Programming playlist](https://www.youtube.com/watch?v=SbVIgzWt8So&list=PLzkJu0O0lYnEpJNYJ4Ent_qckS0OKkYYg) on Bertel Schjerning's [YouTube channel](https://www.youtube.com/user/BSchjerning). 



