![Example Tasks created with ORBIT](docs/source/_static/tasks.jpg)

---

# Orbit

[![IsaacSim](https://img.shields.io/badge/IsaacSim-2023.1.1-silver.svg)](https://docs.omniverse.nvidia.com/isaacsim/latest/overview.html)
[![Python](https://img.shields.io/badge/python-3.10-blue.svg)](https://docs.python.org/3/whatsnew/3.10.html)
[![Linux platform](https://img.shields.io/badge/platform-linux--64-orange.svg)](https://releases.ubuntu.com/20.04/)
[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)](https://pre-commit.com/)
[![Docs status](https://img.shields.io/badge/docs-passing-brightgreen.svg)](https://isaac-orbit.github.io/orbit)
[![License](https://img.shields.io/badge/license-BSD--3-yellow.svg)](https://opensource.org/licenses/BSD-3-Clause)

<!-- TODO: Replace docs status with workflow badge? Link: https://github.com/isaac-orbit/orbit/actions/workflows/docs.yaml/badge.svg -->

**Orbit** is a unified and modular framework for robot learning that aims to simplify common workflows
in robotics research (such as RL, learning from demonstrations, and motion planning). It is built upon
[NVIDIA Isaac Sim](https://docs.omniverse.nvidia.com/isaacsim/latest/overview.html) to leverage the latest
simulation capabilities for photo-realistic scenes and fast and accurate simulation.

Please refer to our [documentation page](https://isaac-orbit.github.io/orbit) to learn more about the
installation steps, features, tutorials, and how to set up your project with Orbit.

## Announcements

* [17.04.2024] [**v0.3.0**](https://github.com/NVIDIA-Omniverse/orbit/releases/tag/v0.3.0):
  Several improvements and bug fixes to the framework. Includes cabinet opening and dexterous manipulation environments,
  terrain-aware patch sampling, and animation recording.

* [22.12.2023] [**v0.2.0**](https://github.com/NVIDIA-Omniverse/orbit/releases/tag/v0.2.0):
  Significant breaking updates to enhance the modularity and user-friendliness of the framework. Also includes
  procedural terrain generation, warp-based custom ray-casters, and legged-locomotion environments.

## Contributing to Orbit

We wholeheartedly welcome contributions from the community to make this framework mature and useful for everyone.
These may happen as bug reports, feature requests, or code contributions. For details, please check our
[contribution guidelines](https://isaac-orbit.github.io/orbit/source/refs/contributing.html).

## Troubleshooting

Please see the [troubleshooting](https://isaac-orbit.github.io/orbit/source/refs/troubleshooting.html) section for
common fixes or [submit an issue](https://github.com/NVIDIA-Omniverse/orbit/issues).

For issues related to Isaac Sim, we recommend checking its [documentation](https://docs.omniverse.nvidia.com/app_isaacsim/app_isaacsim/overview.html)
or opening a question on its [forums](https://forums.developer.nvidia.com/c/agx-autonomous-machines/isaac/67).

## Support

* Please use GitHub [Discussions](https://github.com/NVIDIA-Omniverse/Orbit/discussions) for discussing ideas, asking questions, and requests for new features.
* Github [Issues](https://github.com/NVIDIA-Omniverse/orbit/issues) should only be used to track executable pieces of work with a definite scope and a clear deliverable. These can be fixing bugs, documentation issues, new features, or general updates.

## Acknowledgement

NVIDIA Isaac Sim is available freely under [individual license](https://www.nvidia.com/en-us/omniverse/download/). For more information about its license terms, please check [here](https://docs.omniverse.nvidia.com/app_isaacsim/common/NVIDIA_Omniverse_License_Agreement.html#software-support-supplement).

Orbit framework is released under [BSD-3 License](LICENSE). The license files of its dependencies and assets are present in the [`docs/licenses`](docs/licenses) directory.

## Citing

If you use this framework in your work, please cite [this paper](https://arxiv.org/abs/2301.04195):

```text
@article{mittal2023orbit,
   author={Mittal, Mayank and Yu, Calvin and Yu, Qinxi and Liu, Jingzhou and Rudin, Nikita and Hoeller, David and Yuan, Jia Lin and Singh, Ritvik and Guo, Yunrong and Mazhar, Hammad and Mandlekar, Ajay and Babich, Buck and State, Gavriel and Hutter, Marco and Garg, Animesh},
   journal={IEEE Robotics and Automation Letters},
   title={Orbit: A Unified Simulation Framework for Interactive Robot Learning Environments},
   year={2023},
   volume={8},
   number={6},
   pages={3740-3747},
   doi={10.1109/LRA.2023.3270034}
}
```