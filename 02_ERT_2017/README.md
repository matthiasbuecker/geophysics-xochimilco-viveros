# Electrical resistivity tomography (ERT) measurements 2017

This directory contains the electrical resistivity tomography (ERT) raw data collected at [Viveros de Netzahualcóyotl in Xochimilco](https://goo.gl/maps/K7xEC44MdnQno9CG8) during September 2017. The following table lists the available ERT lines, which are grouped into a shallow survey (L1-L10) and a deep survey (Y1-Y7).

| Line ID | Acquisition date | Electrodes (spacing) | Total length | Orientation | Remark |
| --- | --- | --- | --- | --- | --- |
| L1 | 09/05/2017 | 48 (3 m) | 141 m | NW > SE | Drilling XOC17-I @ 105 m along line |
| L2 | 09/05/2017 | 48 (3 m) | 141 m | NW > SE | |
| L3 | 09/05/2017 | 48 (3 m) | 141 m | NW > SE | |
| L4 | 09/05/2017 | 48 (3 m) | 141 m | NW > SE | |
| L5 | 09/06/2017 | 48 (3 m) | 141 m | NW > SE | |
| L6 | 09/07/2017 | 48 (3 m) | 141 m | NW > SE | |
| L7 | 09/07/2017 | 48 (3 m) | 141 m | NW > SE | |
| L8 | 09/06/2017 | 41 (5 m) | 200 m | SW > NE | |
| L9 | 09/06/2017 | 40 (5 m) | 195 m | SW > NE | |
| L10 | 09/06/2017 | 41 (5 m) | 200 m | SW > NE | |
| Y1 | 09/11/2017 | 48 (10 m) | 470 m | NW > SE | 1st part of roll along |
| Y2 | 09/11/2017 | 48 (10 m) | 470 m | NW > SE | 2nd part of roll along |
| Y3 | 09/11/2017 | 48 (10 m) | 470 m | NW > SE | 3rd part of roll along |
| Y4 | 09/11/2017 | 48 (10 m) | 470 m | NW > SE | 1st part of roll along |
| Y5 | 09/11/2017 | 48 (10 m) | 470 m | NW > SE | 2nd part of roll along |
| Y6 | 09/11/2017 | 48 (10 m) | 470 m | NW > SE | 3rd part of roll along |
| Y7 | 09/11/2017 | 48 (10 m) | 470 m | NW > SE | 4rd part of roll along |

Lines L1-L10 were measured with a Dipole-Dipole (DD), a Wenner (We) and a Pole-Dipole (PD) configuration, 

Line Y1-Y7 were measured with a DD and a We configuration. Lines Y1-Y3 and Y4-Y7 were carried out as roll-along profiles, respectively, with overlaps of 24 electrodes.

Data is provided as binary files *.bin*, which can be read, processed and exported to *.txt* files with the Prosys II software available free of charge on the homepage of the manufacturer of the measuring device (http://www.iris-instruments.com/download.html#processing).

Please note that for practical reasons, the electrode spacing was set to 1 m during the acquisition. Thus, during the processing, geometric factors (and apparent resistivities) need to be recomputed employing the actual electrode spacings given in the above table.

The study area is located right next to the deep groundwater well [Santa Catarina 3](https://goo.gl/maps/Q2ooHxkMeXRhmgLB8). The exact positions (datum: WGS84) of the first and the last electrodes of each ERT line are listed in the file *ERT2017_positions.txt*. The positions of the infinite electrodes of the PD measurements are included, too. For convenience, we also include a GoogleEarth *.kml* file containing lines and electrode positions. 

None of the lines includes significant topographical variations.

## Financial support

Financial support for the data acquisition was provided by the UNAM (DGAPA-PAPIIT-IN107416-2: "Paleoambientes del Pleistoceno tardío en la cuenca de Xochimilco"). Matthias Bücker’s participation in this study was partly funded by a scholarship awarded  by the TU-Wien.

## Acknowledgements

We thank Sergio Rodríguez Elizarrarás from the Instituto de Geología (IGL) of the UNAM, who kindly provided the Syscal Pro Switch measuring system. Special thanks to Elena Centeno (IGL) and the staff from Instituto de Geología and Instituto de Geofísica, UNAM for their support. Vianey Guadalupe Cruz Fitz, Ismerai Yazmín Reyes Corona, Marco Albarrán, and Johannes Bücker assisted during the geoelectrical field work in Xochimilco. We acknowledge the personnel of the Viveros de Netzahualcóyotl in Xochimilco without whose cooperation the realization of the field survey would not have been possible.
