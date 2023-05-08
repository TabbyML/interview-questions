# Language model distillation

Create a distilled model of `SantaCoder` with `flan-t5-small` on `moonscript`.

# Instructions

You'll need to build an distilled language model using following sources:
1. [SantaCoder](https://huggingface.co/bigcode/santacoder) as teacher model.
2. [flan-t5-small](https://huggingface.co/google/flan-t5-small) as student model.
3. `moonscript` slice in [The Stack](https://huggingface.co/datasets/bigcode/the-stack) as dataset for distillation.
4. [Weights and Bias](http://wand.ai)

We do **NOT** require you to build a fully converged model. You only need to provide an wand training history of 100 steps.

# Minimum Requirements

1. A python package implements the distillation training process & basic evaluation.

The requirements are relatively simple. On the other hand, please put more thought on the overall design and leave space for the future improvement.

# Good to have

### Features

We don't require any additional features. If you have more time, we recommend you to polish those minimum requirements. But if you can't resist the temptation, just go ahead and surprise us.

# Deliverables

1. Instruction on how to download the code and run locally.
2. wand link to a 100-steps training history.
