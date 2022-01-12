# 3.1. Dendrites and Synapses

![image-20220104214633420](C:\Users\maxyc\AppData\Roaming\Typora\typora-user-images\image-20220104214633420.png)

![image-20220104214655469](C:\Users\maxyc\AppData\Roaming\Typora\typora-user-images\image-20220104214655469.png)

# 3.2. Synaptic short-term plasticity

$$
I^{syn}(t) = g_{syn}(t)\cdot (u-E_{syn})\\
C\cdot\frac{du}{dt} = -\sum g_i(u-E_i) - I^{syn}(t)
$$

STF, STD, LTP, LTD

Fraction of filled release sites
$$
\frac{dP_{rel}}{dt} = - \frac{P_{rel}-P_0}{\tau_P} - f_D\cdot P_{rel}\cdot\sum_k \delta(t-t^k)\\
\tilde{g}_{syn} = c\cdot P_{rel}\\
g_{syn}(t) = \tilde{g}_{syn}e^{-(t-t_k)/\tau}\Theta(t-t_k)\\
BTW,\ \frac{dP_{rel}}{dt} = - \frac{P_{rel}-P_0}{\tau_P} + f_F\cdot P_{rel}\cdot\sum_k \delta(t-t^k)
$$

# 3.3. Dendrites as Cable

$$
I(t,x) = C\cdot \frac{d}{dt}U(t,x) + \sum_{ion}I_{ion}(t,x) \\
Besides,\ I(t,x) = I^{ext}(t,x) + \frac{u(t, x-dx)-u(t,x)}{R_l}-\frac{u(t, x)-u(t,x+dx)}{R_l}\\
C\cdot \frac{d}{dt}U(t,x) + \sum_{ion}I_{ion}(t,x) -I^{ext}(t,x)= \frac{u(t, x-dx)+u(t,x+dx)-2u(t,x)}{R_l}
$$

![image-20220104231027997](C:\Users\maxyc\AppData\Roaming\Typora\typora-user-images\image-20220104231027997.png)
$$
\frac{d^2}{dx^2}u(t,x) = c\cdot r_L \frac{d}{dt}u(t,x)+r_L\sum_{ion}i_{ion}(t,x)-r_Li^{ext}(t,x)\\
where\ R_L = r_Ldx,\ C=c\cdot dx
$$

# 3.4. Cable Equation

passive dendrite

![image-20220104234105332](C:\Users\maxyc\AppData\Roaming\Typora\typora-user-images\image-20220104234105332.png)



# 3.5. Compartmental models

![image-20220104234418413](C:\Users\maxyc\AppData\Roaming\Typora\typora-user-images\image-20220104234418413.png)

