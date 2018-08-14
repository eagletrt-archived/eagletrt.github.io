.. image:: /images/wallpaper.png

Cooling of Chimera Evoluzione
=============================

.. image:: /images/design.png

1 Introduction
^^^^^^^^^^^^^^

.. image:: /images/designCooling/designCool1.png

**1.1 Apparatuses producing heat**

**Electric motors: Letrica Emrax 208 LC**

The machine elements providing the car the power necessary to achieve its great dynamic performances are two Emrax 208 electric motors, working in parallel, virtually free and linked together by an electronic differential. The starting point in order to set a cooling system, not having experimental data, was the factory technical datasheet. Advised cooling parameters were a water flow of 7-8lpm with inlet water temperature not exceeding 50°C. No extra information was added on the internal geometry of the liquid passage or the heat exchange coefficient.

**Inverters: Unitek Bamocar D3-V6**

The inverter in the chimera EVO is a custom rearrangement of two Unitek Bamocar D3-V6 inverters, readapted to be used inside a self-developed
carbon fiber reinforced polymer case, with an in-house designed and
produced aluminum cooling plate.

**Custom High Voltage Battery Pack**

The battery pack providing energy for our high performance electric vehicle is an high voltage custom battery, that uses 108 modules of 6 parallel Sony cells. Its design was complicated by many envelope
constraints, and this affected the design of the cooling system. In particular, to minimize envelope, weight and to optimize mounting condition, the series of modules are put so to form channels perpendicular to
the vehicle longitudinal axis and thus to air velocity. Air cooling was chosen, differently from the previous year in which water cooling was used, to minimize any risk of internal leakage, while the loss of
performances is not so marked to prevent this choice. A self developed air conveyor was designed in order to force the frontal air to curve and enter the transversal air channels that are formed by the geometry and
envelope of the battery modules. The interface allowing air to enter consists of holes made in correspondence of the natural channel, while a laser cut aluminum plate with laser cut silicone gasket seals
the conveyor against the battery pack walls. On the end (left side of the pack) of the channels, we find asimilar plate, holding three conveyor that act also as support for high static pressure fans.

.. image:: /images/designCooling/designCool2a
.. image:: /images/designCooling/designCool2b

**1.2 Quality Function Deployment and Engineering choices**

**Quality Function Deployment**

With the target of investing time and consolidating ideas about the product to be designed, a quality functional deployment (QFD) was first built.

The construction of the house of quality first began with identifying who the main customers for our product are.
Four customers prototypes were taken into account: the student who designs and/or manufactures the cooling system, a sponsor, the driver and a Formula SAE judge.

The next step involved understanding what every customer really wanted, that is each customer's requirements.
With the aim of finding out how well requirements satisfy customers, a fixed sum method was used so that these four virtual people could distribute their marks to the requirements keeping a total sum of 100.
The competition was afterwards analyzed, to understand how some among the main rivals manage to satisfy customers' requirements.

It was found that most of the teams refrigerate electric motors and inverters via water cooling, and they rarely use custom solutions, preferring OEM fittings and hydraulic circuits already present inside these electrical devices. As far as the BTMS (Battery Thermal Management System) is concerned, many teams develop an air cooling system, especially those employing pouch cells.

A set of engineering specifications was then generated, and a correlation was searched to understand how these parameters actually measure the previous requirements. In the process of understanding how the competition manages to fulfil engineering specifications, target and threshold values for each technical parameter were imposed for the E-agle Chimera EVO vehicle.

In the end an effort was made to identify how specifications can be dependent on one another, completing in this way the roof of the house of quality.
The QFD diagram is shown in the following page.

.. image:: /images/designCooling/designCool3.png

In order to understand the right direction for the system to be designed, best design practices were adopted, so a QFD analysis was performed, takin into account the students-designer, sponsors, driver and the Judges as “customers”, and the comparison was set against successful FSAE teams.

**Proposed Layouts**

As the battery pack is treated separately, liquid cooling of motors and inverter is now analyzed.
The first term of comparison to start the work for Chimera Evo cooling system was last year layout.
This was compared with three different new ideas of layout, each one trying to solve the critical aspects of the previous system in a different way.

.. .. image:: /images/designCooling/tabella1.png

.. image:: /images/designCooling/designCool4.png
.. image:: /images/designCooling/designCool5.png
.. image:: /images/designCooling/designCool6.png

