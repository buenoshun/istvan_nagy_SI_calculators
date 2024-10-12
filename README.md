# istvan_nagy_SI_calculators
These are MS Excel files containing hundreds of equations. They are used for high-speed digital board design projects.

To download: Click the zip file, on the next page click "view raw" to download it.
They are also hosted on my personal website at: buenos.extra.hu
This is a snapshot taken at oct/12-2024

S-Parameter Smoothie 2021
This template can smooth out the measurement noise in an S-parameter file, providing a smooth curve. Use on 2-port Voltage Regulator models, or board PDN models, obtained from a VNA measurement.

S-parameter Permutations 2023
This template can take an S-parameter file from a PCB layout extractor, and create 4 new S-par files, with impedance and insertion loss variation. This can be used before running a batch SI simulation, that checks all combinations of different boards’ manufacturing tolerances, for interface compliance verification.

Design Assurance Calculator 2024
This template calculates voltage/temperature stress on resistors, capacitors, derated maximum power for resistors, derated maximum voltage and derated capacitance for capacitors. It also provides RX to TX connectivity check for SERDES signals, and finally a power net total capacitance finder. Most of this analysis is traditionally done manually, but this sheet extracts information from board data (Allegro report files), auto finds relevant components, sorts them automatically, so the user just needs to fill in the last bit of data.

PCB Interconnect Timing Analysis Calculator   2007-2010 
With this tool, we can determine PCB trace length cosntraints or we can check if the already designed system meets the timing requirements with setup/hold magins, or not. Timing analysis is very recommended for common clock synchronous, asynchronous, sourcce-synchronous and clock forwarding PCB buses.

Dielectric Constant Frequency Compensation Calculator  2009
Most of the PCB trace impedance calculators dont take the signal frequency into account. With this calculator, you can fill this gap, by providing frequency-pre-compensated dielectric constant to them. If DK and DF are provided by the material vendor at f1 frequency, but we wanto know DK and DF at a different f2 frequency, with this template we can calculate them.
