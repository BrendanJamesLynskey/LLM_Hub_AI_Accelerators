<!-- portfolio-strip:start (brief 40) -->
<sub>**Brendan Lynskey** · [Portfolio home](https://brendanjameslynskey.github.io/) · [Interactive sites](https://brendanjameslynskey.github.io/#sites)</sub>
<!-- portfolio-strip:end -->

# AI Accelerators

The families of AI silicon, compared on the same work: GPUs, systolic designs, wafer-scale engines, compiler-scheduled SRAM chips, reconfigurable dataflow, meshes of small cores, FPGAs and edge NPUs, and in-memory compute. For each: where the weights live, what moves on each step, and who decides when it moves.

**Live index:** https://brendanjameslynskey.github.io/LLM_Hub_AI_Accelerators/

The three decks are the slide companion to **[AI Accelerators Explained](https://ai-accelerators-explained.vercel.app)**, ten animated chapters in the Hardware track (beside GPU Kernels, Systolic Arrays and AI Racks Explained). Every number in the decks is computed by the site's tested model, with every specification sourced and dated in its [results.md](https://github.com/BrendanJamesLynskey/ai-accelerators-explained/blob/main/results.md).

## Presentations in this series

| # | Title | Status | Description | Site chapters |
|---|-------|--------|-------------|---------------|
| 01 | [The Design Space and the Memory Wall](https://brendanjameslynskey.github.io/AI_Accelerators_01_The_Design_Space/) | live | The three axes and the eight families; the running workload (a Llama decoder); GPUs and systolic designs as the baseline; capacity as the first trade; every family side by side; bounds against published figures; what the families are converging on. | [1](https://ai-accelerators-explained.vercel.app/learn/01-the-design-space), [2](https://ai-accelerators-explained.vercel.app/learn/02-gpus-the-baseline), [3](https://ai-accelerators-explained.vercel.app/learn/03-systolic-designs), [10](https://ai-accelerators-explained.vercel.app/learn/10-choosing) |
| 02 | [SRAM Machines: Wafers, LPUs and IPUs](https://brendanjameslynskey.github.io/AI_Accelerators_02_SRAM_Machines/) | live | Why SRAM; a wafer of 84 dies and how defects are survived; models split across wafers and weight streaming; the GroqChip's static schedule and a 576-chip chain; what the published speeds say about the bound; the IPU's bulk-synchronous tiles. | [4](https://ai-accelerators-explained.vercel.app/learn/04-wafer-scale), [5](https://ai-accelerators-explained.vercel.app/learn/05-compiler-scheduled), [6](https://ai-accelerators-explained.vercel.app/learn/06-reconfigurable-dataflow) |
| 03 | [Dataflow, Meshes, Edge and In-Memory](https://brendanjameslynskey.github.io/AI_Accelerators_03_Dataflow_Meshes_Edge_In_Memory/) | live | A layer kernel by kernel vs fused; three tiers of memory and the SN40L paper's measured speed; a mesh of cores split over cards; a batch-1 decode at narrower weights on an NPU or FPGA; a decoder on phase-change crossbars, and what it costs in capacity and precision. | [6](https://ai-accelerators-explained.vercel.app/learn/06-reconfigurable-dataflow), [7](https://ai-accelerators-explained.vercel.app/learn/07-meshes-of-cores), [8](https://ai-accelerators-explained.vercel.app/learn/08-fpgas-and-npus), [9](https://ai-accelerators-explained.vercel.app/learn/09-in-memory-compute) |

## Related

- [NVIDIA GPU Architectures](https://github.com/BrendanJamesLynskey/LLM_Hub_NVIDIA_GPUs) and [Google TPUs](https://github.com/BrendanJamesLynskey/LLM_Hub_Google_TPUs): the two baseline families in depth.
- [GPU Kernels Explained](https://gpu-kernels-explained.vercel.app/), [Systolic Arrays Explained](https://systolic-arrays-explained.vercel.app/) and [AI Racks Explained](https://ai-racks-explained.vercel.app/): inside one GPU, inside one matrix engine, and the racks these chips go into.
- [Fourier Optics for Inference](https://github.com/BrendanJamesLynskey/LLM_Hub_Fourier_Optics_Inference) and [Compute in Transit](https://github.com/BrendanJamesLynskey/LLM_Hub_Compute_in_Transit): computing with light, the analogue route these decks mention but do not cover.

## Where this fits

Part of the [LLMs hub](https://github.com/BrendanJamesLynskey/LLMs) &mdash; an index of presentation series for AI/LLM engineers.