Concept 2 uses two independent circuit, one for the motors, one for the inverters.
The strength of this solution is that it allows to achieve working conditions that are best for each unit, and this also allows better controllability.
Also, this solution minimizes electrical power requirement, as the circuits work independently and as the motors are more efficient, their circuit can be switched on and off on demand.
The application is also very modular.
Concept 1 minimizes the number of pumps, but has less controllability, and will have the lowest efficiency.
Concept 3 has a good controllability and efficiency and in particular allows to have the water flow perfectly divided in the left and rigth motor and inverter.
But it has no modularity and the demand of power will be higher, as water will always pass inside the motors even when not needed.

**1.3 Layout of the Cooling System**

**Water cooling system: ultimate layout.**
The final choice, aided by the comparison seen in the previous section, was concept 2. It was decided to have a slightly more complex system which optimizes performance at minimum electrical power requirement and with greater modularity.

**Battery pack air cooling: a separate solution**

The design of the cooling system layout for the battery pack was a true design challenge as other choices adopted for the position of the components inside the chassis and the frame itself gave precise and mandatory constraints.
It was decided to adopt an air cooling system to avoid complexity of water flowing inside a battery pack whose cells are not water resistant by themselves, in order to minimize the weight and the complexity, thus minimizing the total hindrance of the added system.
The battery pack is composed by modules of 6 parallel cylindrical cells, which are disposed vertically.
These modules are present in number 108.
We find six segments of 3x6 modules, disposed with the major length transversal to the car.
As we see in figures, the modules are constructed in a way which depicts natural tubes running for all the transversal length of the battery pack.
It was considered that these tubes were the most effective way to let the fluid air to flow and “wet” the maximum amount of heated surface inside the HVBM.
The interface linking the tubes inside the pack with the external consists in holes on the lateral faces of the carbon fiber composite walls. The major problem left to solve is to convey air inside the pack.
In fact, air flow would come longitudinally as the car moves, and it is necessary to send it into the already existing tubes running transversally. An air conveyor was designed with the aid of Ansys computational fluid dynamics software, which collects the frontal air flow brought by the car movement and deviates it, dividing it into three main flows- Each of the three fluid flow serves two segments, with a total of 20 virtual tubes.
The conveyor is on the right side of the car, and lets the fluid to go from the right to the left.
To counteract the high pressure losses due to the uneven geometry of the modules, which makes the virtual channel far from perfect cylindrical piping, three high static pressure fans were chosen, after a persevering research on producers site. The three fans, one for each main fluid channel, are secured using small conveyors which provide also a supporting action.
The interface was then studied in order to be rain proof.
So the conveyor on the right side and the three fan supporting conveyors on the left side are, respectively, fixed with adhesive bonding to aluminum laser-cut masks, which are sealed against the lateral faces of the case by automotive silicon laser-cut gasket, providing an effective protection against water infiltration.

The whole system is fixed with removable bolts against the case and demounting is made easy by this system, as the HVBP must be removed by the bottom of the car, without the conveyor installed.
All the conveyors are 3D printed in PA12 by Multi Jet Fusion, which provides an almost isotopic material, resistant to abrasion, stiff and strong.

.. image:: /images/designCooling/designCool789.png

2. Design of the cooling system
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**2.1 Determination of heat production**

**Electric motors: efficiency considerations**

From the performance point of view, the factory requirements for the cooling system were too much strict and would lead to an over-dimensioned cooling system. Instead, the aim of the team was to develop a clever cooling system specifically designed for a use rich in peaks of power instead than continuous power, and that could reduce the weight to the minimum. It was decided to contact the manufacturer to achieve extra information.
Letrica provided us with experimental work on Emrax 228 motors and extra information on the thermal resistance of the coiling and the electronic components.

.. image:: /images/designCooling/designCool10.jpeg

This information demonstrated the possibility of the system to work safely with low water flow (3lpm) at severe condition (70°C inlet water). It was chosen to increase the system maximum working temperature,
because this would allow to have a smaller heat exchange area, judging the loss of performance negligible.
As stated above, no experimental data were acquired, even though for year 2019 dyno tests with temperature sensors on the water inlet and outlet are planned. An average working condition was
determined for rpm and torque of the motors, and efficiency diagrams provided by the manufacturer were used.

.. image:: /images/designCooling/designCool11.png

