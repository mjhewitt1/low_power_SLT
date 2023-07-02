# Low Power SLT

## Low Power Computing for Speech and Language Technologies
Collection of resources designed for those interested in low power computing for speech and language technologies, e.g. low-power, energy-efficient, on-device approaches to speech and language processing.

Keywords: low-power, energy-efficient, speech processing, natural language processing

Related: on-device training, on-device inference, edge computing, federated learning, embedded systems, mobile devices, IoT, sustainability, open source, low cost, green computing, power efficiency, sustainable computing systems, tiny ml, private-by-design, language processing, speech synthesis, keyword spotting, natural language understanding, dialogue systems, language modelling, text processing


## Background and Motivation
Research areas that aim to enhance the performance and capabilities of speech and language technologies that run on resource-constrained devices are attracting increasing attention. 

The benefits of such methods are becoming increasingly important and include:
- privacy
- energy efficiency
- real-time processing
- reduced latency
- offline functionality
- edge intelligence
- scalability and flexibility


## In the News
These articles highlight the significance of low power and on-device computing in enabling efficient and privacy-preserving speech and language processing on mobile devices, edge devices, and IoT devices. They discuss the challenges, opportunities, and advancements in this field, motivating further research and development in energy-efficient algorithms, hardware optimizations, and edge AI technologies.

