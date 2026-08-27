This is the Custom VRM for 1807 redbird robotics.
It uses a pololu 12V, 2.5A Step-Up/Step-Down Voltage Regulator to output a constant 12V 2.5A.
 (https://www.pololu.com/product/4984)
To give the short circuit protection I am using a E fuse. 
(https://www.digikey.com/en/products/detail/texas-instruments/TPS25961DRVR/17394947)
(Datasheet - https://www.ti.com/lit/ds/symlink/tps25961.pdf?ts=1703073741623&ref_url=https%3A%2F%2Fwww.ti.com%2Fsitesearch%2Fen-us%2Fdocs%2Funiversalsearch.tsp%3FlangPref%3Den-US%26searchTerm%3D) 
The Resistances for each resistor were included in the data sheet for a 12v 2A application. 
I plan for this to have two layers the bottom with all of the ICs and then a second PCB for all of the connectors. 
The Pololu board will be soldered onto the bottom layer PCB. 
The preferred connector for everything will be WAGO quick connects. 
Each connector will have an LED in series to display status.
All resistors are 0201 (0603 Metric) sizing standard. 
All capacitors are Ceramic Capacitor 0402 (1005 Metric). 
