---
layout: post
title:  "Senior Design"
brief:  "A custom Smart Lock concept, using Facial Recognition"
categories: socketio raspi msp432 face_recognition python bluetooth
source: https://github.com/isibley765/ECE-477-Senior-Design
previews:
    - image: CadHousings.png
---

My forked copy of my old team's Senior Design project.

A 'smart lock' concept, with a lock that allowed for facial recognition to allow user access through a threshold.
Overrides are accepted in the form of a manual hard key, and a pincode entry, should extraneous use cases or
recognition failure occur.

My contributions were largely for the facial recognition automation, socket connection & communications, and the
orchestration of the application logic throughout the Pi and a remote computer, for faster processing of the frames
captured vs the people known. Faces are saved in their vector forms after the first pass, to minimize processing
time.

---
<br/>

Full project concept design included a laptop communicating with a Raspberry Pi over WiFi or Ethernet, and the
Raspberry Pi communicating to a TI MSP-432 microcontroller over Bluetooth, with a powered door lock and custom
PCB designed by our team.

<img src="{{site.baseurl}}/images/Senior Design/PiAndCameraEnclosed.jpg" alt="Pi Encasing" width="50%" />
<img src="{{site.baseurl}}/images/Senior Design/solderingNewBoard.jpg" alt="New PCB being soldered" width="44%" />

---
<br>

I don't believe the project website is still being hosted by the school, but can be found in the
[477Team2Website](https://github.com/isibley765/477Team2Website) repository still if need be.

Facial recognition was done using the [face_recognition](https://pypi.org/project/face-recognition/) python
library.

---
