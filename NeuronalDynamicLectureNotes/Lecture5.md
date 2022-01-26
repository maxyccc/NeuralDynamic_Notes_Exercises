# 5 Noise, Variability

- intrinsic noise
- network noise

# 5.3. Rate coding

stochastic firing & Poisson model

Homogeneous Poisson model: constant rate 
$$
Pr(firing\ in\ bin) = P_F=\rho_0 \Delta t\\
\rho_0 = \lim_{dt\rightarrow 0}\frac{P_F}{dt}\\
$$
​		survival equation

<img src="C:\Users\maxyc\AppData\Roaming\Typora\typora-user-images\image-20220126210335434.png" alt="image-20220126210335434" style="zoom: 67%;" />



Inhomogeneous Poisson Process



<img src="C:\Users\maxyc\AppData\Roaming\Typora\typora-user-images\image-20220126211043302.png" alt="image-20220126211043302" style="zoom: 50%;" />

# 5.4. Stochastic spike arrival

![image-20220126212910434](C:\Users\maxyc\AppData\Roaming\Typora\typora-user-images\image-20220126212910434.png)
$$
<S(t)> = <\sum_{k=1}^K\sum_f \delta(t-t_k^f)> = K\rho_0
$$
<img src="C:\Users\maxyc\AppData\Roaming\Typora\typora-user-images\image-20220126213300327.png" alt="image-20220126213300327" style="zoom:50%;" /><img src="C:\Users\maxyc\AppData\Roaming\Typora\typora-user-images\image-20220126213717293.png" alt="image-20220126213717293" style="zoom:50%;" />

<img src="C:\Users\maxyc\AppData\Roaming\Typora\typora-user-images\image-20220126213949286.png" alt="image-20220126213949286" style="zoom:50%;" />

- Membrane potential fluctuations

  

![image-20220126214828806](C:\Users\maxyc\AppData\Roaming\Typora\typora-user-images\image-20220126214828806.png)

![image-20220126215146626](C:\Users\maxyc\AppData\Roaming\Typora\typora-user-images\image-20220126215146626.png)

# 5.5. Stochastic Spiking Firing in LIF models

![image-20220126220133805](C:\Users\maxyc\AppData\Roaming\Typora\typora-user-images\image-20220126220133805.png)

<img src="C:\Users\maxyc\AppData\Roaming\Typora\typora-user-images\image-20220126220436033.png" alt="image-20220126220436033" style="zoom: 67%;" />

