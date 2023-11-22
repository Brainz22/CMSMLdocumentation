## What are FPGAs?

FPGAs stands for Field Programmable Gate Arrays, and they are digital integrated circuits (ICs) that contain programmable blocks of logic. A crucial feature of such devices is that they allow the acquisition of data at sub-microsecond and high data rates, while offering flexibility in terms of their functionality and low power usage. The following image depicts how the FPGAs compare with the more common CPUs and GPUs, as well as ASIC devices.

![Untitled](../../../images/resources/fpga_figs/fpga_spectrum.png)

On the left side of the spectrum, devices like CPUs and GPUs have an internal architecture that is predetermined by the manufacturer, but which are created in a way that they can be reprogrammed to perform a variety of tasks.

On the opposite end of the spectrum are ASICs which contain hundreds of millions of logic gates. Thus, ASICs can be used to implement extremely complex functions. Although, the ultimate in complexity and performance, designing and building one is an extremely time-consuming and expensive process. In addition, once the final design is implemented, the ASIC device is "frozen in silicon." This means that the device cannot be modified or reconfigured without creating a new version.

As it can inferred, FPGAs lie in the middle of the spectrum for justified reasons. The functionality of FPGAs can be customized in the field without the need to replace the device, and they can contain millions of logic gates. Such advantages are important because they mean that FPGAs can be used to implement extremely large and complex functions that could only be realized using ASICs, while offering the flexibility to reprogram.

## FPGAs at the CMS Detector

The Compact Muon Solenoid (CMS) comprises of a system of two triggers that select collision events in a live and offline basis. These two triggers are the High Level Trigger (HLT) and the Level 1 (L1) trigger. A significant difference between the two triggers to highlight in this discussion is that, on one hand, the HLT is a version of the CMS offline reconstruction software running on a computer farm made up of CPUs and GPUs. On the other hand, the L1 trigger is a custom hardware-software codesigned algorithm implemented on FPGAs. The workflow of the two-trigger system in the CMS detector is outlined in the figure below.

![Untitled](../../../images/resources/fpga_figs/TriggerSysWorkflow.png)


## HL-LHC Implications for the CMS Level-1 Trigger



## Machine Learning on the Level-1 Trigger for Targeted Data Acquisition
Research involving these devices has become 