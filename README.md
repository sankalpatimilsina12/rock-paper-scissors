# Face/Emotion Recognition

An AI to play the Rock Paper Scissors game.

## Installation

1. Install Python3 and pip.
2. Install virtualenv (pip install virtualenv).
3. Create virtualenv (virtualenv venv) and activate (source venv/bin/activate).
4. pip install -r requirements.txt.
5. python3 gather_images.py rock 200 (Once webcame window opens, press 'a' to start recording hand gesture for rock)
6. python3 gather_images.py paper 200 (Once webcame window opens, press 'a' to start recording hand gesture for paper)
7. python3 gather_images.py scissors 200 (Once webcame window opens, press 'a' to start recording hand gesture for scissors)
8. python3 gather_images.py none 200 (Once webcame window opens, press 'a' to start recording hand gesture for nothing, ie. blank screen or something)
9. python3 train.py
10. python3 play.py
