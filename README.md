# AI Upscaling Explained: What It Recovers and What It Invents

Measured band by band: a single-frame upscale recovers 4.3% of the detail its source lost, and sharpening raises the amplitude 9x without moving that number at all. How to tell recovery from invention, with reproducible code.

**Read it with the tables and the reproduction snippets:** <https://celticgemini001.github.io/upgolab-ai-upscaler-guide/>

## About this repo

This repository exists to serve one measured article. Every number in it came from
ffmpeg and numpy run on real files on this machine — the commands are in the page so
you can re-run them and get the same rows. Where the measurement contradicted the
hypothesis, the page says so.

## The tool behind the notes

<https://upgolab.com> — browser-based AI upscaler for photos and short video.

## Index

All the guides are cross-linked from the hub:
<https://celticgemini001.github.io/upgolab-tools/>
