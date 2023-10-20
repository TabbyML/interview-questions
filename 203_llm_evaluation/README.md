# Language Model Evaluation

Create a [Dagster](https://dagster.io/) pipeline to conduct an evaluation of [CrossCodeEval](https://github.com/amazon-science/cceval) using [CodeT5P-220M](https://huggingface.co/Salesforce/codet5p-220m).

## Instructions

1. To execute the evaluation, employ the following files:
   - `./data/crosscodeeval_data/java/line_completion_oracle_bm25.jsonl`
   - `./data/crosscodeeval_data/java/line_completion_rg1_bm25.jsonl`

2. Develop the evaluation pipeline using Python and Dagster.

4. Compute metrics for both exact matches and edit similarity at the line level.

   Note: Running samples for 200 data points will suffice for this assignment.

5. Visualize the results using a Jupyter notebook (and make the visualization part of dagster pipeline)

## Deliverables

1. Provide instructions for downloading the code and running it locally.
