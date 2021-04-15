# mediapipe_aarch64RPI4
This are my whl files for installing mediapipe and tensorflow on a Raspberry Pi 4 running ubuntu 20.04

I just followed the guide provided in this link: https://github.com/jiuqiant/mediapipe_python_aarch64

I had a problem with the whl file provided on this link the mediapipe installed using this whl file does not have a face detection module

To generate this whl for mediapipe
after following the guide up until

step 8. Disable carotene_o4t in third_party/BUILD

Before running the command on step 9. Build the package
Is to create an symlink to python3 and python3
using this command
sudo ln -s /usr/bin/python3 /usr/bin/python


To use the whl files:
sudo -H python3 -m pip install <whl file>