- ['Data Centers: Climate Change Call to Action' (June, 2023)](https://formtek.com/blog/data-centers-climate-change-call-to-action/)
- ['Collection of voice data for profit raises privacy fears' (Jan, 2023)](https://abcnews.go.com/Technology/collection-voice-data-profit-raises-privacy-fears/story?id=96363792)
- ['On-device speech processing makes Alexa faster, lower-bandwidth' (Jan, 2022)](https://www.amazon.science/blog/on-device-speech-processing-makes-alexa-faster-lower-bandwidth) 


## Getting Started
### Hardware platforms
The following hardware platforms commonly arise for processing, training and inference in low-power SLT settings and are useful to know about.

Microcontroller (MCU) devices typical of the IoT:
- [Espressif](https://www.espressif.com/) ESP32
- [Arduino](https://www.arduino.cc/) Uno

CPU and GPU devices for handling more powerful tasks:
- [Raspberry Pi](https://www.raspberrypi.org/) 3/4 (CPU)
- [Nvidia Jetson](https://www.nvidia.com/en-gb/autonomous-machines/embedded-systems/) Nano (CPU+GPU)
- [Nvidia](https://www.nvidia.com/en-gb/), [AMD](https://www.amd.com/en.html) provide many GPUs

Coral AI Edge TPU: 
- [Coral AI](https://coral.ai/products/) USB Accelerator ft. Edge TPU
- Coral AI provided examples for this include a keyphrase detector and pose estimator, plus others. 


### Software
#### For MCU devices
[TensorFlow Lite for microcontrollers (TFMicro)](https://www.tensorflow.org/lite/microcontrollers)
- The TensorFlow lite framework from Google provides a library for training and deploying machine learning (ML) models on microcontroller devices, like the ESP32. 
- [tflite-micro repo](https://github.com/tensorflow/tflite-micro/tree/main) has examples for recognising keywords (Speech Commands) and handwritten digits (MNIST), plus others.

 Speech processing on MCU devices:
- Espressif ESP-SR
- ESP Skainet
- WakeNet
- MultiNet
- ESP-ADF
- [Snowboy Hotword Detection](https://github.com/seasalt-ai/snowboy)


#### For CPU and GPU devices
[TensorFlow Lite (TFLite)](https://www.tensorflow.org/lite/) for mobile and edge devices
- Examples include: speech recognition, pose estimation, text classification, autocomplete text inputs, natural language question answering, smart reply chat suggestions, audio classification, and on-device training, plus more. 

Speech recognition on CPU/GPU devices:
- Vosk
- Coqui
- Whisper
- Mozilla DeepSpeech
- CMU PocketSphinx
- Fairseq STT
- ESPNet
- Jasper (PocketSphinx / Julius for STT)
- SpeechBrain
- Kaldi


## Open Source Systems
[Willow](https://github.com/toverainc/willow) & [Willow Inference Server (WIS)](https://github.com/toverainc/willow-inference-server)
- Willow is
- The Willow Inference Server is a local, self-hosted and highly optimized language inference server that supports ASR/STT, TTS, and LLM tasks across WebRTC, REST and WS.
- The project attracted much attention to the Espressif ESP32-S3 Box that it uses for the user interface

[Rasa Open Source](https://github.com/RasaHQ/rasa)
- A machine learning framework for building chat and voice-based AI assistants that make use of contextual information.
- The platform allows for connecting to messaging channels and thirdy party systems through a set of APIs, so you can build contextual assistants on Facebook, Slack, Telegram.

[Rhasspy](https://rhasspy.readthedocs.io/en/latest/)
- Rhasspy (Mozilla DeepSpeech / Kaldi / PocketSphinx for STT) focuses on smart home applications

[ESP-Skainet](https://github.com/espressif/esp-skainet)
- An offline voice assistant with wakeword engine and speech command recognition for up to 200 commands.
- The library includes acoustic algorithms for speech enhancement, acoustic echo cancellation, voice activity detection, automatic gain control, noise suppression.

[FedML-AI](https://github.com/FedML-AI/FedML)
- Provides a research and production interated edge-cloud platform for federated ML


## Research Publications
### Review Papers
Natural Language Processing (NLP) review papers: 
-  "Energy-efficient natural language processing: A review" by Y. Guo et al. (2020)
- "A survey on energy-efficient natural language processing" by S. Zhang et al. (2021)
- "Energy-efficient natural language processing: A systematic review" by J. B. Lopes et al. (2021)
-  "Energy-efficient techniques for natural language processing: A survey" by L. Zhou et al. (2021)

Speech Processing review papers: 
- "Low-power hardware for automatic speech recognition: A review" by J. Chen et al. (2020)
-  "Energy-efficient automatic speech recognition: A review" by Y. Wang et al. (2021)
- "Energy-efficient techniques for automatic speech recognition: A survey" by X. Li et al. (2021)
-  "Low-power techniques for speech synthesis: A review" by H. Li et al. (2021)
- "Energy-efficient techniques in speech processing: A comprehensive survey" by C. Zhang et al. (2021)


### Speech processing


### Natural language processing


### Related topics
On-device inference

On-device training

Federated learning

Edge AI


## Journals & Conferences

### Journals
- IEEE Transactions on Audio, Speech and Language Processing
- IEEE Transactions on Signal processing
- IEEE/ACM Transactions on Audio, Speech, and Language Processing
- IEEE Journal of Selected Topics in Signal Processing
- ACM Transactions on Speech and Language Processing
- ACM Transactions on Embedded Computing Systems
- ACM Transactions on Intelligent Systems and Technology
- Eurasip Journal on Audio, Speech, and Music Processing

### Conferences
- Interspeech (Annunal Conference of the International Speech Communication Association)
- IEEE Automatic Speech Recognition and Understanding Workshop (ASRU)
- IEEE Spoken Language Technology Workshop (SLT)
- IEEE Conference on Acoustics, Speech, and Signal Processing (ICASSP)
- Association for Computational Linguistics (ACL) Conference
- Conference on Empirical Methods and Natural Language Processing
- European signal processing conference (EUSIPCO)
- IEEE Interntational Conference on Multimedia and Expo (ICME)
- IEEE Workshop on Automatic Speech Recognition and Understanding (ASRU)

### Challenges
Some challenges that consider low-power and on-device speech and language processing: 
- Interspeech Challenges
- Dialog System Technology Challenges
- Common Voice Data Set Challenges
- Global Energy Forecasting Competition (GEFCom): While not specifically focused on speech processing, the GEFCom series challenges participants to develop accurate and energy-efficient forecasting models for energy consumption and production. These competitions often involve time series analysis and can be applicable to optimizing energy consumption in speech and language processing systems.
- IEEE Signal Processing Cup: The IEEE Signal Processing Cup is an annual competition that challenges teams of undergraduate students to solve a specific signal processing problem. While the topics vary each year, some editions have focused on speech and audio processing, encouraging participants to develop efficient and low-power algorithms for speech-related tasks.

## Events & Announcements
A place to share upcoming special issues/workshops/conferences on low-power SLTs. 


## Future plans & feedback
The aim is to maintain an up-to-date snapshot of recent and interesting works relating to low-power speech and language technologies, whilst also detailing resources for getting started in this area. 

The repo is intended as a springboard to form a special interest group of those that are working on or interested in this field of research. While the repo will be maintained, it could be good to share quartlerly updates and anouncements with the communty via a newsletter.

Interested in a newsletter? [Sign up here](https://forms.gle/V83hQmvwHPsEELjr7)

Getting feedback from the community will be invaluable to the usefulness of this repository an group moving forward. Please feel free to send suggestions for anything you think should be included, anything you are working on, or any other ideas you may have.

Have suggestions? [Give feedback here](https://forms.gle/WVfKC9YZ3kZhnZ4i9)

Finally, to help grow the community - if you know others interested in low-power SLTs, please share this with them!:)

