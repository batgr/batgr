# Grévy Batsotsa

MSc Artificial Intelligence at Heriot-Watt University and engineering double-degree student at ESME. I build reproducible data and model systems for conversational AI, with a research focus on multi-party turn-taking for social robots.

## Current work

| Project | What I built |
| --- | --- |
| [Conversational dynamics data](https://github.com/batgr/world-model-turn-taking-data) | A shared Python pipeline with corpus-specific adapters for EgoCom and Ego4D: audits, synchronized vocal-state grids, conversation-level splits, training windows, media manifests, label sidecars and provenance checks. |
| [Turn-taking world model](https://github.com/batgr/world-model-turn-taking-model) | PyTorch/Lightning training and evaluation for an action-conditioned, JEPA-style latent dynamics model using frozen Mimi audio features. The [audio-only V2 branch](https://github.com/batgr/world-model-turn-taking-model/tree/v2/audio-only) contains the next pilot recipe; results are pending. |
| [EgoCom release on Hugging Face](https://huggingface.co/datasets/batgre/conversational-dynamics-egocom) | Public, versioned action grid, model-ready indexes and optional speech/text labels. Raw media is not redistributed. |

The research goal is turn-taking in a live social-robot interaction. A Hugging Face Space voice-agent demonstration is planned after the V2 study; it is a separate software demo, not a robot deployment.

**Tools:** Python, PyTorch, Hugging Face, Hydra, Parquet, pytest, Git, Linux, SLURM and Weights & Biases.

[Hugging Face](https://huggingface.co/batgre) · [LinkedIn](https://www.linkedin.com/in/grevy) · [Email](mailto:grevy.batsotsa@esme.fr)
