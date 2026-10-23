# Location and Capacity of Electric Vehicle Battery Swapping Stations (Matlab Code Implementation)

​  
Including complete code and data.
1. Overview - As the number of electric vehicles (EVs) continues to increase annually, The construction coverage of electric vehicle charging and swapping infrastructure in cities is becoming increasingly widespread. The site selection and capacity planning of charging and battery swap infrastructure have become an indispensable part of urban transportation network planning and construction. This article is about "centralized charging". This study and discussion are made on the location and capacity planning of battery swap stations in the unified distribution "charging mode". Further research and improvement on the siting and capacity planning issues of charging and battery swap infrastructure in this mode. Different from the charge mode, The battery swapping station and the central charging station should be considered together in the battery swapping mode. Conduct the site selection and capacity planning for battery swap stations.
The location and capacity planning of battery swap stations must first consider the daily charging and battery replacement demand for electric vehicles in the local area. Therefore, this paper focuses on the prediction of daily charging load for electric vehicles. Firstly, the charging behavior patterns of four different types of electric vehicles based on the order-based charging strategy are introduced. Monte Carlo method is used to randomly select the starting charging time distribution and daily driving distance of electric vehicles. Calculate the starting charge state and the charging time required for the vehicle. The daily charging total load of four types of electric vehicles is respectively obtained. The daily charging load of the four types of electric vehicles is added up to obtain the total daily charging load for electric vehicles.
2. Running Results 2.1 The maximum utility of electric vehicle charging
Editor
2.2 Site selection for battery swap stations
Editor
2.3 EVs_4kw Editing
Editor
2.4 EVs_7kW​edit
Editor
Editor
Editor
2.5 No EVs​Edit
Editor
Editor
2.6 Best Distance Edit
Editor
Editor
Editor
3. Matlab code implementation: This document only showcases a portion of the code, the full code can be found in:
%% Visualization\n\n% Current / Load capacity\nfigure\nbar(peak_line_currents)\nhold on\nplot(1:length(peak_line_currents), ones(size(peak_line_currents)), 'k--')\naxis([1 length(peak_line_currents) 0 1.5])\nxlabel('Number of lines')\nylabel('Current / Load capacity')\ngrid on\n\n\n% Load voltage\nfigure\nbar(peak_node_voltages,'BaseValue',1)\nhold on\nplot(1:length(peak_node_voltages), 1.1* ones(size(peak_node_voltages)), 'k--')\nplot(1:length(peak_node_voltages), 0.9* ones(size(peak_node_voltages)), 'k--')\naxis([1 length(peak_node_voltages) 0.8 1.2])\nxlabel('Load number')\nylabel('Voltage (p.u.)')\ngrid on\n\n% The apparent power of the transformer\nfigure\nplot(1:length(trafo_power), trafo_power)\nhold on\nplot(1:length(trafo_power), 0.8 * ones(1,length(trafo_power)), 'k--')\nxlim([1 length(trafo_power)])\nxlabel('Time(min)')\nylabel({'Transformer', 'Imaginary power(MVA)'})\ngrid on\n  
4. References
[1] Wu Yuan, Ye Ning. Dual-Objective Location and Capacity Model for Electric Vehicle Charging Stations in Urban Road Networks [J]. Shanxi University Journal (Natural Science Edition), 2021, 44(04): 695-704. DOI: 10.13451/j.sxu.ns.2021045.
[2] Zhang Zhaoxuan. Location and Capacity of Electric Vehicle Battery Swapping Stations Based on Improved Bat Algorithm [D]. Guangdong University of Technology, 2021. DOI: 10.27029/d.cnki.ggdgu.2021.001682.

## Images

![Location selection and capacity determination for electric vehicle battery swap stations (Matlab code implementation)](01.png)
![Location selection and capacity determination for electric vehicle battery swap stations (Matlab code implementation)](02.png)
![Location selection and capacity determination for electric vehicle battery swap stations (Matlab code implementation)](03.png)
![Location selection and capacity determination for electric vehicle battery swap stations (Matlab code implementation)](04.png)
![Location selection and capacity determination for electric vehicle battery swap stations (Matlab code implementation)](05.png)
![Location selection and capacity determination for electric vehicle battery swap stations (Matlab code implementation)](06.png)
![Location selection and capacity determination for electric vehicle battery swap stations (Matlab code implementation)](07.png)
![Location selection and capacity determination for electric vehicle battery swap stations (Matlab code implementation)](08.png)
![Location selection and capacity determination for electric vehicle battery swap stations (Matlab code implementation)](09.png)
![Location selection and capacity determination for electric vehicle battery swap stations (Matlab code implementation)](10.png)
![Location selection and capacity determination for electric vehicle battery swap stations (Matlab code implementation)](11.png)
![Location selection and capacity determination for electric vehicle battery swap stations (Matlab code implementation)](12.png)
![Location selection and capacity determination for electric vehicle battery swap stations (Matlab code implementation)](13.png)
![Location selection and capacity determination for electric vehicle battery swap stations (Matlab code implementation)](14.png)
![Location selection and capacity determination for electric vehicle battery swap stations (Matlab code implementation)](15.png)
![Location selection and capacity determination for electric vehicle battery swap stations (Matlab code implementation)](16.png)
![Location selection and capacity determination for electric vehicle battery swap stations (Matlab code implementation)](17.png)
![Location selection and capacity determination for electric vehicle battery swap stations (Matlab code implementation)](18.png)
![Location selection and capacity determination for electric vehicle battery swap stations (Matlab code implementation)](19.png)
![Location selection and capacity determination for electric vehicle battery swap stations (Matlab code implementation)](20.png)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
