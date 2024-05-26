# About training with colab
## setup
- account: google colab pro

## capacity
- A100 40G GPU (one)

## runs
### 2024.05.26
[results](https://wandb.ai/lux-tech/huggingface/runs/pwfagxmt?nw=nwuserlunac)

_tips:_
- opt-125m 可以
- opt-6.7b 不行，内存不够(even with fsdp or deepspeed)
    - （只能考虑lora）