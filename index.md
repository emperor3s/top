# TOP
## We facilitate development of fit-for-purpose organ-on-chip systems by enabling seamless integration of components.

We provide tools for you to apply as an organ-on-chip developer. The tools are organized around the concept of TOP: an open, modular organ-on-chip platform.

TOP is structured along three levels:
- Microfluidic Building Blocks (MFBBs)
- Fluidic Circuit Boards (FCBs)
- Control systems

**MFBBs** are individual microfluidic devices with a dedicated function. They have one or more fluidic connections that allow microfluidic interfacing to the FCB. Optionally, an MFBB also has electronic, pneumatic or photonic connections. Examples of MFBBs are flow sensors, liquid reservoirs, biosensors, lab-on-a-chip devices and organ-on-chip devices.

**FCBs** are holders with fixed, standardized dimensions that allow interfacing with both MFBBs and with the control system. An FCB has at least one pneumatic inlet for pressure-driven flow control. FCBs can provide passive routing of liquids between MFBBs, but can also contain active pneumatic or electronic elements for advanced control.

**Control systems** are modular systems that provide power, pressure, and control to all system components, including MFBBs and FCBs. Typically, the control system includes at least one microcontroller for full system control and a pressure controller for pressure control. Other electronic components can also be part of the control system. Control systems also include the software that interacts with all individual modules (MFBBs, FCBs, control system components) and enables programming of system function.

The tools that we provide on each level are the following:

We provide a **community-driven database of MFBBs** (link to GitHub CMS) that are compatible with TOP. Some of the MFBBs are non-commercial and follow principles of open-source hardware, others are commercial and provide only the required specifications on interfacing. Database entries for all MFBBs at least provide specifications related to footprint and fluidic interfacing with FCBs. Optionally, other relevant specifications are provided, such as those related to electronic interfacing with control systems and software (e.g. through APIs). Where possible, we provide direct links to web shops in which MFBBs can be purchased (in the case of commercial MFBBs) or where they can be made-to-order (in case of open-source hardware MFBBs).

We provide an **online, open-source tool for generating FCB CAD-files** (link to GitHub) based on the MFBBs that you select for integration in the organ-on-chip system. The tool takes into account footprint and fluidic connections of each MFBB and generates a lay-out of pneumatic channels, fluidic channels and inlets and outlets. We provide links to web shops in which the custom-designed FCB can be fabricated using your material and fabrication method of choice.

We provide a **database of control system components** that are either required for overall functioning of the intended organ-on-chip system (such as microcontrollers, power sources and pressure controllers), or that are directly required by the selected MFBBs (such as microcontrollers or input/output components). 

We provide a **community-driven, open-source software package** (link to GitHub) for interfacing with control system components and for providing an API with higher-level functions derived from the control system. A graphical user interface is also provided for basic access to the higher-level functions of the system without having to write a program. 
