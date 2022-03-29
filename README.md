# CS_amplifer_current_mirror
CS Amplifier with active load and Current Mirror Biasing
### Schematic Entry using Xschem

### • XSCHEM is a schematic capture software that allows to design electronic circuit using a graphical interface.
#### – After Schematic has been created, a circuit netlist can be generated for simulation

### • XSCHEM supports four netlist formats:
#### – SPICE netlist
#### – VHDL netlist
#### – VERILOG netlist
### • Commands:
#### – Open terminal and type
  #### Xschem
![1_CS_schemetic_xschem](https://user-images.githubusercontent.com/81389879/160616551-790a848d-d915-4837-87a5-4395498ae1a3.jpg)
### Simulations using Ngspice
#### Ngspice is a general-purpose circuit simulation program for nonlinear and linear analyses.
![2_ac_analysis_plot](https://user-images.githubusercontent.com/81389879/160616583-309a3143-9b52-4304-a48c-06bb185e613f.jpg)
![3_dc_analysis_plot](https://user-images.githubusercontent.com/81389879/160616598-34bf08bd-42ed-468e-8395-48df87f52796.jpg)
![4_transient_analysis_plot](https://user-images.githubusercontent.com/81389879/160616605-ab81c7d0-b126-44da-99db-f4a18f58eaf2.jpg)
## Layout using Magic Tool
#### – Magic has built-in knowledge of layout rules
#### – Tool uses simplified design rules and circuit structures for laying out devices

#### – It also extracts the Netlist from layout for LVS
### • Commands:
#### – Open terminal and type
  #### Magic –d OGL
![5_cs_layout n LVS](https://user-images.githubusercontent.com/81389879/160616627-46cd158c-cd7c-4f2d-a181-c2e5f0d814b2.jpg)
![6_log for match](https://user-images.githubusercontent.com/81389879/160616646-ecee372c-72df-4074-9875-60e0a1eb977c.jpg)
![7_cs_simple_layout](https://user-images.githubusercontent.com/81389879/160616669-3b599c0d-1a92-4e16-97d5-928c4f7a3c93.jpg)
![8_multi_finger_layout](https://user-images.githubusercontent.com/81389879/160616685-4ee45596-c6cc-4985-ae30-9eb3bdd580f9.jpg)

##### Appendix

 
 
 
  
  ### **xschem**


  
 
 ```
  shift+i :  used to open the device library 
  
  w : used to draw wire between to nodes
  
  c : used to copy the device
  
  m :  used to move the device
  
  f : used to go into full screen (zoom to fit)
  
  shift+f : used to flip the device
  
  shift+r : used to rotate the device
 
  ctrl+o : used to open schematic/symbol  
 
```

