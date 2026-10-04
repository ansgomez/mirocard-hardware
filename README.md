# MiroCard Hardware Files

Hardware design files for the MiroCard, a batteryless, light-powered BLE smart card
(TI CC2650 MCU, e-peas AEM10941 harvester, Epishine organic solar cell).

The current version, `MiroCard_V2.0/`, contains:

* `Datasheet_MiroCard_V2.pdf` – datasheet
* `Schematics_MiroCard_V2.pdf` – schematics
* `Altium_Files_MiroCard_V2/` – Altium project for the PCB design and production
  (schematics, PCB, libraries, Gerber/drill/pick-and-place outputs, BOM and STEP model)

Contact: [Andres Gomez](https://andresgomez.ch).

## Contributors

* Sinan Uyan (PCB layout)
* Andres Gomez

## MiroCard project

Project website: <https://ansgomez.github.io/mirocard-website/>

The MiroCard is a batteryless, light-powered BLE smart card, designed by Andres Gomez
(Miromico AG) and inspired by the
[Transient BLE Node](https://gitlab.ethz.ch/tec/public/employees/sigristl/transient_ble_node)
project developed at ETH Zurich. It was presented in:

> Andres Gomez. 2020. *Demo Abstract: On-Demand Communication with the Batteryless MiroCard.*
> In The 18th ACM Conference on Embedded Networked Sensor Systems (SenSys '20).
> [doi:10.1145/3384419.3430440](https://doi.org/10.1145/3384419.3430440)

Related repositories:

| Repository | Contents |
| --- | --- |
| **mirocard-hardware** (this repository) | Hardware: datasheet, schematics and Altium PCB project (MiroCard V2.0) |
| [mirocard-contiki-ng](https://github.com/ansgomez/mirocard-contiki-ng) | Firmware: Contiki-NG fork with the MiroCard platform and example applications |
| [miroreader-app](https://github.com/ansgomez/miroreader-app) | Android app to receive and display MiroCard beacons |
| [mirocard-scanner-python](https://github.com/ansgomez/mirocard-scanner-python) | Python scripts to scan for and decode MiroCard beacons (bluepy) and discover devices (gattlib) |
| [mirocard-scanner-mqtt](https://github.com/ansgomez/mirocard-scanner-mqtt) | Node.js bridge forwarding MiroCard beacons to an MQTT broker |
| [mirocard-scanner-influx](https://github.com/ansgomez/mirocard-scanner-influx) | Node.js bridge storing MiroCard beacons in InfluxDB |
| [mirocard-webid](https://github.com/ansgomez/mirocard-webid) | Web Bluetooth demo page for identification and sensor readout |
| [mirocard-postprocessing](https://github.com/ansgomez/mirocard-postprocessing) | Jupyter notebook to post-process RocketLogger power measurements |
| [mirocard-plotly](https://github.com/ansgomez/mirocard-plotly) | Plotly Dash web app visualizing a RocketLogger measurement |

## Copyright and License

The MiroCard and MiroReader app are designed by Andres Gomez, inspired by the
[Transient BLE Node](https://gitlab.ethz.ch/tec/public/employees/sigristl/transient_ble_node)
project developed at ETH Zurich. The Transient BLE Node project is released under the
Creative Commons Attribution 4.0 International License (CC BY 4.0); the Altium libraries
`MiroCard/TransientBLE.SCHLIB` and `MiroCard/TransientBLE.PcbLib` originate from that project.

The MiroCard hardware files are released under the BSD 3-Clause License, see [LICENSE](LICENSE).

Copyright: (c) 2020, Andres Gomez, Miromico AG

Copyright: (c) 2017-2020, ETH Zurich, Computer Engineering Group and Microelectronics Design Center.