Again, it was chosen to aim at maximum performance, so an average condition was analyzed, instead that dimensioning for maximum produced heat.
The adopted approach is regarded as a good engineering practice as it is demonstrated that the main car use is in transient, which leads to a heat production more similar to a constant average current. This lead to estimate a production of 750W of thermal power, resulting in a total of 1500W entering the circuit with the two motors in parallel.

**Infineon Iposim: simulation on inverters heat production**

The approach used is similar to the previous step, but in order to determine the average produced current was used a more precise tool.
After a fruitful contact with the manufacture it was advised to use Infineon Iposim tool, which allows to simulate the electrical circuit of the inverter coupled with the cooling plate.
This powerful tool allows to specify the circuit topology, the application parameters and choose the exact devices used in the DC/AC three phase 2 level circuit.
After that cooling conditions are inserted, obtaining in output the results for the IGBT and Diode.
Carrying out this simulation for different currents and different water flow temperatures for the different devices and total power loss were obtained.
Again, it was chosen to consider an average condition leading to a total of 2000W of power to be dissipated on average.

.. image:: /images/designCooling/designCool12.png
.. image:: /images/designCooling/designCool13.png

**Battery pack energetic consideration and experimental work**

The heat dissipation on the battery pack was determined combining classical electrical theory and experimental work, which is still under research and development.
A custom discharging circuit was built by the team, allowing the discharge of three modules in series at high currents (in the order of magnitude of 10^2 Ampere), with also different current profiles.
This custom circuit also allows to test custom profile of currents (current vs time), recreating the conditions of a FSAE autocross or endurance test, obtaining curves for heating of the cells versus the time of the test.
This testing bench would also allow to simulate different cooling layouts and the effect of the several layout solutions.
However, the whole testing apparatus is still under development for this part and more precise consideration will be carried out to increase the precision and scientific reliability of the acquired data. An average current of 35 Ampere was chosen, according to data available on the net, confirmed by road tests made later to the designing step.
This value, combined from the internal resistance of the battery pack determined experimentally (5mohm at 25°C, 3.5mOhm at 50°C), lead to an estimation of 600W.
Yet, the mean current could reach values up to 60A, which leads to 2000W.

**2.2 Thermal Design**

**Design approach**
The design of the radiators for the liquid cooling system was carried out using the following approach.
The heat production of the corresponding unit to be cooled, treated in the previous sections, was taken as a regime condition.
The radiator was then designed to dissipate the produced heat at a fixed stationary condition for the flow of both fluids.
This condition was chosen in a way to be achieved at an high working point for the water pump, but not its maximum, so to maintain a certain factor of safety, but to exploit almost all the capability of the pump, and for an average condition for the air flow, as the latter is more variable and speed is generally low during FSAE competitions.
The ambient temperature was set at 25°C, as the car is used in different periods of the year in different locations in Europe.
The sensitivity of heat exchangers performances to the variation of these parameters (flow, ambient temperature, heating unit temperature) was then checked with the aim of avoiding critical conditions as much as technically possible.

This approach is not the more sophisticated, but it is simple and safe: in fact it provides a threshold to the system temperature which cannot be trespassed.
As the unit starts to accumulate heat, the cooling fluid will recirculate, increasing the heat exchanger temperature, which will start increasing its thermal
dissipation capability.
If the heat production is higher than the dissipation, the temperature will rise, until the nominal values are reached.
At this point the power dissipation is, by design, higher than the heat production capability of the system, even at regime, guaranteeing the functioning of the unit.

**Design of Louver Fin Flat Tube Plate-Fin Heat Exchanger: Inverter**

The inverter unit is cooled by a high performance radiator derived by a geometry used to upgrade high performance motorbikes or on race motorbike.
It consists in flat tubes, with very small channels, for the water, and louver fins, which have a triangular profile, but are characterized by cuts in the thickness direction, which present partially bent metal that constrain the fluid to a very tortuous path, generating turbulence, breaking of the boundary layer and thus higher heat exchange coefficients compared to traditional fin geometry.

.. image:: /images/designCooling/designCool14.png

The method used for designing is a classical method, widely used to obtain simple and cost effective dimensioning with few iterations, called Effectiveness-Number of Thermal Units method, for unmixed fluids in cross-flow.
The heat exchanger effectiveness ε is then given by

