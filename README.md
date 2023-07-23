# Open Soure Hardware Optics and Mechanics Design for Fluorescence Activated (Microfluidic) Droplet Sorting (FADS) [![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

It in cludes the design of positioning, lasers, filters, detectors, fixtures for open droplet sorting. Note that the design in this repository is quite different to literatures designs. The set-up has been re-designed in order to make it more low-cost (estimated parts cost 20.000 USD, mainly for optical filters, detectors and laser) and open source, including hardware, software and accessible fabrication of parts where possible. Also, a number of updates and improvements have been made over the current state-of the art of droplet sorters, inspired by technical advances in the related field of flow-cytometry.

If you are wondering what the sorting of microfluidic droplets is, we reccomend the following litertature:
* The original [droplet sorting publication (2009)](https://doi.org/10.1039/b902504a) using electrical droplet actuacion and fluorescence detection.
* A review of [active droplet sorting methods (2017)](https://doi.org/10.1039/c6lc01435f ), inclduing alternatives to the dielectrophoresis used here.
* A review of [advances on sorting and detection methods (2021)](https://doi.org/10.3389/fchem.2021.666867) in the context of directed enzyme evolution.
* And a [detailed protocol (2023)](https://doi.org/10.1038/s41596-022-00796-2) of how to assemble a current state-of-the-art droplet sorting set-up as it exsists in several research labs around the world (estimated parts costs 200.000 USD).

## Related documents:

* The open source FPGA controll is documented seperately: https://github.com/MakerTobey/Open_FADS_FPGA_control
* The microfluidic chip is positioned with an [open source SQUID microscopy stage](https://github.com/wenzel-lab/squid-motorized-stage).
* And the otptical detection arm assembly is based on the [Open-UC2 3d printed optics cubes](https://github.com/openUC2/UC2-GIT).
* The modified and new Open-UC2 compatible cubes can be found in the STL folder of this repository, and all modifyable design files are openly availble in the cloud [here on OnShape](https://tinyurl.com/WenzelLabUC2), where you can view, export and copy (to modify) the project designs.

A few examples of modified or new designs for this project:

<p align="center">
<img src="./images/filter_cube_finished_(green_blue).jpg" height="360">
<img src="./images/objective_insert_as_filter_in_cube.jpg" height="360">
</p>
<p align="center">
<img src="./images/detector_SiPM_holder_assembled.jpg" height="310">
<img src="./images/mirror_mount_with_heat_inserts_assembled.jpg" height="310">
</p>
<p align="center">
<img src="./images/detection_arm_assembly.jpg" height="400">
</p>

## Contribute

This is an open project in the Wenzel Lab in Santiago, Chile. If you have any suggestions to improve it or add any additional functions make a pull-request or [open an issue](https://github.com/wenzel-lab/droplet-cytometry-optomechanics/issues/new).
For interactions in our team and with the community applies the [GOSH Code of Conduct](https://openhardware.science/gosh-2017/gosh-code-of-conduct/).

## License

[CERN OHL 2W](LICENSE) © Tobias Wenzel. This project is Open Source Hardware - please acknowledge us when using the hardware or sharing modifications.
