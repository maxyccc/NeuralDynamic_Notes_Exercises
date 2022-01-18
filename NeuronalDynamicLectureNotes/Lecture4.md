# 4. 2D HH model

$$
C\frac{du}{dt} = -g_{Na}[m(t)]^3h(t)(u(t)-E_{Na})-g_K[n(t)]^4(u(t)-E_K)-g_l(u-E_l)+I(t)\\
C\frac{du}{dt} = -g_{Na}m_0(u)^3(1-w)(u-E_{Na})-g_K[\frac{w}{a}]^4(u-E_K)-g_l(u-E_l)+I(t)\\
where\ \frac{dw}{dt}= -\frac{w-w_0(u)}{\tau_{eff}(u)}\\
$$

In conclusion 
$$
C\frac{du}{dt} = f(u(t), w(t))+I(t)\\
\frac{dw}{dt} = g(u(t),w(t))
$$

# 4.1 Detour exploiting similarities

features: 

1. dynamic m is fast than n/h
2. n & h dynamic are similar

$$
\tau\frac{du}{dt} = F(u(t), w(t))+RI(t)\\
\tau_w\frac{dw}{dt} = g(u(t),w(t))
$$

# 4.2. Nullclines,

![image-20220115205827943](C:\Users\maxyc\AppData\Roaming\Typora\typora-user-images\image-20220115205827943.png)

![image-20220115210218522](C:\Users\maxyc\AppData\Roaming\Typora\typora-user-images\image-20220115210218522.png)

![image-20220115211046898](C:\Users\maxyc\AppData\Roaming\Typora\typora-user-images\image-20220115211046898.png)



# 4.3 flow analysis

![image-20220115212550710](C:\Users\maxyc\AppData\Roaming\Typora\typora-user-images\image-20220115212550710.png)

![image-20220115214409817](C:\Users\maxyc\AppData\Roaming\Typora\typora-user-images\image-20220115214409817.png)

# 4.4. Type I and II Neuron Models

hopf bifurcation

firing threshold: stable point, (saddle point), unstable point

# 4.5. Nonlinear IF model

![image-20220117004442059](C:\Users\maxyc\AppData\Roaming\Typora\typora-user-images\image-20220117004442059.png)

