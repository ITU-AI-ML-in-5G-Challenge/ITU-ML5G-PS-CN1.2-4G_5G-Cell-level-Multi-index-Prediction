---
# PS-CN1.2: 4G/5G Cell-level Multi-index Prediction (China Mobile)
---

## PS-CN1.2

**Team Name:**

Ironhead-5

**Problem Statement**

4G/5G Cell-level Multi-index Prediction

(The problem statement information can be found at http://36.133.53.121:1080/index/content_page?pageType=11#about)

**Team Members:**

XU Haigao,CAO Yihong,MEI Hui,WU Jiaxu,WANG Yaliu,SHUI Tianyun,China Mobile Jiangxi,China

**Special Explanation**

Download on the server offer by the match organization is prohibit,we can not get the data(maybe sensitivity) download to local computer to run again.So the effect of code is only can be showed by screenshot of running on server.Or you can watch the **Working demo** to learn how the code works.

## List of Notebooks:

**001step data cleaning**

Data cleaning(necessary and important),The data of 4 cities and 2 formats for 2 months requires 4 cores of 32G + 1 V100 for a total of 6 hours(screenshot shown in the end of code) .I suggest you may read it for not more than 10 minutes.

**002step slect training cells**

002step slect training cells(necessary but not important).There is no much technical details,you can pass it.

**003step slect training cells**

003step slect training cells(necessary but not important).There is no much technical details,you can pass it.

**004step wavenet training and prediction(0.2562 mape)**

Step 004 004step **wavenet** training and prediction(necessary and important).The training data is input to the WaveNet model, using a two-layer 1/2/4/8 diffusion rate model, and the input and output are sequence-to-sequence modes.This notebook is our kernel code.I suggest you may read it most time.

**Other01 direct 7days-shift cleaning data to watch(0.3182 mape)**

Other01 direct 7days-shift cleaning data to watch(not necessary,only for watching and compare).There is no much technical details,you can pass it.

**Other02 liner mode to compare(0.2665 mape)**

Other02 liner mode to compare(not necessary,only for watching and compare).You can read it for few minutes.

**Other03 LSTM mode to compare(0.2569 mape)**

Other03 LSTM mode to compare(not necessary,only for watching and compare).You can read it for few minutes.

**Other04 168-168 wavenet model to compare(0.2665 mape)**

Other04 168-168 wavenet model to compare(not necessary,only for watching and compare).You can read it for few minutes.

**Special Explanation**

Download on the server offer by the match organization is prohibit,we can not get the data(maybe sensitivity) download to local computer to run again.So the effect of code is only can be showed by screenshot of running on server.Or you can watch the **Working demo** to learn how the code works.Sorry for it.