ε = Actual heat transfer rate/ Maximum possible heat transfer rate = q/qmax

.. image:: /images/designCooling/designCool15f.png

where the maximum heat transfer rate is given by
.. image:: /images/designCooling/designCool16f.png

The capacity rate is the product of the mass flow and the specific heat. The curve of the fluid with the
smaller Capacity rate will approach the curve of the higher one. he number of thermal units will be given
by this ratio:

.. image:: /images/designCooling/designCool17f.png

Concisely, for each geometry, scientific literature provides correlations for two factors: Colburn and friction
factor. The former is used to represent the thermal characteristics of the heat exchanger and allows to
determine epsilon and NTU values, while the friction factor allows to study the pressure losses on both fluid
sides. Chang and Wang in 1997 produced, after an extensive study on air flow databases, a correlation for
Colburn factor for the used geometry. A Maple spreadsheet was produced providing the thermal design
and verification of the selected finned tubes, which were then sought in several companies. After a similar
profile was found to be available, the design step was reiterated to
verify the functioning of the commercially available heat exchanger.
The performance of this heat exchanger is crucial for the correct
efficiency of the Inverter unit, so a fan was chosen in order to always
win the pressure drop of the heat exchanger and in particular to
obtain the nominal values of the air flow at the mean car speed,
which provides the air flow by itself. The various external parameters
were then varied for the final geometry, and the power dissipation
was calculated at different ambient, flow rate and unit temperature
conditions, the results are shown below. The chosen fan is a Spal
va68-a101-83 and has the following characteristics

.. image:: /images/designCooling/designCool15.png
.. image:: /images/designCooling/designCool16.png

**Design of Louver Fin Flat Tube Plate-Fin Heat Exchanger: Motor**

The same approach of the previous paragraph was used to design
the heat exchanger of the motor circuit, with an additional
peculiarity. Motors are proven by information provided by
manufacturer to be more robust and less sensitive to heat than the
inverter units. It was decided to try and use a radiator without an
additional fan, to save electrical power and the maximum amount of
weight, leaving more energy coming from the LVBP for the air
cooling of the HVBP and lowering the LVBP total capacity and
weight.

.. image:: /images/designCooling/designCool17.png

A first iteration was carried out with Bernoulli equation,
considering that the energy of the incoming airflow is distributed in
pressure and air flow passing through the fins.
After a suitable finned profile was chosen with a guessed air flow, iterations were carried out to determine the expected air flow passing at a given nominal velocity and the air flow was then updated.
The geometry was modified at every step, until the air flow allowed would provide the required heat dissipation.
This approach could be called a daring one, as Bernoulli equation is not the more precise method compared with modern ones, still the electric motors
are able to withstand some overheating and are at the best of their efficiency at the considered car speeds.
Finally, the various external parameters were then varied for the final geometry, and the power dissipation
was calculated at different ambient, flow rate and unit temperature conditions, with the added difficulty of
reiterating the steps to find the correct value for the allowed air flow. The results are shown below.

.. image:: /images/designCooling/designCool18.png

Design of Battery Pack air cooling system.
As portrayed in the layout section, this system was decided mainly by geometrical and hindrance
constraints. Design parameters consist in the characteristics of the fans, chosen to provide the most
effective heat transfer inside the battery pack, and the geometry of the conveyor, to allow the best possible
distribution of the incoming airflow in the three main channels. The airflow is regarded as given by the car,
so its energy will be summed with the energy provided by the fans, which in the worst case will provide
only static pressure. To characterize the thermal behavior the section for the fluid passage was considered
as a cylinder of equivalent area, and the contribution of the continuous expansion and contraction along
the length were taken into account using correlations for the friction factor such as the one shown in the
following equation:

.. image:: /images/designCooling/designCool19f.png

This allows on a theoretical basis to determine the resistance curve of the system, which intersects with the
power curve of the fans and determines a working point. The working point would then allow to determine
the heat transfer coefficient. However, this preliminary approach can’t take into account effectively of the
highly complicated geometry of the inlet and outlet of the conveyor, so a CFD approach was used instead.
[parte da chiarire con Enrico Lovato]. The CFD analysis highlights how the incoming airflow distributes
evenly in the three channels and reaches good velocities inside the battery pack. This work proved to be
time demanding and thus is still under development. The easier solution would be to look for a suitable
correlation for the Nusselt parameter and determine the heat transfer coefficient, but a thermal-fluido-
dynamic analysis is under development to characterize correctly the behavior of the fluid inside the pack.
Early results with the analytical model used above, combined with data from the testing bench, prove that
the air cooling system can’t maintain the temperature under a steady state regime of 2000W of thermal
loss. Nevertheless, they show a progressive heating from the ambient temperature that doesn’t reach
critical values before the end of the longest FSAE dynamic test, the endurance. Thus, the designed solution
is accepted, and it proves to be light and performing given the starting constraints.

