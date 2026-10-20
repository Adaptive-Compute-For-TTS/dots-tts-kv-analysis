# dots-tts-kv-analysis
KV-style inference analysis and runtime profiling for dots.tts adaptive compute. 

Goal: Build a KV-style map for dots.tts by reading the inference code and using traces/logs from runs to identify important tensors, repeated operations, invariants, reusable state, and the most useful information to hand off to the GPU team for later adaptive compute scheduling.

Writeup: https://docs.google.com/document/d/1HG10EOWkfriFupQQNDICYXcf8ezMxd15Z4q3j5540Fw/edit?usp=sharing