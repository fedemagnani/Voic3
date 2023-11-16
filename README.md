We could make an App which simply generates tmpl files pointing to existing docker images. The most cool models always come with a Docker image, like Coqui-TTS

# Voic3

## Useful links: 
Running Lilypad jobs from smart contracts: https://github.com/bacalhau-project/lilypad/blob/main/docs/smart-contract-jobs.md
Docker x Coqui: https://tts.readthedocs.io/en/latest/docker_images.html
Docker image: https://github.com/coqui-ai/TTS/pkgs/container/tts
Synthetizer: https://github.com/coqui-ai/TTS/blob/dev/TTS/bin/synthesize.py
Notebook for training: https://github.com/coqui-ai/TTS/blob/dev/notebooks/Tutorial_2_train_your_first_TTS_model.ipynb

- Set the image to: ghcr.io/coqui-ai/tts:3c2d5a9e03040e081732a5e917464ddd74049c43@sha256:80b0b260421850b10f28d327b44802dc61eebf62603e19e6ef7560df33174fb5 (according to https://github.com/coqui-ai/TTS/pkgs/container/tts)
- Setting 10 GPUs
- we remove the input key in tmpl
