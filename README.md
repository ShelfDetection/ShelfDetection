### This program uses detectnet to identify objects on your shelf and notifies you when you are out of an item

Setup: Change lines 19-21 to your email, password and who you want to send the message to(this will be the notification that something is taken off of your shelf.

How to run the program:
  This program was created for a jetson nano but may be used on other devices however, modifications will need to be made

  Running from a USB camera:  python3 test.py /dev/video0 rtp://[Your IP here]:1234
    When running from a Camera follow these steps for camera streaming: https://github.com/dusty-nv/jetson-inference/blob/master/docs/aux-streaming.md#v4l2-cameras

  If you want to run from a usb camera to an mp4 file run this command here: python3 test.py /dev/video0 output.mp4

  If you want to run from an image run this command: python3 test.py [image path] [output path]
    For example: python3 test.py shelf.png shelf_output.png
### Optional Terminal Arguments(See code for further details):
  --overlay
  --threshold



<!--
**ShelfDetection/ShelfDetection** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
