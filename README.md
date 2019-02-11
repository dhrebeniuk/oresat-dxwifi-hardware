# oresat-dxwifi-hardware
OreSat communication subsystem for high speed data (1 Mbps) using 2.4 GHz WiFi between the spacecraft and ground.

We intend to use "rdinary WiFi (IEEE 802.11b) as a high speed satellite communication system. What is _not_ ordinary is that we run the radio under the amateur radio rules and regulations (FCC Part 97) and thus can increase power levels and antenna gains necessary to make the link budget work.

### Ordinary WiFi
The plan is to use the Qualcomm Atheros AR9271 USB to WiFi adapter because of the driver support in Linux.

### Non ordinary bi-directional power amplifier
This project is intended to operate under the Amateur Radio Service [47CFR97](https://www.gpo.gov/fdsys/pkg/CFR-1996-title47-vol5/pdf/CFR-1996-title47-vol5-part97.pdf) whereby larger power levels and higher gain directional antennas can be used within the [13 cm band](https://en.wikipedia.org/wiki/13-centimeter_band) to close the link.

NB:  There are other DxWiFi materials on the PSAS GitHub repo, but those repos are deprecated.

Link budgets can be found [here](https://github.com/oresat/oresat-dxwifi-hardware/tree/master/Link-Model).
