# actuated-umi-gripper


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/actuated-umi/actuated-umi-gripper">
    <img src="assets/actuated-UMI.png" alt="actuated-umi-gripper" height="200">
  </a>

  <h3 align="center">Actuated UMI Gripper</h3>
  <h5 align="center">Erik Helmut*, Niklas Funk*, Tim Schneider, Jan Peters<br><em>*Equal contribution</em></h5>
  

  <p align="center">
    This repository provides an actuated, open-source version of the popular <a href="https://umi-gripper.github.io">UMI gripper</a>. Designed to be cost-effective and modular, this gripper uses 3D-printed components to ensure accessibility and reproducibility. With a Dynamixel motor for actuation, you can assemble the gripper yourself using the included design files and guidelines. This repository contains the mechanical design files and printable components, enabling you to build and customize the gripper to suit your needs. <br />
    <a href="https://actuated-umi.github.io"><strong>For more information about actuated-UMI, visit the project page »</strong></a> <br />
  </p>
</div>


<!-- Citation -->
## Citation
If you use this project in your research, please cite it.

```
@inproceedings{helmut2024actuatedumi,
  author = {Helmut, Erik and Funk, Niklas and Schneider, Tim and Peters, Jan},
  title = {Actuated Version of the Universal Manipulation Interface Gripper},
  year = {2024},
  url  = {https://actuated-umi.github.io/}
}
```

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#bill-of-materials-bom">Bill of Materials (BoM)</a>
    </li>
    <li>
      <a href="#3d-printing-details">3D Printing Details</a>
    </li>
    <li>
      <a href="#assembly-guide">Assembly Guide</a>
    </li>
    <li>
      <a href="#usage">Usage</a>
    </li>
    <li>
      <a href="#acknowledgements">Acknowledgements</a>
    </li>
    <li>
      <a href="#questions-and-contributing">Questions and Contributing</a>
    </li>
  </ol>
</details>


<!-- Bill of Materials -->
## Bill of Materials (BoM)
Coming soon.


<!-- 3D Printing Details -->
## 3D Printing Details
Coming soon.


<!-- Assembly Guide -->
## Assembly Guide
We provide a comprehensive, step-by-step assembly guide to help you build the gripper with ease. The video tutorial walks you through each step, ensuring a clear and straightforward assembly experience. You can find the video tutorial below:

[![Assembly Guide Video](https://img.youtube.com/vi/YOUR_VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=YOUR_VIDEO_ID)


<!-- Usage -->
## Usage
To use the gripper after it is fully assembled, you will need the appropriate software to control it. We recommend using the [Dynamixel API](https://github.com/TimSchneider42/dynamixel-api) developed by our team. This API provides a comprehensive set of tools and functions to interface with Dynamixel motors, which are used in the actuated UMI gripper.

The repository includes detailed instructions on how to install and use the API, as well as example code to get you started. By following the guidelines provided in the Dynamixel API repository, you can easily integrate the gripper into your projects and control its movements programmatically.


<!-- Acknowledgements -->
## Acknowledgements
This work heavily builds upon the following prior efforts. It would not have been possible without them.

- C. Chi, Z. Xu, C. Pan, E. Cousineau, B. Burchfiel, S. Feng, R. Tedrake, and S. Song, "Universal Manipulation Interface: In-The-Wild Robot Teaching Without In-The-Wild Robots," in Proc. Robotics: Science and Systems (RSS), 2024. We used the [UMI Gripper](https://umi-gripper.github.io) as a key reference for our design, aiming to closely replicate its functionality and form. 
- Clayton Haight, creator of [OpenGrip](https://github.com/clayhaight01/OpenGrip). The OpenGrip gripper mechanism served as the initial design starting point for our own gripper development.
- Stan Markwell, for providing CAD files of the ROBOTIS U2D2 Power Hub Board & U2D2, available on [GrabCAD](https://grabcad.com/library/robotis_u2d2_power_hub_board-1).


<!-- License -->

<!-- Questions and Contributing -->
## Questions and Contributing
If you have any questions or need help with building the gripper, please create an <a href="https://github.com/actuated-umi/actuated-umi-gripper/issues/new/">issue</a>.

We also welcome contributions to this repository, including new 3D models or other improvements. If you would like to contribute, please <a href="https://github.com/actuated-umi/actuated-umi-gripper/fork">fork</a> this repository and submit a <a href="https://github.com/actuated-umi/actuated-umi-gripper/compare">pull request</a> with your changes, or reach out to erik.helmut1 [at] gmail [dot] de.
