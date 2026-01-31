# Orbis

<p align="center">
  <img src="assets/orbis.png">
</p>

<div align="center">

**High Diversity · High Fidelity · Controllability · Simulation Ready**

<a href="https://huggingface.co/datasets/IntimeAI/Orbis" target="_blank"><img src="https://img.shields.io/badge/🤗%20huggingface-dataset-orange.svg" height="22px"></a>
<a href="https://github.com/IntimeAI/Orbis" target="_blank"><img src="https://img.shields.io/badge/github-repo-blue?logo=github" height="22px"></a>
<img src="https://img.shields.io/badge/License-Apache%202.0-green" height="22px">

</div>

## 📖 Dataset Overview
**Orbis** is an open-source collection of high-quality 3D scene datasets that covers multiple spatial scales, ranging from **tabletop (small-scale) scenes** to **complex indoor (medium-scale)**, **urban, and natural (large-scale) environments**. All scenes are **simulation-ready** with comprehensive physical properties, enabling seamless integration with physics engines. Powered by our advanced generative models, these datasets support precise scene editing and customization through multimodal inputs such as text and images. We also provide API capabilities for programmatic access and automated dataset generation at scale.

### High Diversity

Orbis covers a wide spectrum of scene types ranging from **tabletop (small-scale) scenes** to **complex indoor (medium-scale)**, **urban, and natural (large-scale) environments**. Each scene features rich object combinations, diverse layout variations, and realistic spatial configurations.

<div align="center">

<table>
<tr>
<td align="center" style="vertical-align: middle;"><strong>small-scale</strong></td>
<td align="center" style="vertical-align: middle;"><img src="./assets/office table.png" width="200"/></td>
<td align="center" style="vertical-align: middle;"><img src="./assets/kitchen.png" width="200"/></td>
<td align="center" style="vertical-align: middle;"><img src="./assets/bookshelf.png" width="200"/></td>
<td align="center" style="vertical-align: middle;"><strong>+ more</strong></td>
</tr>
<tr>
<td align="center" style="vertical-align: middle;"><strong>medium-scale</strong></td>
<td align="center" style="vertical-align: middle;"><img src="./assets/factory.png" width="200"/></td>
<td align="center" style="vertical-align: middle;"><img src="./assets/interior.png" width="200"/></td>
<td align="center" style="vertical-align: middle;"><img src="./assets/market.png" width="200"/></td>
<td align="center" style="vertical-align: middle;"><strong>+ more</strong></td>
</tr>
<tr>
<td align="center" style="vertical-align: middle;"><strong>large-scale</strong></td>
<td align="center" style="vertical-align: middle;"><img src="./assets/landscape.png" width="200"/></td>
<td align="center" style="vertical-align: middle;"><img src="./assets/city scene.png" width="200"/></td>
<td align="center" style="vertical-align: middle;"><img src="./assets/golf.png" width="200"/></td>
<td align="center" style="vertical-align: middle;"><strong>+ more</strong></td>
</tr>
</table>

</div>


### High Fidelity

Orbis adopts a Physically Based Rendering (PBR) material system with complete texture maps (diffuse, normal, roughness, metalness, etc.) to ensure visual realism and consistency.

### Strong Controllability

Powered by our underlying generative models, scenes can be precisely edited and customized using multimodal inputs such as text descriptions and reference images. Scenes are stored in USD/USDC format, enabling flexible modifications to generate diverse training data tailored to specific requirements.

### Simulation Ready

All scenes come with comprehensive physical properties and seamlessly integrate with mainstream physics engines and simulation platforms (such as Isaac Sim, Omniverse, MuJoCo), This makes Orbis directly usable for training and testing robotic manipulation, navigation, and other embodied AI tasks.

<div align="center">

![orbis](./assets/orbis.gif)

</div>

Orbis demonstrates excellent performance in dynamic scene rendering, supporting real-time physics simulation and high-quality visual effects.

Orbis has significant advantages in scene realism, material quality, and detail richness. It adopts professional-grade PBR material workflow, natively supports USD format, features clear scene structure and distinct object hierarchy, and supports programmatic modification and batch generation.

## 📦 Available Subsets

<div align="center">

| Dataset | Description | Status | Github Link |
|:-------:|:-----------:|:------:|:----:|
| **Orbis-Tabletop** | Tabletop scenes<br>with objects and equipments | ✅ Available | [💻 Github](https://github.com/IntimeAI/Orbis-Tabletop) |
| **Orbis-Home** | Home scenes<br>with diverse layouts and furnitures | 🚧 Coming Soon | - |
| **Orbis-Urban** | Urban scenes<br>with streets, buildings, and city environments | 🚧 Coming Soon | - |

</div>

> More specialized subsets are under development. Stay tuned for updates!

## 💡 Application Scenarios

- **Robot Manipulation Learning**: Provides realistic training environments for robotic grasping, placement, and other manipulation tasks
- **Object Detection and Recognition**: Rich object categories and scene variations, suitable for training visual perception models
- **Virtual Reality and Visualization**: High-quality visual effects, applicable for VR/AR application development
- **Synthetic Data Generation**: Controllable scene parameters, facilitating large-scale annotated data generation

## 📄 Citation

If you use the Orbis dataset in your research, please cite:

```bibtex
@dataset{orbis2026,
  title={Orbis: A High-Quality 3D Scene Dataset},
  author={IntimeAI},
  year={2026},
  publisher={github},
  url={https://github.com/IntimeAI/Orbis}
}
```
## 📜 License

This dataset is released under the [Apache License 2.0](LICENSE).
