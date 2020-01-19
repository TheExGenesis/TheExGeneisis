---
layout: ''
project: ''
published: false

---
\- Planeamento, Aprendizagem, Decisão Inteligente

    - \[\[Planning\]\], \[\[Machine Learning\]\], intelligent \[\[decision making\]\]

\- \[Office Hours\](https://fenix.tecnico.ulisboa.pt/disciplinas/PADInt.7/2019-2020/1-semestre/horario-de-duvidas-e-contactos)

\- Overview

    - Goals

        - Understand the main issues in \[\[decision making\]\] in the face of uncertainty

        - Familiarize with the main tools for **planning** and **learning** in such settings

    - !\[\](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fxiqo%2Fgt6Vmu8t1x?alt=media&token=4294b8e6-8142-4e5d-93ee-38e96d24e384)

\- \[Practice tests\](https://fenix.tecnico.ulisboa.pt/disciplinas/PADInt.7/2019-2020/1-semestre/testes)

\- \[Exercises to practice\](https://fenix.tecnico.ulisboa.pt/downloadFile/563568428782685/Exercises.pdf) (no solutions)

\- PADI Test 1

    - Tips

        - Practice makes perfect

        - Open book test

            - Any written material

            - Calculator

            - no cellphone

    - Example Tests

        - \[PP solving test\](https://fenix.tecnico.ulisboa.pt/downloadFile/1970943312340024/lec13.pdf)

        - 2015 \[Primeiro teste\](https://fenix.tecnico.ulisboa.pt/downloadFile/563568428782723/sol-test1-1516.pdf)

        - 2016 \[Primeiro teste\](https://fenix.tecnico.ulisboa.pt/downloadFile/563568428782724/sol-test1-1617.pdf)

        - 2017 \[Primeiro teste\](https://fenix.tecnico.ulisboa.pt/downloadFile/563568428782730/sol-test1-1718.pdf)

        - 2018 \[Primeiro teste\](https://fenix.tecnico.ulisboa.pt/downloadFile/563568428782727/sol-test1-1819.pdf)

        - 2019 \[Primeiro teste\](https://fenix.tecnico.ulisboa.pt/downloadFile/1407993358896926/sol-test1-1920.pdf)

    - Notes

        - {{\[\[TODO\]\]}} \[Cap. 1: Introdução\](https://fenix.tecnico.ulisboa.pt/downloadFile/282093452063471/1-introduction.pdf)

        - {{\[\[TODO\]\]}} \[\[Markov Chains\]\]

            - \[Cap. 2: Cadeias de Markov\](https://fenix.tecnico.ulisboa.pt/downloadFile/282093452063474/2-markov%20chains.pdf)

        - {{\[\[TODO\]\]}} \[\[Hidden Markov Models\]\]

            - \[Cap. 3: Modelos de Markov escondidos\](https://fenix.tecnico.ulisboa.pt/downloadFile/563568428785188/3-hmms.pdf)

        - {{\[\[TODO\]\]}} \[\[Utility Theory\]\] 

            - \[Cap. 4: Teoria da utilidade\](https://fenix.tecnico.ulisboa.pt/downloadFile/563568428785190/4-utility.pdf)

        - {{\[\[TODO\]\]}} Markov Decision Problems (\[\[MDP\]\]s) 

            - \[Cap. 5: Problemas de decisão de Markov\](https://fenix.tecnico.ulisboa.pt/downloadFile/1689468335625511/5-mdps.pdf)

        - {{\[\[TODO\]\]}} Partially Observable Markov Decision Problems (\[\[POMDP\]\]s) 

            - \[Cap. 6: Problemas de decisão de Markov parcialmente observáveis\](https://fenix.tecnico.ulisboa.pt/downloadFile/1689468335626083/6-pomdps.pdf)

\- PADI Test 2 \[\[January 20th, 2020\]\] - 11:30

    - Examples Tests (2)

        - Edição 2015-16

            - \[Segundo teste\](https://fenix.tecnico.ulisboa.pt/downloadFile/563568428782725/sol-test2-1516.pdf)

            - \[Exame\](https://fenix.tecnico.ulisboa.pt/downloadFile/563568428782729/sol-exam-1516.pdf)

        - Edição 2016-17

            - \[Segundo teste\](https://fenix.tecnico.ulisboa.pt/downloadFile/563568428782726/sol-test2-1617.pdf)

            - \[Exame\](https://fenix.tecnico.ulisboa.pt/downloadFile/563568428782721/sol-exam-1617.pdf)

        - Edição 2017-18

            - \[Segundo teste\](https://fenix.tecnico.ulisboa.pt/downloadFile/563568428782720/sol-test2-1718.pdf)

            - \[Exame\](https://fenix.tecnico.ulisboa.pt/downloadFile/563568428782722/sol-exam-1718.pdf)

        - Edição 2018-19

            - \[Segundo teste\](https://fenix.tecnico.ulisboa.pt/downloadFile/563568428782728/sol-test2-1819.pdf)

            - \[Exame\](https://fenix.tecnico.ulisboa.pt/downloadFile/563568428782719/sol-exam-1819.pdf)

    - Read/skim book

        - # {{\[\[TODO\]\]}} \[\[Machine Learning\]\] 

            - \[Cap. 7: Aprendizagem supervisionada\](https://fenix.tecnico.ulisboa.pt/downloadFile/282093452075896/7-supervised.pdf)

            - What is \[\[machine learning\]\]?

                - “A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P if its performance at tasks in T, as measured by P, improves with experience E.”

            - How to specify a Learning Problem?

            - ## Types of \[\[Machine Learning\]\]

                - \[\[Supervised Learning\]\]

                    - \[\[Classification\]\] (general)

                        - Discrete output

                            - e.g. Handwritten digit recognition

                        - "Symbolic" approach

                            - \[\[Decision Trees\]\]

                                - Learning rules

                                    - Make splits until training set is fully classified

                                    - Trees can be trivially converted to rules

                                        - Each path from the root to a lead is a rule

                                    - \[\[Entropy\]\]

                                        - Given set S with N bits, let 

                                        - p: amount of 1s

                                        - n: amount of 0s

                                        - The entropy of set S is

                                            - $$H(S)=-\\frac{p}{N} \\log _{2} \\frac{p}{N}-\\frac{n}{N} \\log _{2} \\frac{n}{N}$$

                        - Probabilistic approaches

                            - \[\[Logistic Regression\]\] and \[\[Naive Bayes\]\] are cousin models

                                - \[\[Logistic Regression\]\]

                                    - Discriminative Model

                                        - A discriminative model is a policy $$\\pi : X \\rightarrow \\Delta(A)$$

                                        - Determines $$\\pi(a|x)$$ 

                                            - the probability of action/class/label __a__ given __x__

                                        - **Deriving a model** (focusing on one probability at a time e.g. $$\\pi(1|x)$$)

                                            1. $$\\pi(1|x)$$ is **linear **in x

                                                1. $$\\pi(1|x) = w_0 + w_1\\phi(x)$$

                                                2. Problem? 

                                                    1. Probabilities outside \[0,1\]

                                            2. **Ratio **between $$\\pi(1|x)$$ and $$\\pi(0|x)$$ is linear in x:

                                                1. $$\\frac{\\pi(1|x)}{\\pi(0|x)} = w_0 + w_1\\phi(x) <=>$$

                                                2. $$\\frac{\\pi(1|x)}{1 - \\pi(1|x)} = w_0 + w_1\\phi(x)$$

                                                    1. Goes from 0 to infinity

                                                3. Problem? 

                                                    1. Probability $$\\pi(1|x)$$ never reaches 1, however, it can be negative

                                            3. **Log ratio** between $$\\pi(1|x)$$ and $$\\pi(0|x)$$ is linear in x:

                                                1. $$\\log\\frac{\\pi(1|x)}{\\pi(0|x)} = w_0 + w_1\\phi(x)$$

                                                    1. goes from negative to positive infinity

                                                2. $$\\pi(1|x) = \\frac{1}{1 + e^{-(w_0 + w_1\\phi(x))}}$$

                                                3. !\[\](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fxiqo%2FPalgqGyq_7?alt=media&token=63d68afe-d905-48b6-af5b-f7419e528827)

                                    - Does not assume independence

                                    - Training the classifier corresponds to computing w0 and w1

                                        - $$\\pi(1|x) = \\frac{1}{1 + e^{-(w_0 + w_1\\phi(x))}}$$

                                    - How to evaluate quality of the classifier?

                                        - Negative log-likelihood

                                            - $$l(x,a;\\pi) = - \\log \\pi (a|x)$$

                                            - $$\\hat{L}_N(\\pi) = - \\frac{1}{N} \\sum_{n=1}^{N} \\log \\pi (a_n|x_n)$$

                                            - Sum of logs of the probabilities for each prediction is equivalent to their product, which is the likelihood of the data given that samples are independent

                                        - Empirical risk

                                            - $$\\hat{L}_{N}(\\pi)=-\\frac{1}{N} \\sum_{n=1}^{N} a_{n} \\log \\pi\\left(1 | x_{n}\\right)+\\left(1-a_{n}\\right) \\log \\left(1-\\pi\\left(1 | x_{n}\\right)\\right)$$

                                                - This makes sense I swear

                                    - Learning with LR

                                        - Using the gradient

                                            - $$\\frac{\\partial \\log \\hat{L}_{N}(\\pi)}{\\partial w_{0}}=\\frac{1}{N} \\sum_{n=1}^{N}\\left(\\pi\\left(1 | x_{n}\\right)-a_{n}\\right)$$

                                            - $$\\frac{\\partial \\log \\hat{L}_{N}(\\pi)}{\\partial w_{1}}=\\frac{1}{N} \\sum_{n=1}^{N} \\phi\\left(x_{n}\\right)\\left(\\pi\\left(1 | x_{n}\\right)-a_{n}\\right)$$

                                            - We can compute w0 and w1 using gradient descent

                                                - $$w = w - \\alpha \\Delta_w \\hat{L}_{N}(\\pi)$$

                                    - $$\\pi(1|x) = \\frac{1}{1+e^{-w^T\\phi(x)}}$$

                                        - However, it's possible to compute this probability with the Bayes rule

                                - \[\[Naive Bayes\]\]

                                    - Generative Model

                                        - determines the joint probabilities P \[x = x, a = a\])

                                    - Assumes independence of attributes given class

                                        - {{embed: ((_EHVjrRq3))}}

                                    - {{embed: ((A0UTbx8hM))}}

                                        - $$\\text {Given } \\vec{x}=\\left(A_{1}=v_{x_{1}}, \\ldots, A_{d}=v_{x_{d}}\\right)$$

                                        - $$\\widehat{y}=\\arg \\max _{c_{i}}\\left\\{P\\left(c_{i}\\right) \\times \\prod_{j=1}^{d} P\\left(A_{j}=v_{x_{j}} | c_{i}\\right)\\right\\}$$

                                        - Joint Probabilities estimation

                                            - Numeric attributes

                                                - $$\\widehat{P}\\left(x_{j} | c_{i}\\right)=f\\left(x_{j} | \\mu_{i j}, \\sigma_{i j}^{2}\\right)$$

                                            - Symbolic attributes

                                                - $$\\widehat{P}\\left(x_{j} | c_{i}\\right)=\\frac{\\left|\\left\\{z \\in D_{i}: \\vec{z} \\cdot A_{j}=x_{j}\\right\\}\\right|+1}{n_{i}+m_{j}}$$

                                    - For **continuous attributes**, we represent likelihood P(x|a) as a Gaussian

                                        - Mean

                                            - $$\\mu_{a, k}=\\frac{1}{N_{a}} \\sum_{n=1}^{N} \\phi_{k}\\left(x_{n}\\right) \\mathbb{I}\\left(a_{n}=a\\right)$$

                                        - Variance

                                            - $$\\sigma_{a, k}^{2}=\\frac{1}{N_{a}-1} \\sum_{n=1}^{N}\\left(\\phi_{k}\\left(x_{n}\\right)-\\mu_{a, k}\\right)^{2} \\mathbb{I}\\left(a_{n}=a\\right)$$

                                    - Good when there's little data

                                    - Non-independent attributes get "counted twice" due to the assumption

                        - Similarity-based approach

                            - \[\[kNN\]\]

                                - "K-nearest neighbors (\[\[kNN\]\])"

                                - How does it work?

                                    - New point arrives, check k closest points

                                    - Select the class of the majority (odd k)

                                - Distance-weighted kNN

                                    - $$

                                    - y=\\operatorname{sgn}\\left(\\sum^{N} \\alpha y_{n} k\\left(\\boldsymbol{x}_{n}, \\boldsymbol{x}\\right)\\right)

                                    - $$

                            - Maximum Margin Classifier

                                - !\[\](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fxiqo%2FyhhoR_OQiE?alt=media&token=6b26f376-c958-4732-8ae4-3386daed3234)

                                - Maximizes margin between classes

                                - How to compute?

                                    1. Step 1. Points in the decision boundary:

                                        1. w · x + b = 0

                                    2. Step 2. Points in the margin:

                                        1. y(w · x + b)=1

                                    3. Step 3. Width of the (double) margin:

                                        1. $$\\frac{2}{||w||}$$

                                - We want to solve the following optimization problem

                                    - $$min \\quad||w||^2$$

                                    - $$s.t. \\quad y_n (w \\cdot x_n + b) \\geq 1$$

                                - 

                            - Support Vector Machine (\[\[SVM\]\]) 

                                - Question:: Not really getting the Lagrangian

                                - !\[\](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fxiqo%2FBRMLmCnihw?alt=media&token=b8db537b-bab5-4d55-95fe-5941b68a21b5)

                                - Lagrangian

                                    - The optimization problem can be turned into:

                                    - $$L(\\boldsymbol{w}, \\boldsymbol{\\alpha})=\\|\\boldsymbol{w}\\|^{2}+\\sum_{n=1}^{N} \\alpha_{n}\\left(1-y_{n}\\left(\\boldsymbol{w} \\cdot \\boldsymbol{x}_{n}+b\\right)\\right)$$

                                    - Lagrangian needs KKT conditions to find minimum

                                - Classifier

                                    - $$y=\\operatorname{sign}\\left(\\sum_{n=1}^{N} \\alpha_{n} y_{n} \\left(\\boldsymbol{x}_{n}, \\boldsymbol{x}\\right)+b\\right)$$

                                - In an SVM, the output is a combination of the labels of the support vectors (i.e. the data points that fall in the margin)

                        - Neural approaches

                            - \[\[Neural Networks\]\]

                                - Activation function

                                    - ReLU = max{0,z}

                                    - Sigmoid: $$ \\sigma(z) = \\frac{1}{1+e^{-z}}$$

                                        - \[0,1\], decision boundary = 0.5

                                    - People use ReLU, not sigmoid

                                - Forward propagation

                                    - !\[\](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fxiqo%2FIHfy0HdDdf?alt=media&token=3ab506a2-d7d0-4c1d-a86c-45b8e41b5515)

                                    - !\[\](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fxiqo%2FseNyVMul9p?alt=media&token=728a3408-ec99-40ee-8dcd-651b0d0ca121)

                                - Back propagation

                                    - !\[\](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fxiqo%2F9IFj7Vfy53?alt=media&token=61c80040-5a5d-4a98-9de3-3d68cd7b6bee)

                                    - 1. Initialize weights $$w_{ij}$$ (connecting output of neuron i to neuron j) to small random values

                                    - 2. Apply a data-point x* to the input layer

                                    - 3. Propagate the signal through the network

                                        - $$y_{i}=\\sigma\\left(z_{i}\\right)=\\sigma\\left(\\boldsymbol{w}_{j i} \\boldsymbol{y}_{j}\\right)$$

                                    - 4. Back-propagate δi back through the network

                                        - $$\\delta_{i}=\\left\\{\\begin{array}{ll}{\\left(a_{i}-a\\right)} & {\\text { if } i \\text { is an output unit }} \\\\{\\sigma^{\\prime}\\left(z_{i}\\right) \\sum_{k} w_{i j} \\delta_{j}} & {\\text { otherwise }}\\end{array}\\right.$$

                                    - 5. Update weights

                                - MLP

                                    - !\[\](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fxiqo%2FdTX7_XlBVY?alt=media&token=acb3c40c-266e-4e2c-98f5-b48a74cbb11d)

                        - What if we assume classes can be described as an MDP?

                            - Examples come from optimal policy of an MDP

                            - We can

                                - try to bring the MDP structure to one of the approaches used: "MDP-induced metric"

                                - "invert" the MDP: "\[\[Inverse Reinforcemente Learning\]\] (\[\[IRL\]\])"

                            - MDP-induced metric

                                - Motivation

                                    - Given a metric for MDPs, examples of actions in one state can be generalized to "nearby" states

                                    - Then, if the "teacher" follows the optimal policy, the learner can learn it without planning

                                - Measuring similarity

                                    - Comparing states in MDPs

                                        - Same actions have same outcomes: states are similar

                                - Bissimulation metric (?) don't get this

                                    - "long term similarity"

                                    - We are given a distance d between distributions

                                    - We define a 1-step (?) dissimilarity between a pair (x,a) and a pair (y,b) as

                                        - $$\\delta(x,a;y,b) = kd(P(.|x,a),P(.|y,b))$$

                                        - d: dissimilarity between transition probabilities in (x,a) and (y,b)

                                        - From $$\\delta$$,we remove the dependence on the actions (?)

                                            - $$d^{\\prime}(x, y)= \\max \\left\\{\\max _{a \\in \\mathcal{A}} \\min _{b \\in \\mathcal{A}} \\delta(x, a ; y, b), \\max _{b \\in \\mathcal{A}} \\min _{a \\in \\mathcal{A}} \\delta(x, a ; y, b)\\right\\}$$

                                            - New distance between states : Dissimilarity of transition probabilities of most similar actions

                                            - Take distance d' and repeat the process to get d''. Keep repeating until distance is the same in two consecutive steps

                    - Continuous output

                        - \[\[Regression\]\]

                            - e.g. Automated driving (steering angle)

                - \[\[Reinforcement Learning\]\]

                    - \[\[Inverse Reinforcemente Learning\]\] (\[\[IRL\]\])

                        - Optimal policy for an MDP can be computed as

                            - $$\\pi^*(x) = \\argmin_{a \\in A} Q^*(x,a)$$

                                - $$= \\argmin_{a \\in A} \[c(x,a) + \\gamma \\sum_{y \\in X} P(y|x,a) J^*(y)\]$$

                        - If someone gives us the optimal policy, can we recover the task (cost function)?

                            - Given optimal policy, for all $$x \\in X$$ and all $$a \\in A$$

                                - $$c_\\pi + \\gamma P_\\pi J^* \\leq c_a + P_aJ^*$$

                                    - ignoring dependence on a

                                - $$(P_\\pi - P_a)J* \\leq 0 $$

                                    - don't fully get this step of equating c_pi and c_a

                                - $$(P_\\pi - P_a)(I - \\gamma P_\\pi)^{-1} c \\leq 0$$

                                - However, if cost = 0, all policies are optimal

                                    - ill-defined problem

                        - Original approaches to IRL select among possible solutions with heuristics

                            - e.g. maximizing difference between value of best and next-best action

                        - Probabilistic approach to IRL

                            - Probabilistic model for the teacher

                                - Don't assume teacher is optimal

                                - Assume that given cost c, it selects each action a in state x with probability

                                    - Question:: Where does this cost come from?

                                    - $$\\pi_{c}(a | x)=\\frac{e^{-\\eta Q_{c}^{*}(x, a)}}{\\sum_{a^{\\prime} \\in \\mathcal{A}} e^{-\\eta Q_{c}^{*}\\left(x, a^{\\prime}\\right)}}$$

                                        - Q*c: optimal Q for cost c

                                        - $$\\eta$$: confidence on expert

                            - Assume independence of examples

                            - Inferring the cost can be done 

                                - using Bayesian inference (assume cost over costs \[?\])

                                    - $$P\[c=c | D\] \\propto \\Pi_{n=1}^N \\pi_c(a_n | x_n) P\[c=c\]$$

                                        - P\[c=c\]: prior

                                - using simple maximum-likelihood

                                    - $$c^* = \\argmax_c \\sum_{n=1}^N \\log \\pi_c(a_c|x_n)$$

                                        - use gradient ascent

                    - What's the fixed point of a function F?

                        - Solution to x = F(x)

                        - Equivalently: H(x) = F(x)-x = 0

                        - "Using stochastic approximation"

                    - Stochastic approximation (detour)

                        - E.g. How to update an average with a new sample?

                            - $$\\bar{x}_{N+1}=\\bar{x}_{N}+\\frac{1}{N+1}\\left(x_{N+1}-\\bar{x}_{N}\\right)$$

                        - Iterative algorithms to compute solution to $$E\[H(x)\] = 0$$

                            - $$x_{n+1}=x_{n}+\\alpha_{n} H\\left(x_{n}\\right)$$

                                - zero-mean noise

                    - MDP

                        - !\[\](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fxiqo%2FvMArHOI3wR?alt=media&token=695b9d81-c142-41e3-a509-3dbdc42001ca)

                    - Computing $$J^\\pi$$

                        - $$J^{\\pi}(x)=c_{\\pi}(x)+\\gamma \\sum_{y \\in \\mathcal{X}} \\mathrm{P}_{\\pi}(y | x) J^{\\pi}(y)$$

                        - Which is equivalent to

                        - $$J^{\\pi}(x)=\\sum_{a \\in \\mathcal{A}} \\pi(a | x)\\left\[c(x, a)+\\gamma \\sum_{y \\in \\mathcal{X}}\\left\[\\mathrm{P}_{a}(y | x)\\right\] J^{\\pi}(y)\\right\]$$

                            - c: we must know the cost

                            - P: we must know the transition probabilities

                    - Computing Q*

                        - $$Q^{*}(x, a)=c(x, a)+\\gamma \\sum_{y \\in \\mathcal{X}} P_{a}(y | x) \\min _{a^{\\prime} \\in \\mathcal{A}} Q^{*}\\left(y, a^{\\prime}\\right)$$

                            - c: we must know the cost

                            - P: we must know the transition probabilities

                    - What if we don't?

                    - Three families of approaches

                        - Model-based methods

                            - !\[\](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fxiqo%2F4bBRH5WjQn?alt=media&token=b4de216b-e085-43fa-81d0-f2e709cb0c31)

                            - Estimating c

                                - Using stochastic approximation

                            - Estimating P

                                - Using stochastic approximation

                            - Once you have estimates for P and c, you can use VI or PI with the model

                                - VI to compute $$J^\\pi$$ or Q*

                                - PI to compute $$\\pi$$*

                            - Does this work?

                                - Model-based approach converges to the true P and c as long as every state,action combo is visited infinitely often.

                            - When to run VI/PI?

                                - In practice, steps of model learning are interleaved with steps of VI/PI 

                            - Model based RL run

                                - Given a sample $$(x_t, c_t, x_{t+1})$$, where the action was selected from $$\\pi$$ 

                                    - Compute P and c

                                        - $$\\bar{P}_{t+1}(y|x_{t}) = \\bar{P}_{t}(y | x_{t})+\\alpha (I(\\bar{x}_{t+1}=y)-\\bar{P}_{t}(y | x_{t}))$$

                                        - $$\\bar{c}_{t+1}(x_{t})=\\bar{c}_{t}\\left(x_{t}\\right)+\\alpha_{t}\\left(c_{t}-\\bar{c}_{t}\\left(x_{t}\\right)\\right)$$

                                    - Compute J

                                        - $$J_{t+1}\\left(x_{t}\\right)=\\bar{c}_{t+1}\\left(x_{t}\\right)+\\gamma \\sum_{y \\in \\mathcal{X}} \\overline{\\mathbf{P}}_{t+1}\\left(y | x_{t}\\right) J_{t}(y)$$

                                        - Update only affected entries

                                - Given a sample $$(x_t, a_t, c_t, x_{t+1})$$

                                    - Compute P and c

                                        - $$\\bar{P}_{t+1}(y|x_{t},a_t) = \\bar{P}_{t}(y | x_{t},a_t)+\\alpha (\\mathbb{I}(\\bar{x}_{t+1}=y)-\\bar{P}_{t}(y | x_{t},a_t))$$

                                            - $$\\alpha$$ ou é dado ou é $$\\frac{1}{N(x_t,a_t)}$$, nº de vezes que par (estado,acção) foi encontrado

                                            - 

                                        - $$\\bar{c}_{t+1}(x_{t},a_t)=\\bar{c}_{t}(x_{t},a_t)+\\alpha_{t}\\left(c_{t}-\\bar{c}_{t}\\left(x_{t},a_t\\right)\\right)$$

                                    - Compute Q

                                        - $$Q_{t+1}\\left(x_{t}, a_{t}\\right)=\\bar{c}_{t+1}\\left(x_{t}, a_{t}\\right)+\\gamma \\sum_{y \\in \\mathcal{X}} \\overline{\\mathbf{P}}_{t+1}\\left(y | x_{t}, a_{t}\\right) \\min _{a^{\\prime} \\in \\mathcal{A}} Q_{t}\\left(y, a^{\\prime}\\right)$$

                                        - Update only affected entries

                        - Value-based methods (\[\[Value-based RL\]\])

                            - Instead of estimating P and c, only estimates values J for each state x

                            - !\[\](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fxiqo%2FKzqrPXaeSO?alt=media&token=009f846d-c6d0-41ef-b8ae-c328bd26f7a4)

                            - Computing $$J^{\\pi}$$

                                - $$J^{\\pi}\\left(x_{t}\\right)=c_{\\pi}(x)+\\gamma \\sum_{y \\in \\mathcal{X}} {\\mathbf{P}}_\\pi (y | x) J^\\pi(y)$$

                                - $$J^\\pi = T_\\pi J^\\pi$$

                                    - $$J^\\pi$$ is a fixed point

                                - For each state x, we can write

                                    - $$J^{\\pi}(x)=\\mathbb{E}_{\\pi}\\left\[\\mathrm{c}+\\gamma J^{\\pi}(\\mathrm{y})\\right\]$$

                                    - $$\\mathbb{E}_{\\pi}\\left\[\\mathrm{c}+\\gamma J^{\\pi}(\\mathrm{y})-J^{\\pi}(x)\\right\] =0$$

                                        - $$J^\\pi$$ is the zero of this function of J

                                - Using the stochastic approximation recipe

                                    - $$J_{t+1}\\left(x_{t}\\right)=J_{t}\\left(x_{t}\\right)+\\alpha_{t}\\left\[c_{t}+\\gamma J_{t}\\left(x_{t+1}\\right)-J_{t}\\left(x_{t}\\right)\\right\]$$

                                    - which can be seen as

                                    - $$J_{t+1}\\left(x_{t}\\right)=J_{t}\\left(x_{t}\\right)+\\alpha_{t}\\left\[\\mathbf{T}_{\\pi} J_{t}\\left(x_{t}\\right)-J_{t}\\left(x_{t}\\right)+\\varepsilon\\right\]$$

                                - (?)Temporal Difference Learning: 

                                    - Question:: How do we go from needing infinite steps to not needing them?

                                    - $$TD(\\gamma)$$

                                        - Given a sample $$(x_t,c_t,x_{t+1})$$ where action is selected from $$\\pi$$

                                        - Compute

                                            - $$z_{t+1}(x)=\\lambda \\gamma z_{t}(x)+\\mathbb{I}\\left(x=x_{t}\\right)$$

                                            - $$J_{t+1}(x_t)=J_{t}(x_t)+\\alpha_{t} z_{t+1}(x)\\left\[c_{t}+\\gamma J_{t}\\left(x_{t+1}\\right)-J_{t}\\left(x_{t}\\right)\\right\]$$

                                            - Matrix form:

                                                - $$\\begin{aligned}&z^{(t+1)}=\\lambda \\gamma z^{(t)}+e_{x_{t}}\\\\&\\boldsymbol{J}^{(t+1)}=\\boldsymbol{J}^{(t)}+\\alpha \\boldsymbol{z}^{(t+1)}\\left(c_{t}+\\gamma \\boldsymbol{J}^{(t)}\\left(x_{t+1}\\right)-J^{(t)}\\left(x_{t}\\right)\\right)\\end{aligned}$$

                                        - Each update uses information from multiple steps

                                        - (?) No looking in the future

                                        - (?) No "long transitions" required 

                                    - What does $$\\lambda$$ mean?

                                        - $$z^{(t)}$$ assigns “blame” for the cost incurred at time step t, ct, to the states visited before t.

                                            - Roughly speaking, the eligibility trace $$z^{(t)}$$ propagates information from the transition observed at time step t, $$(x_t, c_t, x_{t+1})$$ back in time, using this information to update the cost-to-go of states visited before. 

                                        - The scalar λ controls how far in the past such information is propagated. 

                                            - For example, for λ = 0, the

information from time-step t is only used to update the cost-to-go of the state $$x_t$$. On the other hand, as λ → 1, the information at time step t is used to update the cost-to-go of all states visited before time step t.

                                        - The use of eligibility traces (with λ > 0) allows for better use of information, leading to potentially faster

convergence.

                                    - TD(0)

                                        - For $$\\lambda$$ = 0 we get TD(0)

                                        - From "$$J^{\\pi}\\left(x_{t}\\right)=c_{\\pi}(x)+\\gamma \\sum_{y \\in \\mathcal{X}} {\\mathbf{P}}_\\pi (y | x) J^\\pi(y)$$" we get

                                        - $$J_{t+1}(x_t)=J_{t}(x_t)+\\alpha_{t}\\left\[c_{t}+\\gamma J_{t}\\left(x_{t+1}\\right)-J_{t}\\left(x_{t}\\right)\\right\]$$

                                            - Stochastic approximation in the brackets

                            - Computing Q*

                                - $$Q^{*}(x, a)=c(x, a)+\\gamma \\sum_{y \\in \\mathcal{X}} \\mathrm{P}(y | x, a) \\min _{a^{\\prime} \\in \\mathcal{A}} Q^{*}\\left(y, a^{\\prime}\\right)$$

                                    - Random variable y

                                - Can be written as Q* = HQ*

                                    - Q* is a fixed point

                                    - lecture 8

                                - For each pair (x,a), we can write

                                    - $$Q^{*}(x,a)=\\mathbb{E}\[\\mathrm{c}(x,a)+\\gamma \\min_{a' \\in A}Q^*(y,a')\]$$

                                        - Random variable y

                                    - $$\\mathbb{E}_{\\pi}\[\\mathrm{c}(x,a)+\\gamma \\min_{a' \\in A}Q^*(y,a') - Q^*(x,a)\] =0$$

                                        - $$Q^*$$ is the zero of this expression

                                - Using stochastic approximation:

                                - $$Q_{t+1}\\left(x_{t}, a_{t}\\right)=Q_{t}\\left(x_{t}, a_{t}\\right)+\\alpha_{t}\\left\[c_{t}+\\gamma \\min _{a^{\\prime} \\in \\mathcal{A}} Q_{t}\\left(x_{t+1}, a^{\\prime}\\right)-Q_{t}\\left(x_{t}, a_{t}\\right)\\right\]$$

                                    - This is Q learning!

                                    - The expression in the brackets can be seen as HQ - Q + $$\\epsilon$$ so it's also a temporal difference!

                                - \[\[Q-Learning\]\] 

                                    - is also a temporal-difference learning algorithm (although not TD-learning)

                                    - Given a sample $$(x_t, a_t, c_t, x_{t+1})$$

                                        - Compute "$$Q_{t+1}\\left(x_{t}, a_{t}\\right)=Q_{t}\\left(x_{t}, a_{t}\\right)+\\alpha_{t}\\left\[c_{t}+\\gamma \\min _{a^{\\prime} \\in \\mathcal{A}} Q_{t}\\left(x_{t+1}, a^{\\prime}\\right)-Q_{t}\\left(x_{t}, a_{t}\\right)\\right\]$$"

                                    - As long as every state-action pair is visited infinitely often, Q-learning converges to Q*

                            - Methods

                                - \[\[Q-Learning\]\]

                                    - (Q-matrix has expected costs)

                                    - As long as every state-action pair is visited infinitely often, Q-Learning converges to Q*

                                    - Q function

                                        - $$Q = c + \\gamma\\sum\\limits_{y\\in \\Chi} P*\\min\\limits_{a' \\in A}Q $$

                                            - $$Q(x,a) = c(x,a) + \\gamma\\sum\\limits_{y \\in X} P(y|x,a)\\min\\limits_{a'\\in A}Q(y,a')$$

                                            - $$Q_{t+1}(x_t,a_t) = c_{t+1}(x_t,a_t) + \\gamma\\sum\\limits_{y\\in \\Chi} P_{t+1}(y|x_t,a_t)\\min\\limits_{a' \\in A}Q_t(y,a')$$

                                    - Q-update towards Q*

                                        - Given a sample $$(x_t,a_t,c_t,x_{t+1})$$

                                        - $$Q_{t+1}(x_t,a_t) = Q_{t}(x_t,a_t) + \\alpha_t \\big\[ c_t + \\gamma \\min\\limits_{a' \\in A} Q_t(x_{t+1},a') - Q_t(x_t,a_t) \\big\]$$

                                    - Learning Policy

                                        - Q-learning is independent of learning policy

                                        - learns Q-values for the optimal policy

                                - On-policy updates (\[\[SARSA\]\])

                                    - What about the Q-values for the actual learning policy?

                                        - $$Q^{\\pi}(x, a)=\\mathbb{E}\\left\[c(x, a)+\\gamma Q^{\\pi}\\left(\\mathrm{y}, \\mathrm{a}^{\\prime}\\right)\\right\]$$

                                        - y an a' are random variables

                                    - Using stochastic approximation recipe

                                        - Given a sample $$(x_t,a_t,c_t,x_{t+1},a_{t+1})$$ compute

                                        - $$Q_{t+1}\\left(x_{t}, a_{t}\\right)=Q_{t}\\left(x_{t}, a_{t}\\right)+\\alpha_{t}\\left\[c_{t}+\\gamma Q_{t}\\left(x_{t+1}, a_{t+1}\\right)-Q_{t}\\left(x_{t}, a_{t}\\right)\\right\]$$

                                        - **SARSA**

                                            - State

                                            - Action

                                            - Reinforcement (cost)

                                            - next State

                                            - next Action

                                - Q-Learning vs SARSA

                                    - **Q-Learning** is **off-policy**

                                        - Learns the values of the optimal policy while following another

                                    - **SARSA **(like TD) is **on-policy**

                                        - Learns the values of the policy that it follows

                                    - For SARSA to learn Q* it must be combined with policy improvement

                                        - For example $$\\epsilon$$-greedy 

                                    - SARSA often leads to more stable updates

                                        - The cliff example. Q hugs the cliff (can fall while exploring). SARSA stays away.

                            - Exploration vs Exploitation tradeoff (ExE)

                                - Visiting every state-action pair a large number of times is intractable for most problems.

                                - The agent needs to balance Exploration and Exploitation

                                    - Exploration

                                        - Trying new actions (or less experienced actions)

                                    - Exploitation

                                        - Using knowledge already acquired to select better actions

                                - Heuristics for ExE

                                    - $$\\epsilon$$-greedy

                                        - Agent selects random action with p=$$\\epsilon$$ (exploration)

                                        - Agent selects greedy action (smallest Q-value) with $$p=1-\\epsilon$$

                                        - $$\\epsilon$$ may decay over time

                                    - Boltzmann policy

                                        - Agent selects each action $$a \\in A $$ with probability

                                            - $$\\pi(a | x)=\\frac{e^{-\\eta Q_{t}(x, a)}}{\\sum_{a^{\\prime} \\in \\mathcal{A}} e^{-\\eta Q_{t}\\left(x, a^{\\prime}\\right)}}$$

                                            - $$\\eta$$ controls the exploration and may grow with time

                                    - Optimistic initialization

                                        - All Q-values initialized at 0 or negative

                                        - Agent always selects the greedy action (in case of tie, it randomizes)

                                            - Initially all action are equally good -> agent randomizes (exploration)

                                            - As more knowledge is available, suboptimal actions become less interesting and the agent approaches the optimal (exploitation)

                            - Large domains

                                - Function approximation 

                                    - Instead of allowing arbitrary functions, methods restrict to pre-specified families of function

                                    - Linear approximation

                                        - Each state is described as a vector $$\\phi(x)$$ of features

                                        - J and Q are represented as linear combinations of features

                                            - $$J^{\\pi}(x) \\approx \\phi^{\\top}(x) \\boldsymbol{w}$$

                                            - $$Q^{*}(x, a) \\approx \\phi^{\\top}(x, a) \\boldsymbol{w}$$

                                        - Methods compute best weights for the combinations

                                    - TD($$\\lambda$$) with linear FA

                                        - Given a sample $$(x_t,a_t,c_t,x_{t+1})$$ where action is selected from $$\\pi$$

                                        - $$\\boldsymbol{z}_{t}=\\lambda \\gamma \\boldsymbol{z}_{t-1}+\\boldsymbol{\\phi}\\left(x_{t}\\right)$$

                                        - $$\\boldsymbol{w}_{t+1}=\\boldsymbol{w}_{t}+\\alpha_{t} \\boldsymbol{z}_{t+1}\\left\[c_{t}+\\gamma J_{t}\\left(x_{t+1}\\right)-J_{t}\\left(x_{t}\\right)\\right\]$$

                                        - $$J_t(x) = \\phi^T(x)w_t$$

                                        - retains convergence guarantees

                                    - Q-learning with with linear FA

                                        - Given a sample $$(x_t,a_t,c_t,x_{t+1})$$ compute

                                            - $$\\boldsymbol{w}_{t+1}=\\boldsymbol{w}_{t}+\\alpha_{t} \\boldsymbol{\\phi}(x, a)\\left\[c_{t}+\\gamma \\min _{a^{\\prime} \\in \\mathcal{A}} Q_{t}\\left(x_{t+1}, a^{\\prime}\\right)-Q_{t}\\left(x_{t}, a_{t}\\right)\\right\]$$

                                        - Where $$Q_t(x,a) = \\phi^T(x,a)w_t$$

                                        - doesn't retain convergence guarantees

                                    - SARSA with linear FA

                                        - Given a sample $$(x_t,a_t,c_t,x_{t+1},a_{t+1})$$ compute

                                        - $$\\boldsymbol{w}_{t+1}=\\boldsymbol{w}_{t}+\\alpha_{t} \\boldsymbol{\\phi}(x_t, a_t)\\left\[c_{t}+\\gamma Q_{t}\\left(x_{t+1}, a_{t+1}\\right)-Q_{t}\\left(x_{t}, a_{t}\\right)\\right\]$$

                            - Batch RL

                                - The methods seen so far are __online__

                                    - Agent samples, immediately updates

                                - Alternatively, agent could collect a big batch of data and use

it to learn

                                    - Data is better used

                                    - Can take advantage of supervised learning

                                    - More stable (convergence problems “solved”)

                                - Batch RL with NNs

                                    - dataset is a batch of transitions $$\\{ (x_1,a_1),(c1 + \\gamma min_{a \\in A}Q_t(x_1',a)), ... \\}$$

                                        - input and target cost?

                                    - $$\\mathcal{E}=\\sum_{n=1}^{N}\\left(c_{n}+\\gamma \\min _{a \\in \\mathcal{A}} Q_{t}\\left(x_{n}^{\\prime}, a\\right)-Q\\left(x_{n}, a_{n}\\right)\\right)^{2}$$

                                    - Qt is held fixed for several iterations (in a **target network**)

                                    - Samples are not ordered, but selected randomly from a

buffer (**experience replay**)

                                    - $$J^\\pi$$ can be computed similarly

                            - Fitted Q-iteration

                                - !\[\](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fxiqo%2FUcNMGbEXVQ?alt=media&token=5a9e8f81-a558-447c-af64-d612d7c5df16)

                            - Fitted value-iteration

                                - !\[\](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fxiqo%2FXQNeb9O8B5?alt=media&token=1c57c858-2483-4ea8-aa18-81711b65905c)

                        - Policy-based methods

                            - !\[\](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fxiqo%2FypUBFRaEmI?alt=media&token=eb13cecf-892f-45de-9195-97521b983abe)

                            - Why policy-based RL?

                                - … value-based methods are not guaranteed to converge

with approximations

                                -  … quality of the result depends on the quality of

approximation

                                - ... even if approximation is good, resulting policy may be bad

                            - What is policy-based RL?

                                - Instead of approximating value, we approximate a policy

                                - Select the best policy within the approximation

                            - What is the best policy?

                                - Considering initial distribution $$\\mu_0$$

                                - $$V(\\pi) = E_{\\mu_0}\[ J^\\pi (x_o)\]$$

                                    - $$= \\sum_{x \\in X} \\mu_0 (x) J^\\pi (x_0)$$

                                - Then, $$\\pi_1$$ is better than $$\\pi_2$$ if $$V(\\pi_1) < V($$\\pi_2$$)$$

                            - How to improve policy?

                                - Gradient descent

                                    - More efficient than hill climbing or evolutionary algorithms

                                    - Exploits MDP structure better

                            - Policy gradient

                                - We consider a family of parameterized policies {$$\\pi_\\theta$$}

                                    - $$\\pi_\\theta$$ is the parameter of the policy

                                - Approaches

                                    - Finite differences

                                        - $$\\frac{\\partial V}{\\partial \\theta_{n}} \\approx \\frac{V\\left(\\theta+\\varepsilon_{n}\\right)-V(\\theta)}{\\varepsilon_{n}}$$

                                        - Simple to compute

                                        - Works on non-differentiable policies

                                        - Noisy and slow to learn

                                        - Requires evaluation V

                                    - Analytical

                                        - Assume we know $$\\Delta_\\theta \\pi$$

                                - Policy gradient theorem

                                    - The policy gradient is given by

                                    - $$\\nabla_{\\theta} V(\\theta)=\\mathbb{E}_{\\mu_{\\theta}, \\pi_{\\theta}}\\left\[\\nabla_{\\theta} \\log \\pi_{\\theta}(\\mathrm{a} | \\mathrm{x}) Q^{\\pi_{\\theta}}(\\mathrm{x}, \\mathrm{a})\\right\]$$

                                        - Must still compute $$Q^\\pi$$

                                    - where $$\\mu_0$$ is a long-term distribution over X

                            - \[\[REINFORCE\]\] Algorithm

                                - Init $$\\theta$$

                                - Collect trajectory $${...,x_T,a_T,c_T}$$ using $$\\pi_\\theta$$

                                - For each t=0,...,T

                                    - Update $$\\theta \\leftarrow \\theta - \\alpha \\Delta \\log \\pi (a_t|x_t) \\sum_{r=t}^T \\gamma^{\\tau + t} c_\\tau $$

                                        - That sum is an estimate of $$\\gamma^t Q^\\pi$$

                                - REINFORCE is significantly better than finite difference approach

                                - However, gradient estimates have large variance

                            - \[\[Actor-Critic\]\] architecture

                                - !\[\](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fxiqo%2FVAAi8BWeP2?alt=media&token=d0cd8646-9266-4507-8474-84d975d8e7d7)

                                - Actor maintains/runs the policy

                                - Critic computes Q

                                - These methods provide satisfactory solutions for both the actor and the critic

                            - Policy gradient theorem II

                                - Given the compatible features/basis functions

                                    - $$\\phi(x, a)=\\nabla_{\\theta} \\log \\pi_{\\theta}(a | x)$$

                                        - if we approximate $$Q^\\pi$$ using the features $$\\phi$$, we recover the gradient

                                - let 

                                    - $$Q_{\\boldsymbol{w}}(x, a)=\\boldsymbol{w}^{\\top} \\phi(x, a)$$

                                - with

                                    - $$\\boldsymbol{w}=\\operatorname{argmin} \\mathbb{E}_{\\mu_{\\theta}, \\pi_{\\theta}}\\left\[\\left(Q^{\\pi_{\\theta}}(\\mathrm{x}, \\mathrm{a})-Q_{\\boldsymbol{w}}(\\mathrm{x}, \\mathrm{a})\\right)^{2}\\right\]$$

                                - Then,

                                    - $$\\nabla_{\\theta} V(\\theta)=\\mathbb{E}_{\\mu_{\\theta}, \\pi_{\\theta}}\\left\[\\nabla_{\\theta} \\log \\pi_{\\theta}(\\mathrm{a} | \\mathrm{x}) Q_{\\boldsymbol{w}}(\\mathrm{x}, \\mathrm{a})\\right\]$$

                - \[\[Unsupervised Learning\]\]

            - No free lunch theorem in machine learning

                - "For every task in which your decision rule is great, there's another task in which it does terribly"

                - We build our algorithms around **assumptions**

                    - Assumptions translate knowledge about the problem (which hypothesis are most likely)

                    - Assumptions greatly reduce search space

                - Inductive bias

                    - Assumptions about the input-output relation allow us to **generalize**

                    - \[\[Bias-variance tradeoff\]\]

            - Some nomenclature

                - Set X of possible situations: **Input space**

                - Set A of possible actions: **Output space**

                - Task

                    - Decision rule (policy): **classifier**

                        - **Deterministic **$$\\pi : X \\rightarrow A$$ 

                        - **Stochastic **$$\\pi : X \\rightarrow \\Delta (A)$$ 

                - Experience

                    - Dataset of examples $$D = {(x_o,a_o),...(x_M,a_M)}$$

                    - (x,a) pairs generated from an unknown distribution $$\\mu_D$$

                - Performance

                    - Expected **cost **or **risk **of policy $$\\pi$$

                        - $$L(\\pi) = E_{\\mu_D}\[l(x,a;\\pi)\] = \\sum_{x,a} l(a,a;x)\\mu_D(x,a)$$

                            - l(x,a; π): cost of π given correspondence (x,a)

                                - (?) Cost of the policy? Shouldn't the cost always be the same for a pair?

                    - Sometimes Q can be computed from a simpler loss function

                        - $$l(x,a; \\pi) = E_\\pi\[d(â,a)\] = \\sum_â d(â,a)\\pi(â|x) $$

                    - The goal of the agent is to compute a policy $$\\pi^* = \\argmin_\\pi L(\\pi)$$

            - Problem: Given a policy, we want to compute L. Should we evaluate it in all (x,a) situations?

                - Alternative 1: **__Empirical risk minimization__**

                    - Evaluate the policy in the provided examples

                    - $$L(\\pi) \\approx L'_N(\\pi) = \\frac{1}{N} \\sum_{n=1}^{N} l(x_n,a_n;\\pi)$$

                        - using ' instead of ^ because latex

                - Alternative 2: **__Inference on the data distribution__**

                    - Estimate distribution $$\\mu_D(x,a)$$ from the examples

                    - Select policy $$\\pi^* (x) = \\argmin_â \\sum_a \\mu'(x,a)d(â,a)$$

                        - "using ' instead of ^ because latex"

            - Inductive Learning

                - Assumption: If we learn from a sufficiently large set of examples, we will do well in the actual task

            - {{embed: ((8BL5bwXkT))}}

            - Exploration vs Exploitation - \[\[Multi-armed bandit\]\]

                - Weighted majority algorithm (not very important) 

                    - Given a set of N "predictors" and $$\\eta \\lt 1/2$$

                    - Initialize predictor weights $$w_o(n) = 1, n=1,...,N$$

                    - Make prediction based on (weighted) majority vote

                    - Update weights of all wrong predictors as $$w_{t+1}(n) = w_t(n)(1-\\eta)$$

                - Sequential prediction

                    - At each time step t

                        - agent selects action

                        - nature selects cost function

                        - nature disclose cost function

                    - Select action proportionally to its confidence 

                        - Again, a confidence level is defined for each action

                        - $$p_{t}(a)=\\frac{w_{t}(a)}{\\sum_{a^{\\prime} \\in \\mathcal{A}} w_{t}\\left(a^{\\prime}\\right)}$$

                    - When cost is revealed, update confidence based on action cost

                        - higher cost, less confidence

                        - $$w_{t+1}(a)=w_{t}(a) e^{-\\eta c_{t}(a)}$$

                    - Then, at each step t (this was in the pp but I don't get the difference between this and the point when the cost is revealed)

                        - $$w_t(a) = e^{-\\eta \\sum_{\\tau = 0}^{t-1} c_\\tau (a)}$$

                    - Regret

                        - $$R_{T}=\\mathbb{E}\\left\[\\sum_{t=0}^{T-1} c_{t}\\left(a_{t}\\right)\\right\]-\\min _{a \\in \\mathcal{A}} \\sum_{t=0}^{T-1} c_{t}(a)$$

                        - Comparison between our total expected cost with that of the best action (in hindsight)

                        - How much regret?

                            - Initial weights: N

                            - Total confidence after T steps is smaller than

                                - $$N e^{-\\eta E\[\\sum_{t=0}^{T-1} c_t (a_t)\]_\\rho}$$

                            - Comparing with the best action (in hindsight):

                                - $$N e^{-\\eta E\[\\sum_{t=0}^{T-1} c_t (a_t)\]_\\rho} \\geq \\min_{a \\in A} e^{-\\eta \\sum_{t=0}^{T-1} c_t (a)}$$

                            - Finally

                                - $$R_t \\leq \\frac{\\log N}{\\eta} + \\frac{\\rho}{\\eta}$$

                            - Selecting $$\\eta$$ properly we get the final bound

                                - $$R_T \\leq \\sqrt{\\frac{T}{2}\\log N}$$

                    - Exponentially Weighted Averager (EWA)

                        - EWA is an algorithm for sequential prediction

                            - Given set of N actions and $$\\eta \\gt 0$$

                            - Init weights (confidence) to $$w_o(a) = 1, a \\in A$$

                            - Select action proportionally to confidence 

                                - $$p_t(a) = \\frac{w_t(a)}{\\sum_{a' \\in A} w_t(a')}$$

                            - Update weights of all actions as $$w_{t+1}(a) = w_{t}(a)e^{-\\eta c_t(a)}$$

                        - Questions

                            - Does EWA make assumptions about the process of cost selection?

                                - Makes no assumptions on process of cost selection (can be adversarial)

                            - Do we observe the complete costs?

                                - Yes

                            - Regret bound of EWA?

                                - $$R_T \\leq \\sqrt{\\frac{T}{2} logN} $$

                                    - N: number of predictors/actions

                                    - T: timesteps

                            - Average regret per step?

                                - Goes to 0 as T increases (bc of sublinear dependency)

                - Types of \[\[Multi-armed bandit\]\]s

                    - Stochastic bandits

                        - Cost $$c_t$$ selected by Nature and drawn from a fixed and unknown distribution. 

                        - UCB algorithm (Upper confidence bound)

                            - Does UCB observe complete costs?

                                - Only observes cost for selected actions (bandit problem)

                            - Actually minimizes lower confidence bound (name is historical)

                            - Assumptions about costs?

                                - Costs follow an unknown (but fixed) distribution

                            - Designed for what type of bandit problems?

                                - stochastic bandit problems

                            - Is selection heuristic deterministic?

                                - yes

                            - Algorithm

                                - Execute each action once

                                - $$a^* =  argmin \\space ĉ(a) - \\sqrt{\\frac{2 \\log t}{N_t(a)}}$$

                                    - ĉ: average cost

                                    - second term represents confidence interval

                            - Regret bound of UCB?

                                - $$R_T \\leq \\sqrt{CNT\\log T}$$

                                    - C: Constant

                                    - N: nr of actions

                                    - T: timesteps

                            - Evaluating UCB performance

                                - $$R_{T}=\\mathbb{E}\\left\[\\sum_{t=0}^{T-1} c_{t}\\left(a_{t}\\right)-\\min _{a \\in \\mathcal{A}} \\sum_{t=0}^{T-1} c_{t}(a)\\right\]$$

                                - To measure performance, we compare its total expected cost to the optimal total expected cost

                                - $$R_{T} = \\sum_{a \\in A} E\[N_T(a)\]c(a) - Tc(a*)$$

                                    - $$N_T$$: Expected n of times that a is selected

                                    - c(a*): expected cost of the optimal action

                    - Adversarial bandits

                        - Assume that cost $$c_t$$ may be selected adversarially

                        - EXP3 algorithm

                            - “EXPonentially weighted algorithm for EXPloration and

EXPloitation”

                            - Designed for Adversarial bandit problems

                            - Selection heuristic is stochastic in order to avoid being exploited by nature

                            - Differences from EWA?

                                - We do not observe cost for all actions, so we can only update weight for current action

                                - What will happen to actions experimented more often?

                                    - More updates, will unbalance weights

                                - To compensate for the above, how should we update?

                                    - $$w_{t+1}(a_t) = w_t(a_t)e^{\\eta \\frac{c_t(a_t)}{p_t(a_t)}}$$

                                    - stochastically

                                    - divide cost by probability of selecting the action

                            - Algorithm

                                - Given set of N actions and $$\\eta \\gt 0$$

                                - Init weights (confidence) to $$w_o(a) = 1, a \\in A$$

                                - Select action proportionally to confidence 

                                    - $$p_t(a) = \\frac{w_t(a)}{\\sum_{a' \\in A} w_t(a')}$$

                                - Update weight function of action a_t as

                                    - $$w_{t+1}(a_t) = w_t(a_t)e^{\\eta \\frac{c_t(a_t)}{p_t(a_t)}}$$

                            - Evaluating EXP3 performance

                                - Compare total expected cost with that of the best action (in hindsight)

                                - {{embed: ((7lHRfXwKF))}}

                            - Regret bound of EXP3?

                                - $$R_T \\leq \\sqrt{2TN\\log N}$$

                                - sublinear in T and N

                - Overview of ExE algorithms

                    - No assumptions about the cost process; observation of complete costs

                        - EWA

                        - "$$R_T \\leq \\sqrt{\\frac{T}{2}\\log N}$$"

                    - Cost sampled from distribution; observation of single-action cost (bandit setting) 

                        - UCB

                        - "$$R_T \\leq \\sqrt{CNT\\log T}$$"

                    - No assumptions about the cost process; observation of single-action cost (bandit setting)

                        - EXP3

                        - "$$R_T \\leq \\sqrt{2TN\\log N}$$"

                - Monte Carlo Tree Search

                    - Application of UCB

                    - Very efficient planning method for large domains

                    - Idea:

                        - Build a search tree incrementally

                        - Use sampling to compute node values

                    - Four stages

                        - SELECTION

                            - Select node to expand

                            - Most standard selection method?

                                - UCB (resulting MCTS alg is called UCT)

                                - At each node, selects node minimizing

                                    - $$Q(i) - c\\sqrt{\\frac{\\log(t)}{N(i)}}$$

                                - 

                        - EXPANSION

                            - Expand it

                        - SIMULATION

                            - Simulate the process starting from that node

                        - BACK-PROP

                            - Back-propagate the resulting value

        - {{\[\[DONE\]\]}}(Still don't really get Bissimulation nor IRL) P18 Learning and Decision Making 

            - Approaches to learning

                - Symbolic

                    - Learn rules (DT)

                    - Assumes classes can be described by small number of rules

                - Probabilistic

                    - Learn probabilities (LR,NB)

                    - Assumes classes can be described probabilistically

                - Similarity-based

                    - Learn by similarity (\[\[kNN\]\], SVM)

                    - Assumes classes can be described "geometically", in the same space

                - Neural

                    - Brain-like (NN)

                    - Assumes classes can be described geometrically by bending the space

        - {{\[\[DONE\]\]}} (Still questions about temporal difference) P20 Reinforcement Learning

            - {{\[\[DONE\]\]}} P19 Model-based methods

        - {{\[\[DONE\]\]}} P22 Policy-Gradient

            - "Policy gradient"

\- \[Exercises (without solutions)\](https://fenix.tecnico.ulisboa.pt/downloadFile/563568428782685/Exercises.pdf)

\- \[PADI Powerpoints\](https://fenix.tecnico.ulisboa.pt/disciplinas/PADInt.7/2019-2020/1-semestre/material-de-apoio)