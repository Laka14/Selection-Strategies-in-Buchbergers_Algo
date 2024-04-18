# Selection-Strategies-in-Buchbergers_Algo

Studying the set of exact solutions of a system of polynomial equations largely depends on a single iterative algorithm, known as Buchbergers algorithm. Optimized versions of this algorithm
are crucial for many computer algebra systems (e.g., Mathematica, Maple, Sage). We introduce a new approach to Buchbergers algorithm that uses reinforcement learning agents to perform S-pair selection, a key step in the algorithm. 
We then study how the difficulty of the problem depends on the choices of domain and distribution of polynomials, about which little is known. Finally, we train a policy model using proximal policy optimization (PPO) to learn S-pair selection strategies for random systems of binomial equations.
In certain domains, the trained model outperforms state-of-the-art selection heuristics in total number of polynomial additions performed, which provides a proof-of-concept that recent developments in machine learning have the potential to improve performance of algorithms in symbolic computation.
