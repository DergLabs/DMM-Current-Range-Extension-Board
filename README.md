# DMM-Current-Range-Extension-Board

This super simple little PCB is used to extend the range of a Keithley 2000 series or Agilent 6 1/2 digit benchtop DMM. It uses 1 or 2 (parallel) low-value current shunt resistors. It is best to use resistor values of 1mΩ, 5mΩ or 10mΩ to make converting the measured voltage drop to current easy. For my aplication, I am using a 10mΩ shunt resistor and thus for every 10mV my DMM reads, 1A will be flowing through the shunt. This board is suitable for roughly 20A with low-value shunt resistors. For my use case, 10A is the maximum. 

The board pictured below was an older test version that uses an aluminum PCB to minimize temperature rise in the Resistor. I have since changed to a two-layer board allowing for parallel resistors for even lower total resistances. 

![IMG_2099-min](https://user-images.githubusercontent.com/11001357/168540110-101cfef7-ccad-44c5-8083-dce8a8de08a4.png)

![Screenshot 2022-05-16 032541](https://user-images.githubusercontent.com/11001357/168540757-e03b4aa5-14ef-4da2-b503-2a2961427654.png)
