# Low-power-CMOS-Inverter
The purpose of this project is to design a Low power CMOS inverter using an opensource EDA Tool called eSim, an opensource spice simulator called ngspice and Sky 130 PDK
# Table of Contents
1 [Abstract](#Abstract)

 2[Introduction](#Introduction)
 
 
 3[Reference Circuit Diagram](#Reference_circuit_diagram)
 
 
 4 [Simulation Results](#Simulation_Results)
 
      a.[input-output waveform](#input_output_waveform)
      
      b[power waveform](#power_waveform)
      
      
      
  5[Parameter Comparison Table](#comparisom_table)
  
  
  6[Conclusion](#conclusion)
  
  
  7[References](#References)
  
  
 
 
 
 
 # Abstract
 
 Low power devices have become increasingly popular in recent years. This rapid proliferation is specifically because of fast increase of battery-operated transportable devices including laptop, tablet PC . Semiconductor devices are scaled to achieve high performance and excessive integration density. Due to elevated density of transistors in a die, the power consumption in a die is increasing . Supply voltage is scaled to balance the power consumption within limits.
New low power techniques are required to reduce overall power in high performance nanoscale circuits.
This project introduces a inverter technique i.e. CMOS inverter and one another approach i.e. reduce Swing approach CMOS inverter



# Introduction
As we know the high performance circuit needs the large number of transistor with high speed. But this improvement in the performance comes with power dissipation. And high
package density becomes the one the major demand in VLSI technology, the size of transistor is getting reduced. As the technology is getting finer, the percentage of leakage power dissipation in total power dissipation is increases significantly.This power dissipation increases cooling cost and reduces the system reliability. There are two main sources of power dissipation in any processors are static power and dynamic power. This static power dissipation causes due to flow of leakage current. And other power dissipation is dynamic power dissipation which is the power dissipation in CMOS circuit in active mode.

# Reference Circuit Diagram
   ## CMOS Inverter
A CMOS inverter is consist of a pmos and an nmos devices. Its operation can be understood with a easy transfer version of the MOS transistor, the transistor is nothing greater than a transfer with an countless off resistance When input is logic 0, logic 1 is obtained at the output and when input is logic 1, logic 0 is observed at the output. Fig.1 shows the conventional CMOS approach.
The CMOS inverter has two important advantages over the other inverter configuration
The first and perhaps the maximum vital advantage is that the  steady-state power dissipation of the CMOS inverter circuit is absolutely negligible, besides for small power dissipation because of leakage currents.
The other blessings of the CMOS configuration are that the voltage transfer characteristic (VTC) exhibits a complete output voltage swing among zero V and VDD, and that the VTC transition is normally very sharp. Thus, the VTC of the CMOS inverter resembles that of an ideal inverter [1].
## Reduce CMOS Inverter




# Simulation Results








