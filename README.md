# strix-scripts

A set of scripts for running models on AMD strix halo 395

Scripts assume that hugging face cli is installed and llama.cpp is in $HOME/Projects. The scripts are written for CachyOS Linux fish shell. Qwen3.8-Flash-Next uses podman.

For Qwen3.8-Flash-Next, set GPU memory allocation to 4GB to force system wide memory sharing. All other models were run with GPU memory at 96GB.

To change memory allocation, reboot into BIOS then

Advanced -> AMD CBS -> NBIO Common Options -> GFX Configuration -> Dedicated Graphics Memory


