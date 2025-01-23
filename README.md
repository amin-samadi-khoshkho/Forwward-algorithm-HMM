# Forwward-algorithm-HMM
This problem is from an assignment of my Pattern Recognition course in 2019.

1. Show that for a Markov Chain, $𝑃(𝑞_𝑡|𝑞_𝑡+1, … , 𝑞_𝑇) = 𝑃(𝑞_𝑡| 𝑞_𝑡+1)$.

2. Consider the following 2-state Hidden Markov Models where both states have two
possible output symbols A and B.

    - **Model 1**:

        Transition probabilities: $a_{11} = 0.6$, $a_{12} = 0.4$, $a_{21} = 0.0$, $a_{22} = 1.0$ ($a_{ij}$ is the probability of going from state i to state j)
        
        Output probabilities: $b_1(A) = 0.45$, $b_1(B) = 0.55$, $b_2(A) = 0.5$, $b_2(B) = 0.5$
        
        Initial probabilities: $𝜋_1 = 0.4$, $𝜋_2 = 0.6$

    - **Model 2**:
    
        Transition probabilities: $a_{11} = 0.2$, $a_{12} = 0.8$, $a_{21} = 0.0$, $a_{22} = 1.0$
        
        Output probabilities: $b_1(A) = 0.2$, $b_1(B) = 0.8$ , $b_2(A) = 0.6$, $b_2(B) = 0.4$
        
        Initial probabilities: $𝜋_1 = 0.7$, $𝜋_2 = 0.3$

a. Sketch the state diagram for two models.

b. Which model is more likely to produce the observation sequence {A, B, A} ?
