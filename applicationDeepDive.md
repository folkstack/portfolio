# Selected full stack applications, ML/AI Projects, and R&D

## At a glance
* Audio, Time-series, and ML algorithms
* Complex end-to-end applications and systems
* Agent system development
* LLM integrations

### [Music Programming Studio](https://folkstack.com)
* generates music from code
* Integrated Agent prompting generates code that makes music.
* Full of tech and features like WASM, multi-process audio engine, and code editor
* provides a simple functional methods to program music (samples, notes, MIDI).
* high-performance audio engine runs in real-time.
* Innovative UX for working with AI (human in the loop)
* Agent system prompt prepares the LLM to use the system and theory.
* Backend with API for payments and registration; websockets for inference. 
* [Full studio demo](https://folkstack.com/studio.html)

### [Deep Learning Vitae](https://github.com/folkstack/deep_learning_vitae)
* A repo documenting my “vectors” in Machine Learning

### [JSYNTH\*](https://www.npmjs.com/search?q=jsynth)
* a base environment and dozens of modules for javascript audio synthesis in the browser
*  Real-time audio synthesis and processing
*  Used for web audio/DOM interaction, live code editors, effects, MIDI, digital synthesizers, and interfaces

### [Chess Foo](https://github.com/NHQ/Chess)"
* full stack web app
* websocket game server and browser client
* features chat, and fun chess variations

### [NetMorphic](https://github.com/NHQ/netmorphic-1)
* API testing framework, developed under contract for eBay, similar to “Chaos Monkey” at Netflix;
* Distributed & parallel multi-tenant proxy for both TCP and HTTP that simulates problematic network (latency, etc)

### [WebRTC Real-Time HIHFI Audio Streamer](https://github.com/NHQ/webRTC-audio-streamer) 
* Mobile first, international design, works in all browsers.    
* WASM Opus codec  
* WebRTC P2P broadcast  
* Listener Call-in  
* Streams host voice, callers, and audio files
  
### [G-Tone](https://github.com/folkstack/g-tone/#g-tone-n-polyphonic-mod-synth-for-midi-keyboards) 
* Musical Synthesizer that uses Gaussian distributions to define tones.
* High Performance real-time perfectly timed audio system, novel math and algorithms, novel modern web UI.
* A Unique Musical Synthesizer for MIDI keyboards; pure algorithmic audio generation in javascript.

## Artificial Intelligence and Machine Learning (AI/ML) 
8+ Years industry-level research, testing and development of AI models, using frameworks,   
data pipelines, Agent systems, plus novel and experimental deep learning R\&D. 

### AI/ML Project Case Study \- Complete deep learning stack written by myself 
**Technologies**: Tensorflow, SQL, Node.js  
**ML**: self attention, metaparameters, training, validation, inference, statistical analysis  
* Self Attention Neural Network: [lines 71-120](https://github.com/folkstack/deep_learning_vitae/blob/master/trx.js#L71-L120); functional, layered style  
* Imports a light [neural network framework](https://github.com/folkstack/various) I wrote in 2018: [Line 25](https://github.com/folkstack/deep_learning_vitae/blob/master/trx.js#L25)  
* Training and resource management: [Lines 153-189](https://github.com/folkstack/deep_learning_vitae/blob/master/trx.js#L153-L189)  
* Result Validation and resource management, : [Lines 195-248](https://github.com/folkstack/deep_learning_vitae/blob/master/trx.js#L195-L248)  
* Cross Correlation with previous prediction results:  [Lines 150-286](https://github.com/folkstack/deep_learning_vitae/blob/master/trx.js#L250-L286)  
* Prediction Inference: [Lines 288-329](https://github.com/folkstack/deep_learning_vitae/blob/master/trx.js#L288-L329)  
* Fitting Results with statistical loss functions: [Lines 332-279](https://github.com/folkstack/deep_learning_vitae/blob/master/trx.js#L332-L379)  
* Multiple Data Batching methods for selecting, sequencing, and shaping data for training and inference, using SQL and Tensorflow   [Lines 381-585](https://github.com/folkstack/deep_learning_vitae/blob/master/trx.js#L381-L585)  
* See Also: [Self-Attention Analyser](https://folkstack.github.io/art-of-inference/bezier-attention/) (2025, Agent generated)  
* Further reference: [My Deep Learning Vitae](https://github.com/folkstack/deep_learning_vitae) (somewhat outdated)

### Autocoding AI Agent (2025) 
* Tech: XML, Perl, Javascript, Bash, Linux, APIs, VMs   
* Automatic code writing Agent.  
* Uses a virtual machine to test code.  
* Complex context awareness for multi-step inference.  
* Server with user controls for prompting.  
* See https://folkstack.github.io/art-of-inference/  
  Results:   
* 100% code written by AI, including the Agent system  
* Wrote several sophisticated full stack projects  
  * WebGPU Parallel Computation Stack (WGLS)  
  * Self attention algorithm analyzer  
  * Painting UI w/ File System API  \[see graphic portfolio below\]  
  * Agent virtual machine, version control scripts, CLI, server, documentation

**AI/ML project study: “Various” \- a neural network framework written by myself in 2018**  
A functional approach to layered neural network topology.  
Provides Recurrent ([RNN](https://github.com/folkstack/various/blob/recent/topo.js#L17)), Convolutional ([CNN](https://github.com/folkstack/various/blob/recent/topo.js#L85)), and [Dense](https://github.com/folkstack/various/blob/recent/topo.js#L128) layers.  
Has many very [useful utilities](https://github.com/folkstack/various/blob/recent/utils.js).  
Validated by [passing MNIST](https://github.com/folkstack/mnist10k/tree/recent).

### AI/ML research and development case study: Boltzmann Machines 
Cutting edge R\&D in Energy-Based Models, proof of concepts, and undocumented magic.  
Entirely conceived and written by myself.  2020-ongoing.  
See [Distributed Training of Boltzmann Machines](https://github.com/folkstack/distributed_training_boltzmann_machines/tree/next)

### Time-Series and Forecasting Experience
Data Science Competitions \- I wrote a self-attention model, trained and backtested against historical data, optimized with trainable parametric statistical methods.  2020-2021.   
Real time media and data modeling \- Quant Data, Digital SIgnal Processing, and real-time multimedia (audio and video streams)  
Time series demand forecasting with Temporal Fusion Transformer ([pytorch forecasting](https://pytorch-forecasting.readthedocs.io/en/stable/tutorials/stallion.html)) \-   
See: [my google colab notebook and code](https://colab.research.google.com/drive/1RhtAletOw275wA5nzEtJuqpJSAw-6sSy)

### Cloud Provisioning, Data Collection, Self-Hosting
* Data collection from web and APIs using NodeJS, Linux, Bash, SQL  
* Google Gemini SDK & Virtex, or direct TPU compute and Virtual Machines  
* Training and inference with Open Source Models on-device or self-hosted servers

### Content Generation, Music and Video Batch Streaming
* Many Open-Source A.I. models and LLM tested (i.e. invokeAI, flux-dev)  
* Low Rank Adapter training (LORA)  
* FFMPEG for selecting, modifying,  shaping, and batching streams: [code](https://github.com/folkstack/deep_learning_vitae/blob/master/videobs.js#L19)  
* Digital Signal Processing
* Dozens of songs composed and publised with pure math and high level functional code
* [music composed with maths and algorithsm](https://soundcloud.com/folkstack)
* [Songs composed with Music Programming Studio using Agent AI](https://folkstack.com/blog/songs.html)
