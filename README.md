# Low-power-CMOS-Inverter
The purpose of this project is to design a Low power CMOS inverter using an opensource EDA Tool called eSim, an opensource spice simulator called ngspice and Sky 130 PDK
# Table of Contents
1 [Abstract](#Abstract)

 2[Introduction](#Introduction)
 
 
 3[Circuit details](#circuit_details)
 
 
 4 [Simulation Results](#Simulation_Results)
 
      a[input-output waveform](#input_output_waveform)
      
      b[power waveform](#power_waveform)
      
      
      
  5[Parameter Comparison Table](#comparisom_table)
  
  
  6[Conclusion](#conclusion)
  
  
  7[References](#References)
  
  
 
 
 
 
 # Abstract
 
 Low power devices have become increasingly popular in recent years. This rapid proliferation is specifically because of fast increase of battery-operated transportable devices including laptop, tablet PC . Semiconductor devices are scaled to achieve high performance and excessive integration density. Due to elevated density of transistors in a die, the power consumption in a die is increasing . Supply voltage is scaled to balance the power consumption within limits.
New low power techniques are required to reduce overall power in high performance nanoscale circuits.
This paper introduces a inverter technique i.e. CMOS inverter and one another approach i.e. reduce Swing approach CMOS inverter



# Introduction


A CMOS inverter is consist of a pmos  and an nmos devices. Its operation can be understood with a easy transfer version of the MOS transistor, the transistor is nothing greater than a transfer with an countless off resistance When input is logic 0, logic 1 is obtained at the output and when input is logic 1, logic 0 is observed at the output. Fig.1 shows the conventional CMOS approach.
The CMOS inverter has two important advantages over the other inverter configuration

# Simulation Results
a input-output waveform
![cmos_inveter_simulation_1](https://user-images.githubusercontent.com/99197393/152943338-6a976bcc-7267-4e1a-9e3d-cf1675e1f673.JPG)


![Reduce_swing_cmosinv _simulation](https://user-images.githubusercontent.com/99197393/152943396-c3c52997-c32a-4c54-89a4-f9eb7271a79d.JPG)


b power waveform

![power_cmos_inv](https://user-images.githubusercontent.com/99197393/152943620-e19adff5-15ff-4210-8d70-cf7f20bc5ec3.JPG)

![power_reduce_swing](https://user-images.githubusercontent.com/99197393/152943694-d2824f7f-0950-4bb4-8598-461f0666f8da.JPG)








