# HowTo-RaspberryPi-LLM-Inference

Testing and benchmarking of performance of LLM inference on Raspberry Pi

# llama.cpp

```bash
~/llama.cpp/build/bin/llama-cli   -m ~/models/Qwen2.5-Omni-3B-Q4_K_M.gguf   -t 6   -c 2048   -b 256   -ub 64   -n 256   -p "What do you get if you multiply six by nine?"   --no-warmup
```

## Raspberry Pi 5

Model: Qwen2.5-Omni-3B-Q4_K_M.gguf 

```bash
> What do you get if you multiply six by nine?

The product of six and nine is 54.

[ Prompt: 26.3 t/s | Generation: 6.1 t/s ]
```