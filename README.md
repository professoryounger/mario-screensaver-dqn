# Mario-Screensaver-DQN

A  vanilla Double-DQN with PER for Super Mario Bros + a auto viewer script.

While training runs in one terminal, this second script sits in the background, checks every 60 seconds if mario_latest.pth changed, and instantly loads + plays the newest version — like a machine learning screensaver.

[](assets/demo.gif)

### How to run
1. `train_1_5.py` (in one terminal — it saves mario_latest.pth)
2. `view.py` (in another — sit back and watch the therapy happen)

Original code written by Ryan Y.  
