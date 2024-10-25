---
  hide:
    -navigation
---

## International Journals

### 1. Chatzilygeroudis, K., Dionis, T., Mouret, J.-B. 2024. **RobotDART: a versatile robot simulator for robotics and machine learning researchers**. *Journal of Open Source Software (JOSS).*

   **Abstract:** *Robot simulation plays a pivotal role in robotics and machine learning research, offering a cost-effective and safe means to develop, validate, and benchmark algorithms in various scenarios. With the growing complexity of robotic systems and the increasing demand for data-driven approaches in machine learning, there is a pressing need for versatile and efficient robot simulators that cater to the diverse requirements of researchers. In response to this demand, we introduce RobotDART, a high-performance and versatile robot simulator designed to empower researchers in robotics and machine learning with a powerful and flexible simulation environment.*

   [(view online)](https://joss.theoj.org/papers/10.21105/joss.06771)
   [(documentation)](https://nosalro.github.io/robot_dart/)
   [(code)](https://github.com/NOSALRO/robot_dart)
   [(doi)](https://doi.org/10.21105/joss.06771)

## International Conferences

### 5. Tsikelis, I.\*, and Chatzilygeroudis, K.\* 2024. **Gait Optimization for Legged Systems Through Mixed Distribution Cross-Entropy Optimization**. *IEEE-RAS International Conference on Humanoid Robots (Humanoids).*

   **Abstract:** *Legged robotic systems can play an important role in real-world applications due to their superior load-bearing capabilities, enhanced autonomy, and effective navigation on uneven terrain. They offer an optimal trade-off between mobility and payload capacity, excelling in diverse environments while maintaining efficiency in transporting heavy loads. However, planning and optimizing gaits and gait sequences for these robots presents significant challenges due to the complexity of their dynamic motion and the numerous optimization variables involved. Traditional trajectory optimization methods address these challenges by formulating the problem as an optimization task, aiming to minimize cost functions, and to automatically discover contact sequences. Despite their structured approach, optimization-based methods face substantial difficulties, particularly because such formulations result in highly nonlinear and difficult to solve problems. To address these limitations, we propose CrEGOpt, a bi-level optimization method that combines traditional trajectory optimization with a black-box optimization scheme. CrEGOpt at the higher level employs the Mixed Distribution Cross-Entropy Method to optimize both the gait sequence and the phase durations, thus simplifying the lower level trajectory optimization problem. This approach allows for fast solutions of complex gait optimization problems. Extensive evaluation in simulated environments demonstrates that CrEGOpt can find solutions for biped, quadruped, and hexapod robots in under 10 seconds. This novel bi-level optimization scheme offers a promising direction for future research in automatic contact scheduling.*

   *\* Equal Contribution*

   [(view online)](https://arxiv.org/abs/2410.02891)

### 4. Asimakopoulos, K., Androutsopoulos, A., Vrahatis, M. and Chatzilygeroudis, K. 2024. **Effective Kinodynamic Planning and Exploration through Quality Diversity and Trajectory Optimization**. *The 18th learning and intelligent optimization conference (LION).*

   **Abstract:** *Efficient and rapid kinodynamic planning is crucial for numerous real-world robotics applications. Various methods have been proposed to address this challenge, primarily falling into two categories: (a) randomized planners and (b) trajectory optimization utilizing simplified models and numerical optimization. Randomized planners such as RRT and PRM excel in exploring the state space, while trajectory optimization methods, like direct collocation, are adept at discovering optimal trajectories within well-defined spaces. We aim to achieve effective and efficient kinodynamic planning and exploration by integrating evolutionary algorithms (Quality-Diversity) with trajectory optimization. Our preliminary experiments showcase that using the proposed methodology we get the best from both worlds on two simulated experiments.*

   [(view online)](https://costashatz.github.io/files/LION18.pdf)

### 3. Tsakonas, C. and Chatzilygeroudis, K. 2023. **Effective Skill Learning via Autonomous Goal Representation Learning**. *The Fourteenth International Conference on Information, Intelligence, Systems and Applications (IISA 2023)*

   **Abstract:** *A long standing goal of robotics researchers is to develop robots that are able to develop in an autonomous open-ended manner through lifelong learning and interactions. If we are to see robots learning in an autonomous and open-ended manner, we need to develop methods for incremental and autonomous skill discovery and trial-and-error learning. In other words, we want our robots to be able to autonomously select their goals according to their current capabilities and learn controllers or policies to achieve those goals. In this paper, we take a step towards solving this challenge and propose a novel pipeline, called AGRL, that effectively combines deterministic simulations, Variational Auto-Encoders (VAEs) and Reinforcement Learning (RL) and enables robots to learn goal-conditioned policies suited to their capabilities. Our main intuition is that we can use effective exploration strategies in order to learn a good goal representation and distribution, and then use this distribution to generate effective and reachable goals for fast skill learning. We extensively evaluate the proposed method in simulation with a 7DOF manipulator and a differential drive mobile robot.*

   [(view online)](https://costashatz.github.io/files/IISA2023-AGRL.pdf) [(video)](https://www.youtube.com/watch?v=x-j5mid6jxM)

### 2. Chatzilygeroudis, K., Tsakonas, C. and Vrahatis, M. 2023. **Evolving Dynamic Locomotion Policies in Minutes**. *The Fourteenth International Conference on Information, Intelligence, Systems and Applications (IISA 2023)*

   **Abstract:** *Many effective evolutionary methods have been proposed that allow robots to learn how to walk. Most of the proposed methods have one or more of the following drawbacks: (a) utilization of hand designed open loop policies that cannot scale to different robots, and/or (b) requiring big wall time due to sample inefficiency and simulation costs, a fact that limits the practical usage of those algorithms. In the paper at hand, we propose combination of (a) a simplified model for locomotion dynamics, and (b) the effectiveness of quality-diversity algorithms, and propose a novel algorithm that is able to evolve, in less than an hour on a standard computer, generic (e.g. neural network), and reactive locomotion policies. Our approach makes it possible to generate in a few minutes reactive policies for locomotion that can perform dynamic motions like jumps. We also present preliminary results of transferring the behaviors to realistic simulators using a whole body inverse kinematics solver and a joint impedance controller.*

   [(view online)](https://costashatz.github.io/files/IISA2023-EvoLoco.pdf) [(video)](https://www.youtube.com/watch?v=VdyUlAAWMzQ)

### 1. Chatzilygeroudis, K. and Vrahatis, M. 2023. **Fast and Robust Constrained Optimization via Evolutionary and Quadratic Programming**. *The 17th learning and intelligent optimization conference (LION).*

   **Abstract:** *Many efficient and effective approaches have been proposed in the evolutionary computation literature for solving constrained optimization problems. Most of the approaches assume that both the objective function and the constraints are black-box functions, while a few of them can take advantage of the gradient information. On the other hand, when the gradient information is available, the most versatile approaches are arguably the ones coming from the numerical optimization literature. Perhaps the most popular methods in this field are sequential quadratic programming and interior point. Despite their success, those methods require accurate gradients and usually require a well-shaped initialization to work as expected. In the paper at hand, a novel hybrid method, named UPSO-QP, is presented that is based on particle swarm optimization and borrows ideas from the numerical optimization literature and sequential quadratic programming approaches. The proposed method is evaluated on numerous constrained optimization tasks from simple low dimensional problems to high dimensional realistic trajectory optimization scenarios, and showcase that is able to outperform other evolutionary algorithms both in terms of convergence speed as well as performance, while also being robust to noisy gradients and bad initialization.*

   [(view online)](http://costashatz.github.io/files/LION17.pdf)

## Peer-Reviewed Workshops

### 1. Totsila, D.\*, Chatzilygeroudis, K.\*, Hadjivelichkov, D., Modugno, V., Hatzilygeroudis, I. and Kanoulas, D., 2023. **End-to-End Stable Imitation Learning via Autonomous Neural Dynamic Policies**. *IEEE International Conference on Robotics and Automation (ICRA), Life-Long Learning with Human Help (L3H2) Workshop*

   **Abstract:** *State-of-the-art sensorimotor learning algorithms offer policies that can often produce unstable behaviors, damaging the robot and/or the environment. Traditional robot learning, on the contrary, relies on dynamical system-based policies that can be analyzed for stability/safety. Such policies, however, are neither flexible nor generic and usually work only with proprioceptive sensor states. In this work, we bridge the gap between generic neural network policies and dynamical system-based policies, and we introduce Autonomous Neural Dynamic Policies (ANDPs) that: (a) are based on autonomous dynamical systems, (b) always produce asymptotically stable behaviors, and (c) are more flexible than traditional stable dynamical system-based policies. ANDPs are fully differentiable, flexible generic-policies that can be used in imitation learning setups while ensuring asymptotic stability. In this paper, we explore the flexibility and capacity of ANDPs in several imitation learning tasks including experiments with image observations. The results show that ANDPs combine the benefits of both neural network-based and dynamical system-based methods.*

   *\* Equal Contribution*

   [(view online)](https://arxiv.org/abs/2305.12886)
   [(poster)](files/2023-ICRA-L3H2-Poster-ANDPs.pdf)
