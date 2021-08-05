---
title: Material Selection for Transistors at the Scaling Limit
author: sylvia
type: page
date: 2014-06-10T23:51:33+00:00
images: ["current_NEGF2.png"]

---
Although Si and Ge are the staples of semiconductor industry, many different materials are being considered for field effect transistor (FET) applications to boost performance. Examples include Si, [Ge](http://www.sciencedirect.com/science/article/pii/S092151070600465X), [III-V](http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=5593863&tag=1)s, carbon nanotubes ([CNT](http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=1234339)s), and [graphene](http://iopscience.iop.org/0022-3727/44/31/313001)</a>. As the channel length drop below 10 nm, direct source-to-drain tunneling through the channel limits the OFF current for both [standard FET](http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=01175936)s and [TFET](http://scitation.aip.org/content/aip/journal/jap/110/7/10.1063/1.3642954)s. Therefore, a natural question arises:

> “How well do different materials block the direct tunneling current in both n-type and p-type NW FETs or CNTFETs with actual 5 nm channels?”


We investigated a wide range of materials including Si, Ge, InAs, InSb, InP, GaAs, GaN nanowires and CNTs with varying diameters  to compare their ability in blocking the tunnel current at the 5-nm length scale.  We found that, overall, Si gives the lowest tunnel current for electron and hole tunneling.

{{< figure src="current_NEGF2.png" caption="Intraband tunneling current as a function of diameter for (a) electrons and (b) holes." >}}


Tunneling currents are determined by the attenuation factor _κ_ in the bandgap. Although _κ_  is the key parameter, most device people do not have an intuitive feel for quantitative values of _κ_. For example, what values of _κ_ would be considered ‘large’ versus ‘small’ decay constants? Device people are, however, well-calibrated to values of the effective mass, and they do have an intuitive feel for what constitutes a ‘heavy’ mass versus a ‘light’ mass. Therefore, to compare the relative size of tunnel currents among different materials without performing expensive numerical simulation, we mapped the values of _κ_ into a tunneling a effective mass m<sup>\*</sup>. The larger the tunneling mass, the smaller the tunneling current and vice versa. Si has the heaviest tunnel mass and the lowest current.

{{< figure src="Tunneling_eff_mass-3in-3.png" caption="Tunneling effective mass for (a) electrons and (b) holes." >}}

