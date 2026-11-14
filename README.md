# strix-scripts

A set of scripts for running models on strix halo 395

For Qwen3.8-Flash-Next, set GPU memory allocation to 4GB to force system wide memory sharing. All other models were run with GPU memory at 96GB.

To change memory allocation, reboot into BIOS then

    Advanced -> AMD CBS -> NBIO Common Options -> GFX Configuration -> Dedicated Graphics Memory
