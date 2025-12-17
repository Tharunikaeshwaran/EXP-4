# EXP-4
EXP. NO. 4. 		HALFWAVE  AND FULL WAVE  RECTIFIERS

AIM: To study the characteristics of half wave, full wave and bridge rectifier with and without filter and calculate the ripple factor, rectification efficiency and % regulation.

COMPONENTS  AND  EQUIPMENT  REQUIRED:  Diodes,  Resistor,  Transformer,  Voltmeter, Ammeter, Breadboard and CRO.

THEORY: Rectifier changes ac to dc and it is an essential part of power supply. The unique property of a diode, permitting the current to flow in one direction, is utilised in rectifiers.

Half Wave Rectifier


Mains power supply is applied at the primary of the step-down transformer. All the positive half cycles of the stepped down ac supply pass through the diode and all the negative half cycles get eliminated. Peak value of the output voltage is less than the peak value of the input voltage by 0.6V because of the voltage drop across the diode.
For a half wave rectifier, Vrms = Vm/2 and Vdc = Vm/π: where Vrms = rms value of input, Vdc = Average value of input and Vm = peak value of output.


Full Wave Rectifier
During the positive half cycle of the transformer secondary voltage, diode     is forward biased and      is reverse biased. So a current flows through the diode     , load resistor      and upper half of the transformer  winding.  During  the  negative  half  cycle,  diode       becomes  forward  biased  and becomes reverse biased. The current then flows through the diode     , load resistor      and lower half of the transformer winding. Current flows through the load resistor in the same direction during both the half cycles. Peak value of the output voltage is less than the peak value of the input voltage by 0.6V
because of the voltage drop across the diode.
During the positive half cycle of the secondary voltage, diodes      and      are forward biased and diodes and      are reverse biased. Therefore, current flows through the secondary winding, diode     , load resistor
and diode     . During the negative half cycle,      and      are forward biased and diodes      and      are reverse biased. Therefore, current flows through the secondary winding, diode     . Load resistor       During both the half cycles, the current flows through the load resistor in the same direction. Peak value of the output voltage is less than the peak value of the input voltage by 1.2V due to the voltage drop across two diodes. The ripple factor of the bridge rectifier is the same as that of full wave rectifier.
All rectifier outputs contain considerable amount of ripple in addition to the DC component. In order to avoid AC components, a filter is connected at the output of the rectifier.

Capacitor input filter, choke input filter, RC, CRC, LC, and CLC filters are the usually used filters. Capacitor input filter is the simplest and cheapest. A high value capacitor C is connected in shunt with the load resistor     . Capacitor charges to peak voltage      when the half cycle appears at the output. After the peak value is passed, the capacitor discharges through the load resistor slowly since the diode is reverse biased by the capacitor voltage. Before the capacitor voltage drops substantially, next output cycle arrives and the capacitor recharges to peak.

Rectifier Efficiency

Rectifier efficiency is defined as the ratio of DC output power to the input power from the AC supply. Even with ideal rectifiers with no losses, the efficiency is less than 100% because some of the output power is AC power rather than DC which manifests as ripple superimposed on the DC waveform.
PROCEDURE:

1.   Wire up the half wave rectifier circuit without capacitor after testing all the components.

2.   Switch on the main supply. Observe the transformer secondary voltage waveform and output voltage waveform across the load resistor, simultaneously on the CRO screen. Note down       and calculate
3.   Connect the capacitor filter and observe the waveforms. Note down and calculate ripple factor, rectifier efficiency and %regulation using the expressions. Repeat for different capacitor values.
4.   Repeat the above steps for full wave and bridge rectifiers.

CIRCUIT DIAGRAMS

Half wave rectifier with filter:
![WhatsApp Image 2025-12-17 at 08 15 13_bbc21418](https://github.com/user-attachments/assets/1827401b-746b-45c8-8f3d-1948855f5117)

Waveform:
![WhatsApp Image 2025-12-17 at 08 15 15_14ee5f56](https://github.com/user-attachments/assets/bb75c750-0362-4389-acab-6318a7211cef)


TABULAR COLUMN
<table>
  <tr>
    <th colspan="2">Input Voltage</th>
    <th colspan="4">Output Voltage</th>
  </tr>
  <tr>
    <th rowspan="2">Vm (V)</th>
    <th rowspan="2">t (ms)</th>
    <th colspan="2">Without Filter</th>
    <th colspan="2">With Filter</th>
  </tr>
  <tr>
    <th>Vm (V)</th>
    <th>t (ms)</th>
    <th>Vm (V)</th>
    <th>t (ms)</th>
  </tr>
  <tr>
    <td>100</td>
    <td>20</td>
    <td>100</td>
    <td>10</td>
    <td>100V, 5V</td>
    <td>5 ms, 25 ms</td>
  </tr>
</table>
Full wave rectifier with filter:
![WhatsApp Image 2025-12-17 at 08 15 14_4f3a7878](https://github.com/user-attachments/assets/b4b51eb6-8f9e-44d2-924f-86ac9aee9fa8)

WAVEFORM:
![WhatsApp Image 2025-12-17 at 08 15 15_55c15cba](https://github.com/user-attachments/assets/c7df6ea9-1369-4d67-bfcd-f9135c18ca15)


Tabular form:
<td>50</td>
    <td>20</td>
    <td>50</td>
    <td>5</td>
    <td>50, 46</td>
    <td>5 ms, 14 ms</td>
  </tr>
</table>

RESULT:

Input and Output waveforms of a half and full bridge-wave with /without filter are observed and plotted.
