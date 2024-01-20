# TremorGuard
This is an IOT project built to help monitor the disease progression of patients with Parkinson's Disease.<br>
A demo of our product can be viewed from [this link](https://www.youtube.com/watch?v=ZfBNp8Ql5Bw)

It is developed by a team of 4 NUS students, who contributed in the following manners:<br>
Celestine - Searching of datasets and related studies, training of AI models<br>
Gabriel - Training of AI models, improving accuracy across models<br>
Khang Hou - Building of web application, setting up internal backend server, training of AI models, overall integration<br>
Joy - Arduino code for collection and sending of data (embedded systems), setting up Azure IoTHub, 3D modelling and printing of device holder<br>

### Client
```
npm run dev
```

### Starting NestJS Server
```
npm run start:dev
```

### Starting AI Server
```
python3 server.py
```

### Steps
#### Collect IoT data
Simply start the main server. The IoT devices should start sending data once connected to Wi-FI

#### View classifications
Classifications are only shown after 60 seconds due to the requirement of having at least 60 seconds of past data before making classifications

#### Submit labelled data
Data collected must be for the same activity type. 
