---
title: Impedance matching for broadband PEH systems
date: 2018-03-30
categories:
- Technology
tags:
- energy harvesting
math = true
---

<p class="description"></p>

<img src="https://s2.ax1x.com/2019/07/22/eiF3jI.jpg" alt="" style="width:50%" />

{% centerquote %}The influence of the coupling intensities on PEH systems.{% endcenterquote %}


<!-- more -->

### Motivation
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; For piezoelectric energy harvesting (PEH) systems, over the past decade, there have been tremendous designs for the self-powered sensors targets. Typically we use a weakly coupled PEH system to minimize the influence of electro-mechanical coupling effect, however, it worth noting that in the real applications that the miniaturized structures often means the strong coupling intensity which will influence the performance of the power sources, i.e., such as mechanical oscillators or cantilever beams. Therefore, it is necessary to address the effect of different coupling intensities to execute the impedance matching method for maximizing the harvested power as well as the robust designs for various power sources. 



### Impedance Matching
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Base the previous study on phase variable technology, it has been proved that it is profitably to manipulate the switching phase when off-resonance cases occurred. Therefore, it is meaningful to investigate its performance on impedance matching from the pragmatism perspective. With reference of the past studies on equivalent impedance of PEH system, it is possible to establish the impedance expressions from mechanical domain and electrical domain, which corresponding to the mechanical structure and   electrical the energy harvesting circuit, respectively. From the classical impedance matching theory we know that the maximum harvested power can be achieved when the load and source impedance is conjugated with each other, which means the real parts of the mechanical and electrical impedance equals to each other and the imaginary parts counteract with each other at resonance. This method is commonly used in electronic analysis to maximize the energy transferred from source to load. It can be utilized in PEH systems to explore the power relationship and limit which contributes to design broadband and high energy capability PEH systems.
<div align="center">    
<p><img src="https://s2.ax1x.com/2019/07/22/eiFoK1.jpg" alt="Figure 1. The illustration of impedance matching"  style="width:40%" />
<p>Figure 1. The illustration of impedance matching
</div>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;With a certain coupling intensity as shown in Fig.1(a), it is enlightening to explore the impedance matching under different circuit solutions. From the detailed view in Fig.1(b), the mechanical impedance curve is outside the available impedance range of conventional topologies such as SEH. Take P-SSHI as an example, with the growth of load resistance, the first tunable parameter varies from 0 to π which leads larger equivalent damping effect , corresponding to the real part of electrical impedance. However, confined by small load resistance, the electrical impedance cannot reach the mechanical impedance.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;As the load resistance continually increases along the one dimensional black dash line until {% raw %} ${Z'_e} = Z_m^*$ {% endraw %} at the resonance frequency, the red circle in Fig.1(c) represents the coupling point where the output power reaches maximum. At this point, the real parts of mechanical impedance and electrical impedance equal to each other and the imaginary parts counteract with each other. However, if the vibration frequency is not at the resonance frequency, such as lower or higher frequency. The real parts of the two impedance may equal to each other, but the imaginary parts could not be matched due to this type of topologies such as P-SSHI, S-SSHI or SEH only have one tunable parameter, the rectified voltage, which has confined the attainable impedance range on one-dimensional curves. Therefore, their off-resonance energy harvesting capability, in other words the broadband capability, is underperformed.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If we consider the general practical model, the second tunable parameter, synchronized switching phase, with different switching phases, the conventional one-dimensional impedance curves become two-dimensional impedance plane, which enables much wider range for impedance matching. As shown in Fig.1(d), if the system operates at lower frequency, there is no way for conventional solutions to match the coupling point, but with a lead phase, which brings a negative electrically induced stiffness to the system, if the system operates at higher frequency, similarly, a lag phase will introduce larger electrically induced stiffness to the system, which tunes the resonance frequency from {% raw %} $\omega_r${% endraw %} to {% raw %} $\omega_h${% endraw %}. With the second tunable parameter, the off-resonance energy harvesting capability is incresed, therefore the general pratical model enables not only the in-resonance harvesting capability, but also the broadband capability at off-resonance cases.


### Critical Coupling


<div align="center">    
    <p><img src="https://s2.ax1x.com/2019/07/22/eiF5vR.jpg" alt="Figure 2. Critical coupling"  style="width:30%" />
    <p>Figure 2. Critical coupling
</div>


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;One important feature of impedance matching is critical coupling for the selected circuit topologies, which means the minimum coupling intensity needed to reach the maximum output power. As shown in Fig.2, for PV-SSHI, the red line is tangent to the boundary of PV-SSHI at the coupling point. In order to determine its critical coupling intensity of PV-SSHI, firstly the effective coupling intensity is defined as {% raw %}$K_e^2${% endraw %}, then with the impedance matching relationship it can be derived that:

{% raw %}
$${\frac{{2\left( {1 - \gamma } \right)}}{{\tilde \omega \pi \left( {1 + \gamma } \right)}}\left( {1 + \cos 2\varphi } \right) = \frac{{2{\zeta _m}}}{{k_c^2}}}\\
{1 + \sin 2\varphi  = \frac{{{{\tilde \omega }^2} - 1}}{{k_c^2}}}$$
{% endraw %}

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;With the critical coupling intensity {% raw %}$K_c^2$ {% endraw %}derived from above expression of PV-SSHI, the minimum coupling intensity required for impedance matching can be identified under certain mechanical damping factor. The red line shown in Fig.2(b) indicates the optimized solutions of switching phases under different mechanical damping factors. For the critical coupling intensity of conventional SSHI topologies, it can be derived when {% raw %}$\phi=0${% endraw %}, however, compared with the vertical dashed gray line crossing {% raw %}$\phi=0${% endraw %}, the optimized phase solutions are smaller than {% raw %}$0${% endraw %}, which means with phase variable technology, the minimum coupling intensity can be coupled with a certain lead switching phase. And as the mechanical damping effect increases, it needs a bigger negative optimized switching phase to couple with the minimum coupling intensity. As shown in Fig.2(a), the two critical coupling points for conventional SSHI topologies and PV-SSHI, a weaker coupling intensity can be handled by the phase variable energy harvesting model. To simplify the expression of {% raw %}$K_c^2${% endraw %}for pratical usage, it can be expanded by Taylor series as:

{% raw %}
$$K_{c}^2 = \frac{2}{{1 + \cos 2\varphi }}c + \frac{{2\left( {1 + \sin 2\varphi } \right)}}{{{{\left( {1 + \cos 2\varphi } \right)}^2}}}{c^2},  \qquad c = \frac{{\pi \left( {1 + \gamma } \right)}}{{2\left( {1 - \gamma } \right)}}{\zeta _m}$$
 {% endraw %}

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;From the expression of {% raw %}$K_c^2$ {% endraw %} it can be found that with a certain switching phase, the critical coupling intensity will increase together with the mechanical damping factor. Moreover, if the flipping factor increases to{% raw %} $-1${% endraw %}, the critical coupling intensity will approach {% raw %}$0${% endraw %}, it means no matter what circuit topology is used, the maximum output power can be reached, due to the mechanical impedance curve is always inside the attainable impedance range of selected circuit. Furthermore, the critical coupling intensity also can be tuned by the switching phase {% raw %}$\phi${% endraw %}, as mentioned before, there exist an optimized switching phase to handle the weakest coupling intensity, which means the application range of conventional topologies have been expanded by the phase variable technology.


## Reference
>B. Zhao, J. Liang, "Impedance Modeling of a Bidirectional Energy Conversion Circuit towards Energy Harvesting and Vibration Exciting Purposes," IEEE/ASME Transactions on Mechatronics, to appear.

>B. Zhao, J. Liang, and K. Zhao, “Phase-Variable Control of Parallel Synchronized Triple Bias-Flips Interface Circuit towards Broadband Piezoelectric Energy Harvesting,” in 2018 IEEE International Symposium on Circuits and Systems (ISCAS), 2018, pp. 1–5.

<hr />
