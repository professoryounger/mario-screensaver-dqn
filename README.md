# Mario-Screensaver-DQN

A  vanilla DQN for Super Mario Bros + a wholesome viewer script.

While training runs in one terminal, this second script sits in the background, checks every 60 seconds if mario_latest.pth changed, and instantly loads + plays the newest version — like a screensaver for people who have no life but love watching reward curves go up by 0.3.

![](assets/demo.gif)

### How to run
1. `trainer.py` (in one terminal — it saves mario_latest.pth)
2. `viewer_auto.py` (in another — sit back and watch the therapy happen)

Original code written in one desperate day circa 2025 by Ryan Y.  
