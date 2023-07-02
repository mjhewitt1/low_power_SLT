# Low Power SLT  -- UNDER CONSTRUCTION

## Low Power Computing for Speech and Language Technologies
Collection of resources designed for those interested in low power computing for speech and language technologies, e.g. low-power, energy-efficient, on-device approaches to speech and language processing.

Keywords: low-power, energy-efficient, speech processing, natural language processing

Related: on-device training, on-device inference, edge computing, federated learning, embedded systems, IoT, sustainability, open source, low cost, green computing, power efficiency, sustainable computing systems, tiny ml, private-by-design, language processing, speech synthesis, keyword spotting, natural language understanding, dialogue systems, language modelling, text processing


## Motivation
Research areas that aim to enhance the performance and capabilities of speech and language technologies that run on resource-constrained devices are attracting increasing attention. 

The benefits of such methods are becoming increasingly important and include:
- privacy
- energy efficiency
- real-time processing
- reduced latency
- offline functionality
- edge intelligence
- scalability and flexibility


## In the news
These articles highlight the significance of low power and on-device computing in enabling efficient and privacy-preserving speech and language processing on mobile devices, edge devices, and IoT devices. They discuss the challenges, opportunities, and advancements in this field, motivating further research and development in energy-efficient algorithms, hardware optimizations, and edge AI technologies.

- "Why Edge Computing Is Crucial for the Future of AI and Speech Recognition" - Forbes
- "The Rise of Edge AI: Powering Speech and Language Processing on Devices" - VentureBeat
- "AI in Your Pocket: How On-Device Computing Is Transforming Speech and Language Processing" - MIT Technology Review
- "The Need for Energy-Efficient Speech and Language Processing in Mobile Devices" - IEEE Spectrum
- "Advancements in Low Power Computing Drive Innovation in Speech and Language Technologies" - Voicebot.ai
- "The Shift to On-Device AI: Enhancing Privacy, Speed, and Energy Efficiency in Speech Processing" - ZDNet
- "Trends in Low Power Computing for Natural Language Processing" - Towards Data Science
- "The Importance of Low Power Speech and Language Processing in Internet of Things (IoT) Devices" - Electronics Weekly
- "Enabling Real-Time Speech and Language Processing with Low Power Edge Devices" - EETimes
- "Energy-Efficient Speech Recognition: The Next Frontier in Mobile Computing" - ScienceDaily
- 'Collection of voice data for profit raises privacy fears' https://abcnews.go.com/Technology/collection-voice-data-profit-raises-privacy-fears/story?id=96363792 (Accessed Jun 23)
- Data Centers: Climate Change Call to Action https://formtek.com/blog/data-centers-climate-change-call-to-action/


## Publications
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

Speech recognition methods
- Low-power automatic speech recognition using dilated convolutional neural networks
- Low-power deep learning for automatic speech recognition on embedded devices
- Energy-efficient large vocabulary continuous speech recognition using sparse coding"
- Energy-efficient dynamic pruning for recurrent neural network language models
- Tian, H et al. (2022). Bioinspired dual-channel speech recognition using graphene-based electromyographic and mechanical sensors. Cell Reports Physical Science. https://doi.org/10.1016/j.xcrp.2022.101075


On-device training

Keyword spotting

Federated learning



## Journals

- IEEE Transactions on Audio, Speech and Language Processing
- IEEE Transactions on Signal processing
- IEEE/ACM Transactions on Audio, Speech, and Language Processing
- IEEE Journal of Selected Topics in Signal Processing
- ACM Transactions on Speech and Language Processing
- ACM Transactions on Embedded Computing Systems
- ACM Transactions on Intelligent Systems and Technology
- Eurasip Journal on Audio, Speech, and Music Processing


## Conferences

- Interspeech (Annunal Conference of the International Speech Communication Association)
- IEEE Automatic Speech Recognition and Understanding Workshop (ASRU)
- IEEE Spoken Language Technology Workshop (SLT)
- IEEE Conference on Acoustics, Speech, and Signal Processing (ICASSP)
- Association for Computational Linguistics (ACL) Conference
- Conference on Empirical Methods and Natural Language Processing
- European signal processing conference (EUSIPCO)
- IEEE Interntational Conference on Multimedia and Expo (ICME)
- IEEE Workshop on Automatic Speech Recognition and Understanding (ASRU)


Upcoming:



## Challenges

- Interspeech Challenges
- Dialog System Technology Challenges
- Common Voice Data Set Challenges
- Global Energy Forecasting Competition (GEFCom): While not specifically focused on speech processing, the GEFCom series challenges participants to develop accurate and energy-efficient forecasting models for energy consumption and production. These competitions often involve time series analysis and can be applicable to optimizing energy consumption in speech and language processing systems.
- IEEE Signal Processing Cup: The IEEE Signal Processing Cup is an annual competition that challenges teams of undergraduate students to solve a specific signal processing problem. While the topics vary each year, some editions have focused on speech and audio processing, encouraging participants to develop efficient and low-power algorithms for speech-related tasks.



## Software

TensorFlow Lite for mobile and edge devices https://www.tensorflow.org/lite/
 - Gesture Recognition
 - Speech recognition (identify speech commands through keyword recognition)
 - Pose estimation (estimate pose of singe or multiple people)
 - Text classification (categorise free text into predefined groups)
 - Autocomplete (generate suggestions for text inputs using Keras language model)
 - On-device recommendation (provide personalised recommendations based on events)
 - Natural language question answering (answer questions based on a given passage of text with BERT)
 - Smart reply (generate reply suggestions to input conversational chat messages)
 - Audio classification 
 - Video classification (identify human actions)
 - Optical character recognition (OCR)
 - On-device training (train a TFLite model on-device)

TensorFlow Lite for microcontrollers https://www.tensorflow.org/lite/microcontrollers
- tflite-micro repo https://github.com/tensorflow/tflite-micro/tree/main has examples for recognising words (Speech Commands) and handwritten digits (MNIST)


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


 Speech recognition on MCU devices:
- Espressif ESP-SR
- ESP Skainet
- WakeNet
- MultiNet


Locally-run assistants/dialogue:
- Rhasspy (Mozilla DeepSpeech / Kaldi / PocketSphinx for STT) focuses on smart home applications
- ESP-Skainet (offline voice assistant with wakeword engine and speech command recognition for up to 200 commands) https://github.com/espressif/esp-skainet (inc acoustic algs for speech enhancement, acoustic echo cancellation, voice activity detection, automatic gain control, noise suppression)
- Willow uses Whisper ASR and supports LLAMA LLM running on a GPU https://github.com/toverainc/willow/tree/main/main


Keyword Spotting systems
- Snowboy Hotword Detection


## Hardware platforms

Espressif

Arduino

Raspberry Pi

Nvidia Jetson Nano

Nvidia GPUs


## Future plans & Feedback
The repository aims to keep an up-to-date snapshot of recent and interesting works relating to low-power speech and language technologies, whilst also assisting with resources for getting started in this area. 

The repo is intended as a springboard to form a special interest group of people that are working on or interested in this growing field of research. While the repo will be maintained over time, it could be nice to share quartlerly updates and anouncements with the communty via a newsletter.

Interested in a newsletter? [Sign up here](https://forms.gle/V83hQmvwHPsEELjr7)

Getting feedback from the community will be invaluable to the usefulness of this repository an group moving forward. Please feel free to send suggestions for anything you think should be included, anything you are working on, or any other ideas you may have.

Have suggestions? [Give feedback here](https://forms.gle/WVfKC9YZ3kZhnZ4i9)

Finally, if you know of anyone else interested in low-power SLTs please share this with them! :)


