<p align="center">
  <img src="https://raw.githubusercontent.com/xdltek/.github/main/assets/banner.png" alt="XDLTEK — AI inference, edge computing, and SDK systems" width="100%">
</p>

<h1 align="center">AI compute, from silicon to complete systems.</h1>

<p align="center">
  XDLTEK delivers a vertically integrated AI inference platform—from RPP processors and AzureBlade<br>
  accelerator cards to edge AI boxes, multi-card servers, and deployment software.
</p>

<p align="center">
  <a href="https://github.com/xdltek/xdl-sdk"><img src="https://img.shields.io/badge/GET_THE_XDL_SDK-087CF0?style=for-the-badge&logo=github&logoColor=white" alt="Get the XDL SDK"></a>
  <a href="#hardware-portfolio"><img src="https://img.shields.io/badge/EXPLORE_HARDWARE-00A7A0?style=for-the-badge" alt="Explore hardware"></a>
  <a href="#application-demos"><img src="https://img.shields.io/badge/VIEW_DEMOS-7952DF?style=for-the-badge" alt="View demos"></a>
</p>

---

## Hardware portfolio

<p align="center">
  <strong>One architecture. Multiple form factors. From compact edge deployment to dense server inference.</strong>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/xdltek/.github/main/assets/product-portfolio.png" alt="XDLTEK AzureBlade KA08, PB08, and MC2A accelerator cards" width="100%">
</p>

<table>
  <tr>
    <td align="center" width="33%"><strong>KA08 Series</strong><br><sub>AzureBlade M.2</sub><br><br>Compact edge and embedded systems</td>
    <td align="center" width="33%"><strong>PB08 Series</strong><br><sub>AzureBlade HHHL PCIe</sub><br><br>Workstations and edge servers</td>
    <td align="center" width="33%"><strong>MC2A Series</strong><br><sub>AzureBlade FHFL PCIe · Dual-slot</sub><br><br>High-throughput and multi-card inference</td>
  </tr>
</table>

### From chip to system

| Product layer | Portfolio | Deployment choice |
|---|---|---|
| **RPP processors** | **AE7100E · AE7103** | Purpose-built AI inference silicon |
| **Accelerator cards** | **KA08 · PB08 · MC2A** | M.2, HHHL PCIe, and FHFL PCIe form factors |
| **Edge AI boxes** | **SR8 · SN5 · SI7 · RPP-BlackBox** | Integrated Arm, Intel, and FPGA host platforms |
| **AI server** | **AzureStation AS1000** | Up to **4× MC2A** dual-slot cards |

<details>
<summary><strong>View integrated system configurations</strong></summary>
<br>

| System | Host platform | Integrated XDLTEK acceleration |
|---|---|---|
| **AzureStation AS1000** | AI server | Up to **4× MC2A** dual-slot cards |
| **AzureEdge SR8** | Rockchip RK3588 AI box | **1× KA08** M.2 card |
| **AzureEdge SN5** | Intel N50 AI box | **1× KA08** M.2 card |
| **AzureEdge SI7** | Intel Core i7 AI box | **1× PB08** HHHL PCIe card |
| **RPP-BlackBox** | AMD/Xilinx XCZU11EG platform | Up to **3× KA08** accelerator cards |

</details>

> Product configurations can vary by deployment. Confirm interfaces, environmental specifications, and the final card configuration with XDLTEK before ordering.

<br>

<p align="center">
  <img src="https://raw.githubusercontent.com/xdltek/.github/main/assets/section-sdk.svg" alt="01 XDL SDK — Start here" width="100%">
</p>

The **XDL SDK** is the primary entry point for deploying models on XDLTEK hardware. Set up the runtime and toolchain here, then select a workload demo as your application baseline.

<p align="center">
  <a href="https://github.com/xdltek/xdl-sdk"><img src="https://img.shields.io/badge/OPEN_xdltek%2Fxdl--sdk-087CF0?style=for-the-badge&logo=github&logoColor=white" alt="Open xdltek/xdl-sdk"></a>
</p>

<br>

## Application demos

<p align="center">
  <img src="https://raw.githubusercontent.com/xdltek/.github/main/assets/section-demos.svg" alt="02 Application Demos" width="100%">
</p>

Choose a working example by workload. C++ and Python coverage will continue to expand.

### OpenRT computer vision

| Workload | C++ | Python |
|---|---|---|
| **YOLOv8** object detection | [YOLOv8](https://github.com/xdltek/YOLOv8) | Python demo planned |
| **YOLOv5** object detection | [YOLOv5](https://github.com/xdltek/YOLOv5) | [YOLOv5_Python](https://github.com/xdltek/YOLOv5_Python) |
| **ResNet50** classification | [ResNet50](https://github.com/xdltek/ResNet50) | [ResNet50_Python](https://github.com/xdltek/ResNet50_Python) |

<table>
  <tr>
    <td width="50%" valign="top">
      <strong>⚡ CUDA-style programming</strong><br><br>
      <a href="https://github.com/xdltek/CUDA_Samples">CUDA Samples</a><br>
      <a href="https://github.com/xdltek/high-end-dsp-rpp-cuda">High-end DSP RPP CUDA</a>
    </td>
    <td width="50%" valign="top">
      <strong>🎬 Complete applications</strong><br><br>
      <a href="https://github.com/xdltek/openstream">OpenStream</a> · Decode + inference + SORT<br>
      <a href="https://github.com/xdltek/llama.cpp">llama.cpp</a> · Qwen-family edge LLM inference
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <strong>🔗 Multi-card inference on MC2A</strong><br><br>
      <a href="https://github.com/xdltek/multi_card_YOLOv5">YOLOv5</a> ·
      <a href="https://github.com/xdltek/multi_card_classification">Classification</a> ·
      <a href="https://github.com/xdltek/multi_card_unet">U-Net</a>
    </td>
  </tr>
</table>

<br>

<p align="center">
  <img src="https://raw.githubusercontent.com/xdltek/.github/main/assets/section-model-zoo.svg" alt="03 Model Zoo and Benchmarks" width="100%">
</p>

### Evaluate model coverage

The [**RPP Model Zoo**](https://github.com/xdltek/rpp-model-zoo) provides model references and benchmark data for evaluating workloads on the XDLTEK platform. Automated benchmark scripts are planned.

<p align="center">
  <a href="https://github.com/xdltek/rpp-model-zoo"><img src="https://img.shields.io/badge/EXPLORE_RPP_MODEL_ZOO-7952DF?style=for-the-badge&logo=github&logoColor=white" alt="Explore RPP Model Zoo"></a>
</p>

<br>

<p align="center">
  <img src="https://raw.githubusercontent.com/xdltek/.github/main/assets/section-tools.svg" alt="04 Deployment Tools" width="100%">
</p>

### Inspect models before deployment

[**ONNX Verify Tools**](https://github.com/xdltek/onnx-verify-tools) helps teams prepare and diagnose ONNX models:

- Repair dynamic dimensions into deployment-ready static shapes
- Print per-node MACs, activation and parameter memory, and parameter counts
- Identify unsupported or abnormal operators when a model cannot run

<p align="center">
  <a href="https://github.com/xdltek/onnx-verify-tools"><img src="https://img.shields.io/badge/OPEN_ONNX_VERIFY_TOOLS-F97316?style=for-the-badge&logo=github&logoColor=white" alt="Open ONNX Verify Tools"></a>
</p>

---

<p align="center">
  <strong>Build your next AI deployment with XDLTEK.</strong><br><br>
  Start with the <a href="https://github.com/xdltek/xdl-sdk">XDL SDK</a> · Choose an accelerator · Scale from edge to server
</p>
