This custom solar harvester board is built around the AEM10330 energy management IC. It efficiently captures power from a solar source and intelligently distributes it between the load and the storage element. A priority selector allows the user to choose whether the harvested energy is directed first to the load or to charge the supercapacitor, enabling flexible operation depending on system requirements. Compact and efficient, the design provides a robust solution for low-power, self-sustaining devices and IoT applications.

The 1F capacitor was chosen to be large enough to power an ultra low power sensor that used an average of 4.5uA. You can calculate the required capacity based on your energy needs.

The harvester is reported to draw a maximum of 30mA from a solar panel and provide maximum 60mA to its output. The quiescent current is around 1uA. In my circuit, the settings are:

HIGH POWER MODE

VLOAD,MIN	VLOAD,MID	VLOAD,TYP 	VLOAD,MAX
3.15 V 		3.23 V 		3.28 V 		3.34 V

VOVDIS		VCHRDY		VOVCH
0.20 V 		1.00 V 		2.60 V

Please see the AEM10330 datasheet
https://e-peas.com/documents/AEM10330/DS-AEM10330.pdf
