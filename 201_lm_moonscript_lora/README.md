# Moonscript language model (LoRA)

Build a lora language model for [moonscript](https://moonscript.org).

# Instructions

You'll need to build an language model with moonscript using following sources:
1. [pythia-70m](https://huggingface.co/EleutherAI/pythia-70m)
2. `moonscript` slice in [The Stack](https://huggingface.co/datasets/bigcode/the-stack)
3. [PEFT](https://github.com/huggingface/peft)
4. [Weights and Bias](http://wandb.ai)

We do **NOT** require you to build a fully converged model. You only need to provide an wand training history of 100 steps.

# Minimum Requirements

1. A python script implements LoRA training / evaluation on moonscript language source codes from *The Stack*.

The requirements are relatively simple. On the other hand, please put more thought on the overall design and leave space for the future improvement.

# Good to have

### Features

We don't require any additional features. If you have more time, we recommend you to polish those minimum requirements. But if you can't resist the temptation, just go ahead and surprise us.

# Deliverables

1. Instruction on how to download the code and run locally.
2. wand link to a 100-steps training history.
