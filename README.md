Fourth-year CS undergrad. I work on making models cheaper to run and measurements harder to fake.

Mostly GPU kernels, low-precision inference, and evaluation harnesses that don't flatter their author.

### Things that exist

**[qgemm-mx](https://github.com/titoatwork/qgemm-mx)** · `C++ / CUDA`  
Block-scaled FP4 on GPUs with no native FP4. MXFP4 moves 1.88x fewer bytes per weight than FP8 and currently delivers roughly none of the speedup. Measuring where it goes.

**[lfx-firstanalysis](https://github.com/titoatwork/lfx-firstanalysis)** · `Python`  
Every published figure re-derives offline from a committed artifact, or the build fails. `./verify.sh`, two dependencies, no API key.

**[COLIDE](https://github.com/titoatwork/COLIDE)** · `Python / CUDA`  
CNN-BiLSTM intrusion detection over network flow, with the inference path moved to GPU.

**[riscv/riscv-unified-db](https://github.com/riscv/riscv-unified-db)** · `Ruby / YAML`  
12 patches merged, none rejected. Most of them closed a defect my own measurement had surfaced.

### Earlier

Transformer inference on DGX H100 clusters. Fused Triton kernels at 3.5x PyTorch on a T4. A hedging agent that beats Black-Scholes mainly by trading less.

### Currently reading about

Ternary quantization, wave quantization on small batch sizes, and why nobody agrees on what a benchmark measured.

