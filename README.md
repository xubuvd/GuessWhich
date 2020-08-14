# About Me
虚步, a Ph.D. student at BUPT. I am very fortunate to be advised by my advisor. My research is in the area of Vision, Language, and Reasoning, with a focus on Visual Dialogue. I am particularly interested in building a visually-grounded conversational AI (social robot) that can see the world and talk with us in natural language. Other interests include Visual/Language Grounding, Visual Reasoning, Visual Question Generation, and Visually-grounded Referring Expression.

Now I've been working on the GuessWhich, Visual Dialog(VisDial) and Talking-to-Videos(Video-Grounded Dialogue) task, please feel free to contact me with pangweitf@bupt.edu.cn or pangweitf@163.com if you have any questions or concerns.

# GuessWhich
GuessWhich is a cooperative image-guessing game between two agents: Q-BOT and A-BOT, like that of GuessWhat?! game that is an image object-guessing game between two players.

GuessWhich is a two player game played by Qbot and Abot. The goal of GuessWhich is to figure out a correct answer out of 9,628 test images by asking a sequence of questions. Abot can see the randomly assigned target image, which is unknown to Qbot. Qbot only observes a caption of the image generated from Neuraltalk2 (Vinyals & Le, 2015). To achieve the goal, Qbot asks a series of questions, to which Abot responds with a sentence. [This part is from the paper of ICLR 2019, Large-scale Answer in Questioner's Mind for Visual Dialog Question Generation, Sang-Woo Lee et al.]

The two agents communicate in natural language dialogue. In the beginning, they can see a broader set of images, in which ABot randomly selects an image as the secret that is not known to Q-BOT. Q-Bot asks a sequence of free-form natural language questions and ABot responds with free-form answers. In the end, QBot tries to identify the secret image from the fixed pool of images. If the right image is found, the dialogue is considered a success, otherwise, failure.

## 1. paper 
## 2. paper 


# Acknowledgements
This PyTorch implementation is based on the PyTorch code of Learning Cooperative Visual Dialog Agents using Deep Reinforcement Learning [Das & Kottur et al., ICCV 2017]. Github:https://github.com/batra-mlp-lab/visdial-rl<br>

## pytorch env
PyTorch version: 1.2.0<br>
CUDA used to build PyTorch: 10.0.130<br>
<br>
OS: Ubuntu 16.04.4 LTS<br>
GCC version: (Ubuntu 5.4.0-6ubuntu1~16.04.9) 5.4.0 20160609<br>
CMake version: Could not collect<br>
<br>
Python version: 3.6<br>
Is CUDA available: Yes<br>
CUDA runtime version: 10.0.130<br>
GPU models and configuration:<br>
GPU 0: TITAN V<br>
GPU 1: TITAN V<br>
<br>
Nvidia driver version: 410.79<br>
cuDNN version: Could not collect<br>
<br>
Versions of relevant libraries:<br>
[pip3] msgpack-numpy==0.4.3.2<br>
[pip3] numpy==1.16.2<br>
[pip3] numpydoc==0.8.0<br>
[pip3] torch==1.2.0<br>
[pip3] torchfile==0.1.0<br>
[pip3] torchtext==0.7.0<br>
[conda] Could not collect<br>

## Challenges
GuessWhich is a challenging visual-language problem. It involves processing large amounts of images, and human's mental imagery that is spawned by a natural language dialogue consists of multi-round Question-Answer-pairs.

# Performance


# Current Vision-and-Language-and-Reasoning tasks, focuses on Visual Dialogue
 LaVi Tasks | conference  | comment
 ----------| :-----------:  | :-----------:
 GuessWhich|AAAI 2017|:camel:
 Multimodal Dialogs(MMD)|AAAI 2018|-
 CoDraw|ACL 2019|-
 GuessWhat?!|CVPR 2017|:smile:
 Multi-agent GuessWhich|AAMAS 2019|-
 Image-Chat|ACL 2020|
 EmbodiedQA|CVPR 2018|
 VideoNavQA|BMVC 2019|
 GuessNumber|SLT 2018|
 VisDial|CVPR 2017|:camel:
 Image-Grounded Conversations(IGC)|CVPR 2017|
 VDQG|ICCV 2017|
 RDG-Image guessing game|LREC 2014|
 Deal or No Deal|CoRR 2017|
 Video-Grounded Dialogue Systems (VGDS)|ACL 2019|
 Vision-Language Navigation (VLN)|CVPR 2018|
 Image Captioning||
 Image Retrieval||
 Visually-grounded Referring Expressions|
 Multi-modal Verification|ACL 2019|
 Viual Dialog based Referring Expression||
 VQA||
 
 # Traning 
 # 


