Fourth-year CS undergrad. I work on making models cheaper to run and measurements harder to fake.

Mostly GPU kernels, low-precision inference, and evaluation harnesses that don't flatter their author.

### Things that exist <img src="https://shields.io" height="18" valign="middle">

**[slipstream](https://github.com)** · `Python / Triton`  
LLM inference engine, built from scratch. The contribution sits at the scheduling layer — a memory-aware, output-length-predictive policy under hard KV-cache limits, where production engines still schedule blind. Companion to qgemm-mx: same bandwidth wall, one layer up.

**[qgemm-mx](https://github.com)** · `C++ / CUDA`  
Block-scaled FP4 on GPUs with no native FP4. MXFP4 moves 1.88x fewer bytes per weight than FP8 and currently delivers roughly none of the speedup. Measuring where it goes.

**[lfx-firstanalysis](https://github.com)** · `Python`  
Every published figure re-derives offline from a committed artifact, or the build fails. `./verify.sh`, two dependencies, no API key.

**[COLIDE](https://github.com)** · `Python / CUDA`  
CNN-BiLSTM intrusion detection over network flow, with the inference path moved to GPU.

**[riscv/riscv-unified-db](https://github.com)** · `Ruby / YAML`  
12 patches merged, none rejected. Most of them closed a defect my own measurement had surfaced.

### Earlier

Transformer inference on DGX H100 clusters. Fused Triton kernels at 3.5x PyTorch on a T4. A hedging agent that beats Black-Scholes mainly by trading less.

### Currently reading about

Ternary quantization, wave quantization on small batch sizes, and why nobody agrees on what a benchmark measured.
