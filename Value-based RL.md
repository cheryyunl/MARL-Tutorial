# Value-based RL (Deep RL)

## Q-Learning

* Value iteration process：

$$
\begin{array}{l}{Q\left(S_{t}, A_{t}\right) \leftarrow Q\left(S_{t}, A_{t}\right)+\alpha\left(R_{t+1}+\lambda \max _{a} Q\left(S_{t+1}, a\right)-Q\left(S_{t}, A_{t}\right)\right)} \\ {S \leftarrow S^{\prime}}\end{array}
$$

* Policy generation: $\epsilon-greedy$ policy
  $$
  \pi\left(S_{t+1}\right)=\arg \max _{a} Q\left(S_{t+1}, a\right)
  $$

* Converge to optimal $Q^*$ with Q-table



```python

```



## Deep Q-Network

* Curse of space dimensionality
* Value Function Approximation



![model](C:\Users\v-yolia\Documents\GitHub\MARL-Tutorial\model.png)

### Q-Network

* Input: data sample with labels

  

* Loss function
  $$
  I=\left(r+\gamma \max _{a^{\prime}} Q\left(s^{\prime}, a^{\prime}, \mathbf{w}^{-}\right)-Q(s, a, \mathbf{w})\right)^{2}
  $$
  
* Output:



## Reference

