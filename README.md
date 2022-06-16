# Speech-Dataset-Summarizing
汇总一些开源可用的语音数据集和噪声数据集

## 语音数据集

### 训练数据集
VTCK:https://datashare.ed.ac.uk/handle/10283/2950  
https://datashare.ed.ac.uk/handle/10283/2791  

### 几个最新免费开源的中文语音数据集
包括普通语音识别、唤醒和合成等中文数据集  
https://blog.ailemon.net/2018/11/21/free-open-source-chinese-speech-datasets/  


### Common Voice
由Mozilla构建的全球语音数据集开源平台，人人均可贡献，也可免费获取世界各国语言的语音数据集，其中，中文的语音数据集分为“中国大陆”“香港”和“台湾”三部分，AI柠檬博主认为这在一定程度上为针对中国不同地区的口音做技术适配提供了方便。  
https://commonvoice.mozilla.org/zh-CN/datasets  

### OpenSLR
描述：Open Speech and Language Resources，即OpenSLR是一个专门托管语音和语言资源的网站，例如语音识别训练语料库，以及与语音识别相关的软件。其中openslr18 THCHS-30和33 AISHELL为普通话。其余包括各种不同的语音数据集共计121个。  
网址: http://www.openslr.org/index.html  

### DNS Challenge
描述：微软在Interspeech和ICASSP会议上举办的DNS挑战赛，其中包含了语音、噪声以及一些RIR等数据集，比较适合于降噪任务。  
官方网址： https://www.microsoft.com/en-us/research/academic-program/deep-noise-suppression-challenge-interspeech-2020/  
Github网址：https://github.com/microsoft/DNS-Challenge, https://github.com/YoungJay0612/DNS-Challenge  

### ACE Challenge
描述：微软在Interspeech和ICASSP会议上举办的有关回声消除的任务，数据集中包括了远端和近端的单桨以及双讲数据  
官方网址：https://www.microsoft.com/en-us/research/academic-program/acoustic-echo-cancellation-challenge-interspeech-2021/  
Github网址：https://github.com/microsoft/AEC-Challenge  https://github.com/YoungJay0612/AEC-Challenge  

### Freesound
描述：Freesound是一个由Creative Commons许可的声音组成的协作数据库。浏览、下载和分享声音。  
官方网址：https://freesound.org/

### MagicData
描述：北京Magic data科技有限公司开发的一个开源数据平台，致力于帮助AI开发者进行模型培训，促进开源生态系统的发展。
官方网址：https://magichub.com/datasets  
Github网址： https://github.com/MagicHub-io  


## 噪声数据集

### NoiseX-92
链接：https://pan.baidu.com/s/1MYfL6_PXPoOmb07LgsoouQ  
提取码：zz2l  
包含15种噪声：  

White noise  
Pink noise  
HF channel noise  
Speech babble  
Factory floor noise 1  
Factory floor noise 2  
Jet cockpit noise 1  
Jet cockpit noise 2  
Destroyer engine room noise  
Destroyer operations room noise  
F-16 cockpit noise  
Military vehicle noise  
Tank noise  
Machine gun noise  
Car interior noise  

### Demand噪声库
包含多通道的真实环境噪声。  
https://zenodo.org/record/1227121#.YMhQBvkzZnI  

### TUT声学场景
https://zenodo.org/record/45739#.YMhP2PkzZnI  
包含15个声学场景的音频片段  
Bus - traveling by bus in the city (vehicle)  
Cafe / Restaurant - small cafe/restaurant (indoor)  
Car - driving or traveling as a passenger, in the city (vehicle) 
City center (outdoor)  
Forest path (outdoor)  
Grocery store - medium size grocery store (indoor)  
Home (indoor)  
Lakeside beach (outdoor)  
Library (indoor)  
Metro station (indoor)  
Office - multiple persons, typical work day (indoor)  
Residential area (outdoor)  
Train (traveling, vehicle)  
Tram (traveling, vehicle)  
Urban park (outdoor)  

### voxceleb dataset
https://www.robots.ox.ac.uk/~vgg/data/voxceleb/  
包含噪声：环境突发噪声、背景人声、笑声、回声、室内噪音、录音设备噪音；  
Speakers总数1,251，句子总数153,516，时长总数351h；  
