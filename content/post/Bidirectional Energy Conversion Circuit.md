---
title: Bidirectional Energy Conversion Circuit
date: 2019-03-30
categories:
- Technology
tags:
- circuit design
- nonlinear dynamics
---

<p class="description"></p>

<img src="https://s2.ax1x.com/2019/04/16/AxDWx1.png" alt="" style="width:80%" />

{% centerquote %}A brief introduction of a bidrectional energy conversion circuit towards the dual task of energy harvesting and vibration exciting, with a nonlinear system demo.{% endcenterquote %}


<!-- more -->

### Motivation
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;With the developement of power electronics, it is not rare to find different types of power conversion ciruits such as bidrectional or multidirectional energy conversion solutions, which mainly use active mosfets to guide the energy flow in the topologies. Based on the similar concept, we have established a bidirectional energy conversion circuit (BECC) in the piezoelectric energy harvesting area, which realizes the second function of vibration exciting besides the conventional function of energy harvesting. With the entirely new control logic, it has some applications such as self-powered transmitter for nondestructive damage evaluation and orbit jumps functions for nonlinear energy harvesting systems.

<img src="https://s2.ax1x.com/2019/04/16/Ax8CcQ.png" width = "300" height = "200" alt="The prototype of BECC solution" align=center />



### Layout of BECC
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The circuit topology of BECC is consist of three bais flip action guiding path for guiding the energy flow from the mechanical vibration into the electrical energy stored into the storage capacitor, and this capacitor is also used as the bias flip voltage source for building the voltages stairs for several bias flip action at the current crossing zero point, which enables the same phase between the piezoelectric voltage and current in order to maximize the harvested power. As for the vibration function, this storage capacitor could also be used as a stable voltage source for creating an opposite phase between the piezoelectric voltage and current, which means the electrical energy is boosted back into the mechanical structure to excite the oscillator for much large vibration amplitude.

### A Demo in Nonlinear Energy Harvesting System


 <img src="https://s2.ax1x.com/2019/04/16/Ax891g.png" width = "600" height = "400" alt="Experimental setup" align=center />


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;It can been seen from the experiment setup that a piezoelectric cantiliver beam is amounted at the vibration base, with two diploe-dipole configuration magnets to introduce the nonlinear magnetic force for the system. The piezoelectirc patch is connected with the BECC board, controlled by the on-board MSP430 controller. From the video below, the oscillator was firstly at the low-energy orbit and the mechanical energy was accumulated at the storage capacitor, when the voltage was enough to excite the oscillator, the circuit was shifted into vibration exciting mode, under which the energy would flow back to the mechanical domain. Therefore, it can be observed that the vibration amplitude was increased and the system had crossed the energy barrier and stablized at the high energy oribt, in this case we can harvested more energy with the advantage of high energy orbit.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If you want to know more about the piezoelectric energy harvesting and nonlinear vibration system, please refer to [METAL](http://www.google.com/ "METAL") and [Wiki](https://en.wikipedia.org/wiki/Nonlinear_system "Wiki").

<div style="text-align:center;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/__6h-lOehkw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>



## Reference
>B. Zhao, J. Wang, J. Liang, and W.-H. Liao, “A bidirectional energy conversion circuit for piezoelectric energy harvesting and vibration exciting purposes,” in Active and Passive Smart Structures and Integrated Systems XII, 2019, vol. 10967, p. 109670J.

<hr />
