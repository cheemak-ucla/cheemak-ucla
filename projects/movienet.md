# MovieNET for radial CEST MR fingerprinting

**Status:** Public preprint, October 2026. [Read the paper](https://arxiv.org/abs/2610.23805).

CEST MR fingerprinting estimates tissue properties from a series of MRI measurements. Accelerated acquisition reduces the available data, creating a reconstruction problem.

Our study adapted MovieNET to use temporal and coil information for radial CEST-MRF reconstruction, with GRASP-LLR as a reference comparison. I am the first author; the work was conducted with Victor Murray, Ricardo Otazo and Ouri Cohen.

## Reported evidence

- Ten healthy volunteers; leave-one-subject-out evaluation.
- Median image correlation of 0.965 and NRMSE of 7.5% across the held-out subjects.
- Whole-brain acquisition in three minutes.
- Reported reconstruction time of 1.7 seconds for a 30-slice series.

These are research results from healthy volunteers. Reconstruction timing is distinct from acquisition and the complete processing workflow. The preprint does not establish clinical deployment or generalization to patients.

## Skills demonstrated

Temporal deep learning, inverse problems, GPU reconstruction, subject-level evaluation and quantitative imaging.

[Back to portfolio](../README.md)
