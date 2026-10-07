# Grévy Batsotsa

MSc Artificial Intelligence @ Heriot-Watt University · Engineering student @ ESME

## About

I build world models for conversation. At the National Robotarium, I am developing an action-conditioned,
JEPA-style model that predicts how a multi-party conversation will evolve, so a social robot can decide when
to speak, wait or yield the floor.

It runs on audio today. My goal is one world model where audio and video share the same latent space.

I also built the dataset behind it: a reproducible pipeline over Ego4D and EgoCom, released on Hugging Face.

Looking for research internships from early 2027.

## Projects

| Project | What it does |
| --- | --- |
| [Turn-taking world model](https://github.com/batgr/world-model-turn-taking-model) | A frozen encoder (Mimi, log-mel, or any audio/video encoder) gives latents; a causal Transformer predicts future latents from vocal actions. Teacher forcing, open-loop rollouts with a horizon curriculum, SIGReg. |
| [Conversational dynamics data](https://github.com/batgr/world-model-turn-taking-data) | An 8-stage pipeline that audits Ego4D and EgoCom and puts them on one grid of the wearer's vocal state: 614 recordings, 2.2M training windows, 116 labels, checksums at every stage. |
| [EgoCom release on Hugging Face](https://huggingface.co/datasets/batgre/conversational-dynamics-egocom) | Public, versioned action grid and model-ready index, at [10 Hz](https://huggingface.co/datasets/batgre/conversational-dynamics-egocom) and [12.5 Hz](https://huggingface.co/datasets/batgre/conversational-dynamics-egocom-12.5hz). Raw media is not redistributed. |

## Tools

Python · PyTorch · Lightning · Hydra · Hugging Face Datasets · Parquet · pytest · Weights & Biases · NVIDIA A100 · SLURM

[LinkedIn](https://www.linkedin.com/in/grevy) · [Hugging Face](https://huggingface.co/batgre) · [Email](mailto:gb4017@hw.ac.uk)
