# Speed control of induction motor using fuzzy logic : ------>

                                                   ABSTRACT
Theuseof Induction motors has increased tremendously, since the day of its invention. They are being used as actuators in various industrial processes, robotics,
house appliances and other similar applications. The reason for increasing popularity day by day can be primarily attributed to its robust construction, simplicity
in design and cost of effectiveness. This paper presents a methodology for implementation of a rule-based fuzzy logic controller applied to a closed loop Volts/Hz 
speed control of induction motor. The Induction motor is modelled using a dq axis theory. The designed Fuzzy Logic Controller's performance is weighed is compared 
with that of a PIcontroller.
                                INTRODUCTION
The Induction machine is an important class of electric machines which finds wide applicability as a motor in industry and they are manufactured in large numbers.
Almost 90% of the mechanical power used in the industry is provided by 3-phase induction motors. It is substantially a constant-speed motor with a shunt characteristic; 
a few percent speed drop from no-load to full load. It is a singly- fed motor unlike the synchronous motor which requires ac supply on the stator side and dc excitation 
on the rotor. The torque developed in this motor has its origin in current induction in the rotor which is only possible at non- synchronous speed hence the name asynchronous 
machine. Speed control is one of the various application imposed constraints for the choice of a motor. Out of all the speed control mechanisms, the volts/hertz control scheme 
is very popular because it provides a wide range of speed control with good running and transient. This control mechanism is referred to as scalar control mode. Here both the
input and output commands are speed, unlike the vector control mode where it is torque/flux and reference current, respectively. The field of power electronics has contributed
immensely in the form of voltage-frequency converterswhichhasmadeitpossibletovarythespeed over a wide range. However, the highly non-linear nature of the induction motor control
dynamics demands strenuous control algorithms for the control of speed. Theconventionalcontroller types that are used fortheaforementioned purposeare maybenumeric or neural or
fuzzy. The only problem associated with use of conventional controllers in speed control of induction motors is the complexity in design arising due to the non- linearity of
Induction Motor dynamics. The conventional controllers have to linearize the non-linear systems in order to calculate the parameters.
