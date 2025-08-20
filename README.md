<div align="center">
  <h1>Altus Charger</h1>
  6 channel output charger for AltusMetrum batteries. 
  
  ## Status
  Boards have arrived and passed testing great!
  <div>
    <h3><em>3D Render:</em></h3>
    <img src="rsc/img/Altus_Charger_V1" alt="Altus Charger Board" style="height: auto; width: 400px;">
  </div>
  
  ## Hardware
  This project is designed to support charging of 6 Altus Metrum batteries over a 5V 2A USB-C connection using the same battery charging circuit as the Telemega. Therefore, the RProg resistor selection was set to 3.3k to charge each battery at ~300mA. For context, the Telemega integrated charger is configured to charge at ~342mA. This results in ~13% slower charging per battery. However, with the benefit of charging multiple batteries at once this quickly makes up the difference.
  This project also includes a switch to turn off the LED indicators for overnight charging. 
  
  ## Schematic
  <h3><em>Root Schematic:</em></h3>
  <p>The root level schematic shows the overall blocking of the hardware design.</p>
  <img src="Hardware/AltusCharger/gen/images/AltusCharger_sch.svg" alt="Root Schematic" style="height: auto; max-width: 500px;"><br>
      
  ## PCB Design
  <div>
    <h3><em>3D Render:</em></h3>
    <img src="Hardware/AltusCharger/gen/images/board.front.png" alt="3D Render" style="height: auto; width: 400px;">
    <img src="Hardware/AltusCharger/gen/images/board.back.png" alt="3D Render" style="height: auto; width: 400px;">
  </div>
  
  <div>
    <h3><em>PCB Artwork:</em></h3>
    <img src="Hardware/AltusCharger/gen/images/pcb_front.svg" alt="Front" style="height: auto; width: 400px;">
    <img src="Hardware/AltusCharger/gen/images/pcb_back.svg" alt="Back" style="height: auto; width: 400px;"><br>
  </div>
</div>