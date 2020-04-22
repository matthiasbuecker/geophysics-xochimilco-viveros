# Electrical resistivity tomography (ERT) measurements 2016

This directory contains the electrical resistivity tomography (ERT) raw data analysed and presented in the first case study (section *3.1. Case I: Shallow explortion at Lake Xochimilco*) of the manuscript

Bücker, M., Lozano-Garcia. S., Ortega-Guerrero, B., Caballero-Miranda, M., Pérez, L., Caballero, L., Pita de la Paz, C., Sánchez-Galindo, A., Jesús Villegas, F., Flores Orozco, A., Brown, E., Werne, J., Valero Garcés, B., Schwalb, A., Kemna, A., Sánchez-Alvaro, E., Launizar-Martínez, N., Valverde-Placencia, A., Garay-Jiménez, F. (2017). Geoelectrical and Electromagnetic Methods Applied to Paleolimnological Studies: Two Examples from Desiccated Lakes in the Basin of Mexico. Boletín de la Sociedad Geológica Mexicana, 69(2), 279-298, http://dx.doi.org/10.18268/bsgm2017v69n2a1.

## Overview

ERT and time-domain induced polarization (TDIP) data was collected with a Syscal Pro Switch-48 manufactured by Iris Instruments. Note that TDIP data was not processed and analysed in the above manuscript. Here, we include it for the sake of completeness.

| Line ID | Acquisition date | Electrodes (spacing) | Total length | Orientation |
| --- | --- | --- | --- | --- |
| Xoch1 | 06/21/2016 | 48 (5 m) | 235 m | SE > NW |
| Xoch2 | 06/21/2016 | 48 (5 m) | 235 m | SW > NE |

Both lines where measured with a Dipole-Dipole (DD), a Wenner (We) and a Pole-Dipole (PD) configuration. All lines were measured in the induced polarization (IP) mode, i.e., raw data files also include chargeability data. 

Data is provided as binary files *.bin*, which can be read, processed and exported to *.txt* files with the Prosys II software available free of charge on the homepage of the manufacturer of the measuring device (http://www.iris-instruments.com/download.html#processing). Here, we also include the exported *.txt* files.

Please note that for practical reasons, the electrode spacing was set to 1 m during the acquisition. Thus, during the processing, geometric factors (and apparent resistivities) need to be recomputed employing the actual electrode spacings given in the above table.

Positions (datum: WGS84) of the first and the last electrodes of each ERT line are listed in the file *ERT2016_positions.txt*. The positions of the infinite electrodes of the PD measurements are included, too.

None of the lines includes significant topographical variations.

## Financial support

Financial support for the data acquisition was provided by the UNAM (DGAPA-PAPIIT-IN107416-2:  Pa-leoambientes  del  Pleistoceno  tardío  en  la  cuenca  de  Xochimilco").  Matthias  Bücker’s  participation in this study was partly funded by a scholarship  awarded  by  the  TU-Wien.

## Acknowledgements

We  thank  Sergio Rodríguez Elizarrarás from the Instituto de Geología  (IGL)  of   the  UNAM,  who  kindly  provided  the  Syscal  Pro  Switch  measuring  system.  Special  thanks  to  Elena  Centeno  (IGL)  and  the  staff from Instituto de Geología and Instituto de Geofísica,  UNAM  for  their  support. Rafael Cossío assisted during the geoelectrical field work in Xochimilco. We acknowledge the personnel of the  Viveros de Netzahualcóyotl in Xochimilco without whose cooperation the realization of the field survey would not have been possible.
