# EE322 Lab 5

### Mosquitto MQTT Test


Paho can be installed quickly using this command:

` $ pip install paho-mqtt `

The next step is to install mosquitto

Then we can test it by opening two teminals and running these commands:

Terminal 1:

` $ mosquitto_sub -h localhost -v -t test/topic & `


Terminal 2:

`$ mosquitto_pub -h localhost -t test/topic -m "Hello" `

---

`python3 sub.py`

![pic1](https://github.com/Githubpucci/EE-322/assets/116912039/b7c94d23-1dcc-41ae-9b6e-18b14da62220)

---

`python3 sub-multiple.py`

![pic2](https://github.com/Githubpucci/EE-322/assets/116912039/00af82c0-bffc-48f6-9835-d787d4553874)

---

`python3 subcpu.py`


![pic3](https://github.com/Githubpucci/EE-322/assets/116912039/6c86e1fc-2d9e-4151-b187-5608505dbe20)
