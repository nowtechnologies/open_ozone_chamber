# Open Source Ozone Sterilizer

### Ozone

Ozone (O3) is an unstable gas comprising three atoms of oxygen. It is unstable because the gas will readily degrade back to its stable state, diatomic oxygen (O2) with the formation of free oxygen atoms or free radicals. The free oxygen atoms or radicals are highly reactive and they will oxidize almost anything  including viruses, bacteria, organic and inorganic compounds) in contacts, making ozone an enormously powerful disinfectant and oxidizer. 

<img src="doc/ozone.jpg" style="zoom:50%;" />

:warning: **Ozone with concentration higher than 1 ppm has adverse effects on human health and the use of ozone for air disinfection is generally not recommended if people are around.** :warning:

* Ozone breaks down to oxygen with a half life of about 20 minutes ( at 20 degrees Celsius )
* Decomposition of 2 mol (96 g) ozone to 3 mols of oxygen requires 286 kJ energy

### Sterilization protocol

The standard program adopted involves increasing the ozone level over a period of 15 min to 25 ppm, maintaining this level for 10 min, at which point the humidifier was activated to produce a rapid burst of water vapor. This should result in the RH increasing to > 95% within 5 min. Following this the humidifier and generator are switched off and the catalytic converter is switched on, which results in decrease in ozone to < 1 ppm within 15 min. [Hudson et al.](doc/Ozone_Science_and_Engineering_Pub_Jan091.pdf)

### Device requirements

* Effective minimum concentration of ozone is 25 ppm **~50 mg/m3** *( 1 ppm (O3) = 2.14 mg/m3 )*
* To meet protocol parameters **for every cubic meter** a generator capacity of **~200 mg/h** is required.
* Air humidity shall be controlled so that RH could be increased to **> 95%** rapidly.
* There should be a **timed lock**, to prevent the user to open the device while operating.
* There should be a clear **sign** indicating potentially dangerous oxidant levels inside the device.
* Ozone **levels** should be either measured or predicted by its decomposition model.
* Temperature and humidity can be easily monitored. *( supporting the level prediction )*

### Block diagram

![](doc/blocks.png)