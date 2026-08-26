<p align="center">
  <img src="https://raw.githubusercontent.com/xdltek/.github/main/assets/banner.png" alt="XDLTEK — AI inference, edge computing, and SDK systems" width="100%">
</p>

<h1 align="center">AI compute, from silicon to complete systems.</h1>

<p align="center">
  XDLTEK delivers a vertically integrated AI inference platform: RPP processors, AzureBlade accelerator cards,<br>
  edge AI boxes, servers, and the software to deploy real workloads.
</p>

<p align="center">
  <a href="https://github.com/xdltek/xdl-sdk"><strong>Get the XDL SDK</strong></a>
  ·
  <a href="#choose-your-hardware"><strong>Choose hardware</strong></a>
  ·
  <a href="#build-with-xdltek"><strong>Explore demos</strong></a>
</p>

---

## One platform. Four ways to deploy.

| Silicon | Accelerator cards | Edge AI boxes | AI server |
|:---:|:---:|:---:|:---:|
| **AE7100E · AE7103** | **M.2 · HHHL · FHFL** | **Arm · Intel · FPGA hosts** | **Up to 4× MC2A cards** |
| Purpose-built RPP processors | Scale from compact edge devices to high-throughput systems | Integrated, deployment-ready appliances | Dense multi-card inference in AS1000 |

XDLTEK gives customers one path from an ONNX model to deployed inference: develop with the XDL SDK, validate with production-oriented demos, then select the form factor that fits the site.

## Choose your hardware

### RPP processors

| Product | Designed for |
|---|---|
| **AE7100E** | High-performance AI inference across XDLTEK accelerator products |
| **AE7103** | Compact, efficient inference deployments |

### AzureBlade accelerator cards

| Product family | Form factor | Best fit |
|---|---|---|
| **KA08 Series** | M.2 | Space-constrained edge devices and embedded systems |
| **PB08 Series** | HHHL PCIe | Compact workstations and edge servers |
| **MC2A Series** | FHFL PCIe, dual-slot | High-throughput servers and multi-card inference |

### Integrated systems

| System | Host platform | Integrated XDLTEK acceleration |
|---|---|---|
| **AzureStation AS1000** | AI server | Up to **4× MC2A** dual-slot cards |
| **AzureEdge SR8** | Rockchip RK3588 AI box | **1× KA08** M.2 card |
| **AzureEdge SN5** | Intel N50 AI box | **1× KA08** M.2 card |
| **AzureEdge SI7** | Intel Core i7 AI box | **1× PB08** HHHL PCIe card |
| **RPP-BlackBox** | AMD/Xilinx XCZU11EG platform | Up to **3× KA08** accelerator cards |

> Product configurations can vary by deployment. Confirm interfaces, environmental specifications, and the final card configuration with XDLTEK before ordering.

## Start with the XDL SDK

The **XDL SDK** is the primary entry point for deploying models on XDLTEK hardware. Use it to set up the runtime and toolchain before moving to the workload examples below.

<p align="center">
  <a href="https://github.com/xdltek/xdl-sdk"><strong>Open xdltek/xdl-sdk →</strong></a>
</p>

## Build with XDLTEK

Start from a working application that matches your workload. C++ and Python coverage will continue to expand.

<details open>
<summary><strong>OpenRT · Computer vision inference</strong></summary>
<br>

| Workload | C++ | Python |
|---|---|---|
| YOLOv8 object detection | [YOLOv8](https://github.com/xdltek/YOLOv8) | Python demo planned |
| YOLOv5 object detection | [YOLOv5](https://github.com/xdltek/YOLOv5) | [YOLOv5_Python](https://github.com/xdltek/YOLOv5_Python) |
| ResNet50 classification | [ResNet50](https://github.com/xdltek/ResNet50) | [ResNet50_Python](https://github.com/xdltek/ResNet50_Python) |

</details>

<details>
<summary><strong>CUDA-style programming · Kernel and optimization samples</strong></summary>
<br>

- [CUDA Samples](https://github.com/xdltek/CUDA_Samples) — programming examples for the XDLTEK compute platform
- [High-end DSP RPP CUDA](https://github.com/xdltek/high-end-dsp-rpp-cuda) — RPP CUDA-style kernels and optimization examples

</details>

<details>
<summary><strong>Complete applications · Video analytics and edge LLMs</strong></summary>
<br>

- [OpenStream](https://github.com/xdltek/openstream) — hardware video decode, inference, and SORT tracking in one pipeline
- [llama.cpp](https://github.com/xdltek/llama.cpp) — edge large-language-model inference for the Qwen model family

</details>

<details>
<summary><strong>Multi-card inference · Scale on MC2A</strong></summary>
<br>

- [Multi-card YOLOv5](https://github.com/xdltek/multi_card_YOLOv5)
- [Multi-card classification](https://github.com/xdltek/multi_card_classification)
- [Multi-card U-Net](https://github.com/xdltek/multi_card_unet)

</details>

## Models, benchmarks, and tools

| Resource | What it provides |
|---|---|
| [RPP Model Zoo](https://github.com/xdltek/rpp-model-zoo) | Model references and benchmark data; automated scripts are planned |
| [ONNX Verify Tools](https://github.com/xdltek/onnx-verify-tools) | Dynamic-to-static shape repair, per-node MACs and memory analysis, parameter counts, and unsupported-operator diagnosis |

---

<p align="center">
  <strong>Ready to evaluate XDLTEK?</strong><br>
  Start with the <a href="https://github.com/xdltek/xdl-sdk">XDL SDK</a>, select a <a href="#choose-your-hardware">deployment platform</a>, and use the closest demo as your application baseline.
</p>
