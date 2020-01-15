TDC based Security Primitive (in Verilog)
--------------------------------------------


Description
-----------

This is a time-to-digital converter (TDC) based security primitive that can be pre-deployed on FPGAs to verify whether 
the FPGA based designs are corrupted by Hardware Trojans (HTs).

The basic idea is to monitor the abnormal voltage fluctuations when Trojan is activated whether or not.

This TDC based security primitive is suitable for Xilinx Spartan-6 FPGAs. 


Package Structure
-----------------

This package contains the following files and folder:

-README 				: This file

-TDC_IP_CORE			        : This folder contains EDN, UCF and Wrapper files both for Spartan-6 FPGAs.


Usage of the Security Primitive  
-------------------------------

Before integrating the security primitive into your design, you have to modify the "signal_name" in the UCF file.


Authors and Contact Details 
---------------------------

Haocheng Ma, 
hc_ma@tju.edu.cn,	
School of Microelectronics, Tianjin University, China

Jiaji He, 
jiaji_he@mail.tsinghua.edu.cn, 
Institute of Microelectronics, Tsinghua University, China


Copyright 
---------

It is mainly intended for non-commercial use, such as academic research.


Release Notes
------------

Build date : January 15, 2020
