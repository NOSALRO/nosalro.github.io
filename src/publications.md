---
  hide:
    -navigation
---

## International Conferences

### 3. Tsakonas, C. and Chatzilygeroudis, K. 2023. **Effective Skill Learning via Autonomous Goal Representation Learning**. *The Fourteenth International Conference on Information, Intelligence, Systems and Applications (IISA 2023)*

   **Abstract:** *A long standing goal of robotics researchers is to develop robots that are able to develop in an autonomous open-ended manner through lifelong learning and interactions. If we are to see robots learning in an autonomous and open-ended manner, we need to develop methods for incremental and autonomous skill discovery and trial-and-error learning. In other words, we want our robots to be able to autonomously select their goals according to their current capabilities and learn controllers or policies to achieve those goals. In this paper, we take a step towards solving this challenge and propose a novel pipeline, called AGRL, that effectively combines deterministic simulations, Variational Auto-Encoders (VAEs) and Reinforcement Learning (RL) and enables robots to learn goal-conditioned policies suited to their capabilities. Our main intuition is that we can use effective exploration strategies in order to learn a good goal representation and distribution, and then use this distribution to generate effective and reachable goals for fast skill learning. We extensively evaluate the proposed method in simulation with a 7DOF manipulator and a differential drive mobile robot.*

### 2. Chatzilygeroudis, K., Tsakonas, C. and Vrahatis, M. 2023. **Evolving Dynamic Locomotion Policies in Minutes**. *The Fourteenth International Conference on Information, Intelligence, Systems and Applications (IISA 2023)*

   **Abstract:** *Many effective evolutionary methods have been proposed that allow robots to learn how to walk. Most of the proposed methods have one or more of the following drawbacks: (a) utilization of hand designed open loop policies that cannot scale to different robots, and/or (b) requiring big wall time due to sample inefficiency and simulation costs, a fact that limits the practical usage of those algorithms. In the paper at hand, we propose combination of (a) a simplified model for locomotion dynamics, and (b) the effectiveness of quality-diversity algorithms, and propose a novel algorithm that is able to evolve, in less than an hour on a standard computer, generic (e.g. neural network), and reactive locomotion policies. Our approach makes it possible to generate in a few minutes reactive policies for locomotion that can perform dynamic motions like jumps. We also present preliminary results of transferring the behaviors to realistic simulators using a whole body inverse kinematics solver and a joint impedance controller.*

### 1. Chatzilygeroudis, K. and Vrahatis, M. 2023. **Fast and Robust Constrained Optimization via Evolutionary and Quadratic Programming**. *The 17th learning and intelligent optimization conference (LION).*

   **Abstract:** *Many efficient and effective approaches have been proposed in the evolutionary computation literature for solving constrained optimization problems. Most of the approaches assume that both the objective function and the constraints are black-box functions, while a few of them can take advantage of the gradient information. On the other hand, when the gradient information is available, the most versatile approaches are arguably the ones coming from the numerical optimization literature. Perhaps the most popular methods in this field are sequential quadratic programming and interior point. Despite their success, those methods require accurate gradients and usually require a well-shaped initialization to work as expected. In the paper at hand, a novel hybrid method, named UPSO-QP, is presented that is based on particle swarm optimization and borrows ideas from the numerical optimization literature and sequential quadratic programming approaches. The proposed method is evaluated on numerous constrained optimization tasks from simple low dimensional problems to high dimensional realistic trajectory optimization scenarios, and showcase that is able to outperform other evolutionary algorithms both in terms of convergence speed as well as performance, while also being robust to noisy gradients and bad initialization.*

   [(view online)](http://costashatz.github.io/files/LION17.pdf)

## Peer-Reviewed Workshops

### 1. Totsila, D.\*, Chatzilygeroudis, K.\*, Hadjivelichkov, D., Modugno, V., Hatzilygeroudis, I. and Kanoulas, D., 2023. **End-to-End Stable Imitation Learning via Autonomous Neural Dynamic Policies**. *IEEE International Conference on Robotics and Automation (ICRA), Life-Long Learning with Human Help (L3H2) Workshop*

   **Abstract:** *State-of-the-art sensorimotor learning algorithms offer policies that can often produce unstable behaviors, damaging the robot and/or the environment. Traditional robot learning, on the contrary, relies on dynamical system-based policies that can be analyzed for stability/safety. Such policies, however, are neither flexible nor generic and usually work only with proprioceptive sensor states. In this work, we bridge the gap between generic neural network policies and dynamical system-based policies, and we introduce Autonomous Neural Dynamic Policies (ANDPs) that: (a) are based on autonomous dynamical systems, (b) always produce asymptotically stable behaviors, and (c) are more flexible than traditional stable dynamical system-based policies. ANDPs are fully differentiable, flexible generic-policies that can be used in imitation learning setups while ensuring asymptotic stability. In this paper, we explore the flexibility and capacity of ANDPs in several imitation learning tasks including experiments with image observations. The results show that ANDPs combine the benefits of both neural network-based and dynamical system-based methods.*

   *\* Equal Contribution*

   [(view online)](https://arxiv.org/abs/2305.12886)
   [(poster)](files/2023-ICRA-L3H2-Poster-ANDPs.pdf)
