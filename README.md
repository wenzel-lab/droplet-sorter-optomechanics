# Open Soure Hardware Optics and Mechanics Design for Fluorescence Activated (Microfluidic) Droplet Sorting (FADS)

It in cludes the design of positioning, lasers, filters, detectors, fixtures for open droplet sorting. 


## Related documents:

* The open source FPGA controll is documented seperately: https://github.com/MakerTobey/Open_FADS_FPGA_control
* The microfluidic chip is positioned with an [open source SQUID microscopy stage](https://github.com/wenzel-lab/squid-motorized-stage).
* And the otptical detection arm assembly is based on the [Open-UC2 3d printed optics cubes](https://github.com/openUC2/UC2-GIT).
* The modified and new Open-UC2 compatible cubes can be found in the STL folder of this repository, and all modifyable design files are openly availble in the cloud [here on OnShape](https://tinyurl.com/WenzelLabUC2), where you can view, export and copy (to modify) the project designs.

An example of new designs for this project:

<img src="https://github.com/wenzel-lab/Open_FADS_optomechanics/blob/main/images/filter_cube_with_heat_inserts1.jpg" height="300">
<img src="https://github.com/wenzel-lab/Open_FADS_optomechanics/blob/main/images/filter_cube_finished_(green_blue).jpg" height="300">

## Contribution guide

This is an open collaborative project currently lead by Tobias Wenze in the Wenzel Lab in Santiago, Chile; your participation (comments, inputs, contributions, issues) are explicitly welcome!

Please get involved by extending the project or interacting with us by submitting an issue, contact us (e.g. [here](https://ingenieriabiologicaymedica.uc.cl/en/people/faculty/821-tobias-wenzel)). Particular extensions wanted are: Simplify the pyprl library fork to the needed tools in this context; further development of the GUI for the user/experimentor and to change the sorting parameters; collecting custom droplet sorting challenges not currently well addressed by exsisting literature examples; extension to more-dimensional questions (boards with more fast analougue inputs-outputs, sorting based on spectral analysis with detector array, sorting based on 2D detector arrays such as imaging detectors, sorting with additional sensor to verify positive sorting events, etc.).
