# Low Power SLT

## Low Power Computing for Speech and Language Technologies
Collection of resources designed for those interested in low power computing for speech and language technologies, e.g. low-power, energy-efficient, on-device approaches to speech and language processing.

Keywords: low-power, energy-efficient, speech processing, natural language processing

Related topics: on-device training, on-device inference, edge computing, federated learning, embedded systems, mobile devices, IoT, sustainability, open source, low cost, green computing, power efficiency, sustainable computing systems, tiny ml, private-by-design, language processing, speech synthesis, keyword spotting, natural language understanding, dialogue systems, language modelling, text processing

Table of Contents
1. [Background and Motvation](#background-and-motivation)
2. [In the News](#in-the-news)
3. [Getting Started](#getting-started)
4. [Open Source Systems](#open-source-systems)
5. [Research Publications](#research-publications)
6. [Journals and Conferences](#journals-and-conferences)
7. [Events and Announcements](#events-and-announcements)
8. [Future Plans and Feedback](#future-plans-and-feedback)


## Background and Motivation <a name="background-and-motivation"></a>
Research areas that aim to enhance the performance and capabilities of speech and language technologies that run on resource-constrained devices are attracting increasing attention. 

The benefits of such methods are becoming increasingly important and include:
- privacy
- energy efficiency
- real-time processing
- reduced latency
- offline functionality
- edge intelligence
- scalability and flexibility


## In the News <a name="in-the-news"></a>
These articles highlight the significance of low power and on-device computing in enabling efficient and privacy-preserving speech and language processing on mobile devices, edge devices, and IoT devices. They discuss the challenges, opportunities, and advancements in this field, motivating further research and development in energy-efficient algorithms, hardware optimizations, and edge AI technologies.

- ['Data Centers: Climate Change Call to Action' (June, 2023)](https://formtek.com/blog/data-centers-climate-change-call-to-action/)
- ['Collection of voice data for profit raises privacy fears' (Jan, 2023)](https://abcnews.go.com/Technology/collection-voice-data-profit-raises-privacy-fears/story?id=96363792)
- ['On-device speech processing makes Alexa faster, lower-bandwidth' (Jan, 2022)](https://www.amazon.science/blog/on-device-speech-processing-makes-alexa-faster-lower-bandwidth)
- ['The Move Toward Green Machine Learning (Nov, 2022)](https://insidebigdata.com/2022/11/06/the-move-toward-green-machine-learning/)
- ['Is there a More Environmentally Friendly Way to Train Artificial Intelligence' (March, 2021)](https://insidebigdata.com/2021/03/31/is-there-a-more-environmentally-friendly-way-to-train-artificial-intelligence/)
- ['C is the Greenest Programming Language' (Nov, 2021)](https://hackaday.com/2021/11/18/c-is-the-greenest-programming-language/)
- ['The Generative AI Race Has a Dirty Secret' (Feb, 2023)](https://www.wired.com/story/the-generative-ai-search-race-has-a-dirty-secret/)
- ['AI and ML Think Green' (April, 2022)](https://www.forbes.com/sites/forbestechcouncil/2022/04/13/ai-and-ml-think-green/amp/)
- ['No Room for Privacy Complacency in the Era of Cloud-Based AI' (June, 2023)](https://www.forbes.com/sites/forbestechcouncil/2023/06/23/no-room-for-privacy-complacency-in-the-era-of-cloud-based-ai/amp/)
- ['Chat GPT's Electricity Consumption' (Mar, 2023)](https://towardsdatascience.com/chatgpts-electricity-consumption-7873483feac4)
- ['Artificial Intelligence is Booming - so is its Carbon Footprint' (March, 2023)](https://www.bloomberg.com/news/articles/2023-03-09/how-much-energy-do-ai-and-chatgpt-use-no-one-knows-for-sure)
- ['The Rise of Smart Speakers and Voice Could Boost Data Ceneters' (Feb, 2019)](https://www.datacenterfrontier.com/internet-of-things/article/11429739/the-rise-of-smart-speakers-and-voice-could-boost-data-centers)
- ['The Climate Cost of the AI Revolution' (May, 2023)](https://labs.ripe.net/author/wim-vanderbauwhede/the-climate-cost-of-the-ai-revolution/)
- ['Green Intelligence: Why Data and AI Must Become More Sustainable' (Mar, 2023)](https://www.forbes.com/sites/bernardmarr/2023/03/22/green-intelligence-why-data-and-ai-must-become-more-sustainable/amp/)


## Getting Started <a name="getting-started"></a>
### Hardware platforms
The following hardware platforms commonly arise for processing, training and inference in low-power SLT settings and are useful to know about.

| Type     | Examples | 
| :---        | :----   |
| MCU    | [Espressif](https://www.espressif.com/) ESP32, [Arduino](https://www.arduino.cc/) Uno       | 
| CPU   | [Raspberry Pi](https://www.raspberrypi.org/) 3/4 (CPU)       | 
| CPU + GPU   | [Nvidia Jetson](https://www.nvidia.com/en-gb/autonomous-machines/embedded-systems/) Nano |
| GPUs  | [Nvidia](https://www.nvidia.com/en-gb/) provide many GPUs, e.g. RTX 3090 graphics card |
| TPU   | [Coral AI](https://coral.ai/products/) USB Accelerator ft. Edge TPU |


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


## Open Source Systems <a name="open-source-systems"></a>
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

### Tutorials
[How to Run a ChatGPT-Like LLM on Your PC Offline](https://beebom.com/how-run-chatgpt-like-language-model-pc-offline/amp/)


## Research Publications <a name="research-publications"></a>
### Review Papers
- Xu, Jingjing, et al. "A survey on green deep learning." arXiv preprint arXiv:2111.05193 (2021).
- Schizas, Nikolaos, et al. "TinyML for Ultra-Low Power AI and Large Scale IoT Deployments: A Systematic Review." Future Internet 14.12 (2022): 363.
- Han, Hui, and Julien Siebert. "TinyML: A systematic review and synthesis of existing research." 2022 International Conference on Artificial Intelligence in Information and Communication (ICAIIC). IEEE, 2022.
- Treviso, Marcos, et al. "Efficient methods for natural language processing: A survey." arXiv preprint arXiv:2209.00099 (2022).
- Hessenthaler, Marius, et al. "Bridging fairness and environmental sustainability in natural language processing." arXiv preprint arXiv:2211.04256 (2022).


### Speech processing
- Wong, Alexander, et al. "Tinyspeech: Attention condensers for deep speech recognition neural networks on edge devices." arXiv preprint arXiv:2008.04245 (2020).
- Li, Qin, et al. "MSP-MFCC: Energy-efficient MFCC feature extraction method with mixed-signal processing architecture for wearable speech recognition applications." IEEE Access 8 (2020): 48720-48730.
- Tian, He, et al. "Bioinspired dual-channel speech recognition using graphene-based electromyographic and mechanical sensors." Cell Reports Physical Science 3.10 (2022).
- Tambe, Thierry, et al. "A 16-nm soc for noise-robust speech and nlp edge ai inference with bayesian sound source separation and attention-based dnns." IEEE Journal of Solid-State Circuits 58.2 (2022): 569-581.
- Maayah, Marina, et al. "LimitAccess: on-device TinyML based robust speech recognition and age classification." Discover Artificial Intelligence 3.1 (2023): 8.


### Natural language processing
- Tambe, Thierry, et al. "Edgebert: Sentence-level energy optimizations for latency-aware multi-task nlp inference." MICRO-54: 54th Annual IEEE/ACM International Symposium on Microarchitecture. 2021.
- Gundu, Krishna Sriharsha, et al. "Comparative Analysis of Energy Consumption in Text Processing Models." International Conference on Advancements in Smart Computing and Information Security. Cham: Springer Nature Switzerland, (2022).
- Ge, Tao, Si-Qing Chen, and Furu Wei. "EdgeFormer: A parameter-efficient transformer for on-device Seq2Seq generation." arXiv preprint arXiv:2202.07959 (2022).
- Moro, Gianluca, Luca Ragazzi, and Lorenzo Valgimigli. "Carburacy: summarization models tuning and comparison in eco-sustainable regimes with a novel carbon-aware accuracy." Proceedings of the AAAI Conference on Artificial Intelligence. Vol. 37. No. 12. 2023.


### Related areas
On-device training
- Incel, Ozlem Durmaz, and Sevda Ozge Bursa. "On-Device Deep Learning for Mobile and Wearable Sensing Applications: A Review." IEEE Sensors Journal (2023).

Federated learning
- Liu, Ming, et al. "Federated learning meets natural language processing: A survey." arXiv preprint arXiv:2107.12603 (2021).

IoT
- Burrello, Alessio, et al. "A microcontroller is all you need: Enabling transformer execution on low-power iot endnodes." 2021 IEEE International Conference on Omni-Layer Intelligent Systems (COINS). IEEE, 2021.

Model compression 
- Mireshghallah, Fatemehsadat, et al. "Differentially private model compression." Advances in Neural Information Processing Systems 35 (2022): 29468-29483.

## Journals & Conferences <a name="journals-and-conferences"></a>
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
- Global Energy Forecasting Competition (GEFCom): While not specifically focused on speech processing, the GEFCom series challenges participants to develop accurate and energy-efficient forecasting models for energy consumption and production.
- IEEE Signal Processing Cup: The IEEE Signal Processing Cup is an annual competition that challenges teams of undergraduate students to solve a specific signal processing problem. While the topics vary each year, some editions have focused on speech and audio processing, encouraging participants to develop efficient and low-power algorithms for speech-related tasks.

## Events & Announcements <a name="events-and-announcements"></a>
A place to share upcoming special issues/workshops/conferences on low-power SLTs. 


## Future plans & feedback <a name="future-plans-and-feedback"></a>
The aim is to maintain an up-to-date snapshot of recent and interesting works relating to low-power speech and language technologies, whilst also detailing resources for getting started in this area. 

The repo is intended as a springboard to form a special interest group of those that are working on or interested in this field of research. While the repo will be maintained, it could be good to share quartlerly updates and anouncements with the communty via a newsletter.

Interested in a newsletter? [Sign up here](https://forms.gle/WVfKC9YZ3kZhnZ4i9)

Getting feedback from the community will be invaluable to the usefulness of this repository an group moving forward. Please feel free to send suggestions for anything you think should be included, anything you are working on, or any other ideas you may have.

Have suggestions? [Give feedback here](https://forms.gle/WVfKC9YZ3kZhnZ4i9)

Finally, to help grow the community - if you know others interested in low-power SLTs, please share this with them!:)