.. image:: /images/designCooling/designCool20.jpeg
.. image:: /images/designCooling/designCool21.jpeg
.. image:: /images/designCooling/designCool22.png

**2.3 Hydraulic Design**

**Experimental Work on Hydraulic losses determination**
To determine the working point of the liquid cooling system it was necessary to set up an experimental set
of tubing. A Marco UP12 pump was used, and the unit to be tested was connected to a manometer at the
inlet and another one at the outlet. A flow measurer was used in series to the unit in order to control the
water flow. Each unit, motor, cooling plate and radiator was tested at different flow rates and data on the
pressure losses were acquired. It was demonstrated that in the range of the system parameters the
contribution of tubing, bends in tubes and fittings could be neglected, and thus curves of resistance were
extrapolated for each unit. The schematics for the hydraulic tests are shown below.

.. image:: /images/designCooling/designCool23.png

3. Results
^^^^^^^^^^

**3.1 Liquid cooling system**

.. image:: /images/designCooling/designCool24.png

**Working Point of the circuit.**

Resistance curve for each unit were compared with the power curve of the GRI INTG3 pump, provided by the manufacturer.
Different working points were found for the different values of the control voltage.
This allows, combined with data calculated from the heat exchanger design, to find the different steady state power dissipation of the circuits

**Performances of the Motor cooling circuit**

Above are shown the schematics of the motor cooling systems with calculated curves describing its working points displayed below. The nominal values are summarized in the datasheet.

.. image:: /images/designCooling/designCool25.png

**Performances of the Inverter cooling circuit**

Above are shown the schematics of the inverter cooling systems with calculated curves describing its working points displayed below.
The nominal values are summarized in the datasheet.

.. image:: /images/designCooling/designCool26.png

**3.2 HV battery pack cooling system**

**Layout of the Battery cooling system and present work on the simulation**

.. image:: /images/designCooling/designCool27.png

The obtained geometry distributes evenly the air flow, allowing for an homogeneous heat transfer.
Data of the chosen fans are also displayed, and will in future be linked to the pressure losses inside the BP obtained by the simulation. In the following image it’s displayed the flow in the first, sixth and last column of tubes (out of twelve).

.. image:: /images/designCooling/designCool28.png

In the next image we have displayed the flow in the third row out of five, starting from the bottom of the case.

.. image:: /images/designCooling/designCool29.png

To demonstrate the distribution of the airflow we have the velocity field inside the conveyor.

.. image:: /images/designCooling/designCool30.png
.. image:: /images/designCooling/designCool31.png

**3.3 Weight Reduction**

**Additive Manufacturing for fittings and tanks**

Different solutions are available on the market for hydraulic fittings such as consumer hydraulic fittings,
manufacturers fittings for motors and inverter cooling plate, or quick connection fittings. In our case, it was
decided to develop a manufacturing technology made available by our main sponsor, in rapid growth
worldwide, for small to medium scale production. Multi Jet Fusion 3D printing was used, working with
Polyamide 12 powder. This technique implies an IR-heated chamber, in which the powder bed is hit by
multiple jets of fusing agent and detailing agents and heated to fusion by additional IR lamps. The
peculiarity of this technique is that the sliding part of the printer is embedded with thousands of micro
injectors, which allow high definition and moreover, makes the printing time not dependent from the
density of the printing layer. Therefore, it is possible to produce with a single print several pieces without
increasing the production time, which depends only on the printed height. It was for us possible to think of
custom and yet cost effective fittings and expansion tanks, much lighter than the metal counterparts, and
with a more optimizable design, in terms of resistance to fluid passage but also geometrical hindrance and
appearance. It was also tried to produce fittings for motors and the cooling plate, but even tough they were
sufficiently resistant to the fluid pressure, problems of rupture of the threaded part made them unreliable,
until further optimization of mechanical resistance and tightening torque is made. These fittings are made
in-house with a turning machine using aluminum instead of the original steel, with a consistent weight
reduction.

