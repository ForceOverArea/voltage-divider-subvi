# voltage-divider-subvi
A sub-vi for LABVIEW 2019 because I'm sick of copying the same file over and over again

# To use this:
1. Click on 'r_from_voltage_divider.vi' above and then click the download button on the right.
2. In the block diagram menu of your LABVIEW project, right click and select 'Select a VI...'
3. Choose the .vi from the location you saved it to

# Inputs/outputs:
Known Resistance: (input)
The resistance (ohms) of your known resistor (duh.) This can be supplied from a numeric control or measured in real time via DMM port.

Supplied voltage: (input)
The voltage applied across both resistors. This can also be supplied from a numeric control or measured in real time via analog in (ai0, ai1) port.

Measured voltage: (input)
The voltage measured across your unknown resistor/thermistor/photoresistor/strain gauge/etc.

Measured resistance: (output)
The resistance of the unknown resistor in ohms. This is what you should convert to temperature, wind speed, light level, strain, etc.
