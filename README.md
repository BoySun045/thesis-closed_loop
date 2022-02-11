<!-- <p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://i.imgur.com/6wj0hh6.jpg" alt="Project logo"></a>
</p> -->

 <font size="5">
 <h3 align="center">Intergrated Perception and Control Pipeline</h3>
</font>

<!-- <div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div> -->

---

<p align="center"> This is a cool project.
    <br> 
</p>

## 📝 Table of Contents

- [TODO](#TODO)
- [About](#about)
- [Getting Started](#getting_started)
<!-- - [Deployment](#deployment) -->
<!-- - [Usage](#usage) -->
<!-- - [Built Using](#built_using) -->
- [Running the package](#tests)
<!-- - [TODO](../TODO.md) -->
<!-- - [Contributing](../CONTRIBUTING.md) -->
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)

## 📝 TODO <a name = "TODO"></a>

- ✅ Visualize the 2D keypoins in heatmap image
- ❌ Visualize stage_cost In Rviz
- ❌ Change Table geometry to be identical with the real setup
- ✅ Adding the depth & pointcloud via "/camera/aligned_depth_to_color/image_raw" topic from RealSense ROS Wrapper
  - need to use ordered pointcloud, or get the 3D pose from depth image, currently trying the later one
    - ✅ Visualize the depth bbox via a heuristic first in visulization_msg node
      - This is hard-coded for a static scene now

- ✅ Add a customed cpp msgs package, in kp wrapper, and include in the object modelling pkg
- ❌ Add a process to deal with the invalid keypoint in modelling pkg 
- ❌ Having bug in primitive frame calculating in modelling pkg
- ❌ Seperate out the modelling pkg from the sampling-based-controller

## 🧐 About <a name = "about"></a>

Write about 1-2 paragraphs describing the purpose of your project.

## 🏁 Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them.

```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running.

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo.

## 🔧 Running the package <a name = "tests"></a>

Explain how to run the automated tests for this system.

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

<!-- ## 🎈 Usage <a name="usage"></a>

Add notes about how to use the system.

## 🚀 Deployment <a name = "deployment"></a>

Add additional notes about how to deploy this on a live system.

## ⛏️ Built Using <a name = "built_using"></a>

- [MongoDB](https://www.mongodb.com/) - Database
- [Express](https://expressjs.com/) - Server Framework
- [VueJs](https://vuejs.org/) - Web Framework
- [NodeJs](https://nodejs.org/en/) - Server Environment -->

## ✍️ Authors <a name = "authors"></a>

- [@BoySun045](https://github.com/BoySun045) - Msc. Thesis at ASL, ETH

<!-- See also the list of [contributors](https://github.com/kylelobo/The-Documentation-Compendium/contributors) who participated in this project. -->

## 🎉 Acknowledgements <a name = "acknowledgement"></a>

- Hat tip to anyone whose code was used
- Inspiration
- References
