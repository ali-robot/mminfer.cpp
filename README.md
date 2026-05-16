# mminfer.cpp

mminfer.cpp is a C++ CPU-first inference engine for open-weight language and multimodal models.

The goal of this project is to implement the core machinery required to run decoder-only transformer models and vision-language models locally on commodity CPUs, with a focus on clean architecture, readable systems code, reproducible benchmarks, and progressive support for modern open model formats.

This project is educational, experimental, and engineering-oriented. It is not intended to immediately replace mature runtimes such as llama.cpp, ONNX Runtime, TensorRT-LLM, vLLM, or MLX. Instead, it is designed to expose the internal mechanics of LLM and VLM inference in a clean, inspectable C++ codebase.
