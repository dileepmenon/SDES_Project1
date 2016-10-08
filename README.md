#SDES Course Project1- Mass spring damper

This is a python based project to solve the ODE of a mass spring damper system and study the position and velocity of the system as a function of time.
<br />
![](http://blogs.mathworks.com/images/loren/2013/MassSpringDamper.png)
<center>**Fig 1.** Schematic of mass spring damper system</center>
<br />
<br />

Consider a spring mass damper system of mass(m), spring constant(k) and damping factor(c) as shown in Fig 1.

From Newtons Law,
$$ \Sigma f = ma$$<br />

$$-kx-c\dfrac{dx}{dt} = m\dfrac{d^2x}{dt^2}$$

rearranging

$$m\dfrac{d^2x}{dt^2} + c\dfrac{dx}{dt} + kx = 0$$

dividing by m

$$\dfrac{d^2x}{dt^2} + \dfrac{c}{m}\dfrac{dx}{dt} + \dfrac{k}{m}x = 0$$ 

Let $\omega_o = \sqrt{\frac{k}{m}} $, be the natural frequency of the system and $\zeta = \frac{c}{2\sqrt{km}}$, be the damping ratio, we get

$$\dfrac{d^2x}{dt^2} + 2\omega_o \zeta \dfrac{dx}{dt} + \omega_o^2 x = 0$$ 
        