**Overall weight reduction**

This comparison is made considering the weight reduction with respect to the previous year cooling
system. The general design procedure of the previous year focused on large safety margins, worked
considering the maximum heat losses and used a water cooling system also for the battery pack, with a
heavy system of copper tubing and aluminum masks inside the HVBP, to provide sealing and good contact.
The new air cooling system uses mainly nylon, abs, and thin aluminum masks. The previous heat
exchangers were copper piping and aluminum tubes, and because of the heavy heat dissipation capability
demand, they were also over-dimensioned. The new heat exchangers reduce the internal volume of water,
are smaller and much more effective, plus they are right-dimensioned. The water cooling system is
simplified and thanks to the new layout and fittings has lower head losses, allowing for less resistant tubes,
less powerful pumps. Speaking of the pumps, brushless 24V pumps are used, with integrated contro

.. image:: /images/designCooling/designCool32.png

A separate section is to be made for the cooling plate. In fact, the original inverter cases were removed and
a new carbon fiber reinforced polymer one was made to hold the two DC/AC inverter circuits. A new plate
had to be designed. In order to produce it, the old ones were studied, and the original cooling circuit was
copied and embedded in a new, laser-cut inverter plate. Values of thermal resistance and pressure loss
were calculated and are shown in the dedicated datasheet in the appendix. The result was a cooling plate
with similar heat transfer coefficient but significantly lower pressure loss.

.. image:: /images/designCooling/designCool33.png

Considering all the newly designed components explained above, the overall weight reduction is,
considering also the smaller volume of fluid, is roughly of 70%, with an estimated weight of the whole
system of 7 kilograms.

**3.4 Future Development**

**Additive Manufacturing for Heat Exchangers**

The conventional manufacturing techniques for heat exchangers have reached a saturation. The
geometries obtainable for fins and tubes with techniques such as profile extrusion, lamination, cutting,
turning etc are limited, so are the possibility of joining fins and tubing. Additive manufacturing, in particular
selective laser melting, uses metal powder, such as aluminum, and shapes it with a complete freedom for
the shape and the geometry, obtaining mechanical properties very similar to the bulk materials the powder
is made of. The team has started a study which will use Ansys simulation software combined with Selective
Laser Melting machines in order to build a functioning 3D printed heat exchanger that will allow greater
heat exchanging capabilities, minimizing weight, internal volume and head losses, pushing the laws of
thermodynamics to their limit.

**Sensors and electronic control for system optimization.**

The present system is perfectly functioning and able to withstand the worst environmental conditions. But
not acquiring data from the working does not allow to finely control the water and air flow, leading to
higher electrical power demand and lower performance than the ideal conditions. Sensor for inlet and
outlet temperature plus flow meters were bought and await to be embedded in the system, in order to
understand at any instant, the working condition of the system and adjust it on demand. Acquiring data will
also allow to prepare functioning maps that can make the system react in advance to car acceleration, or to
start the cooling system only when it is really effective or necessary to start it.

**Data acquisition**

To design even at lower safety margins, it is planned to use temperature sensors and a dyno bench to test
exactly the motor and inverter heat production at any current, and to determine the heat exchange
coefficient of the internal tubing of each unit. This will allow to optimize the water flow, which does not
affect much the efficiency of the radiators but could affect the unit temperature and heat exchange greatly.
Moreover smaller radiators could be designed, and a more precise control of the system could be
implemented.

**Thermal-Fluid-dynamic Simulation on the HVBP**

The present cooling system for the battery pack is functioning and allows to maintain the temperature of
the battery under the critical threshold, in compliance with FSAE rules. It is need of a complete
characterization. This work is in progress and will lead to characterize the thermal behavior of the entire
pack. The fluid-dynamic analysis will be refined, changing the internal geometry from the ideal cylindrical
tubes to the real geometry, considering the cells and the walls of the modules, the internal walls and the
insulation. Then a thermal simulation will be carried out to determine the temperature in each point of the
pack. This analysis will allow to consider the hotter spots, to adjust the geometry of the conveyors and if
needed to modify the position of the fans. With this model it will also be possible to re-design the new
HVBP to optimize the cooling, as it is of central importance for achieving the maximum efficiency
