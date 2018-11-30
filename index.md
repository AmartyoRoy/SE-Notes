# Software Engineering Notes Unit 3
## Software Design 
### Coupling
Coupling is the *measure of interdependence* between modules. Two modules with high coupling are strongly interconnected.
In the diagram below S1 is highly coupled(many dependancies) while s2 is loosely coupled(some dependencies)
![Coupling Diagram](https://www.researchgate.net/profile/Hakim_Lounis/publication/228687342/figure/fig1/AS:669530477064208@1536639913691/Different-Modules-Coupling.png "Coupling")  

*There are 6 types of coupling*-  
![Types-Coupling](https://qph.fs.quoracdn.net/main-qimg-ab2a7909670e50d227f6941e33e5c536 "types of coupling")
1. **Data Coupling**
  The modules communicate only by passing of data.
  Module dependencies can be minimized by ensuring that modules  
  communicate only neccesary data.  
2. **Stamp Coupling**
  Complete Data Structure is passed from one module to another.
  Typically involves tramp data.
3. **Control Coupling**
  Modules communicate by passing of control information.
4. **External Coupling**
  External coupling occurs when two modules share an externally imposed data format, communication protocol, or device interface.
5. **Common Coupling**.
  Modules have common shared and common data space.
  Any change to data space may effect the working of all the modules.
6. **Content Coupling**
  This occurs when control is passed from one module to the middle of another module.
