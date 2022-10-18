# <center> Cross-speaker Style Transfer Ssing Curriculum Learning and Data Augmentation</center>

<center> Author name</center>  


<center>Netease Games AI LAB, Guangzhou, China</center>  

## Abstract
This paper addresses the problem of cross-speaker style transfer for text-to-speech (TTS) using curriculum learning and data augmentation. In this paper, the training corpus consists of neutral non-expressive data from a target speaker and expressive data in different speaking styles from source speakers. The goal is to transfer different speaking styles from source speakers to the target speaker. We propose to regard the task as a curriculum divided into two learning steps. The first step is parallel style transfer, whose learning outcome is synthesizing parallel data from the stylized data of source speakers. In the second step, we pool the augmented expressive data with the original dataset to fine-tune the model (trained by the first step) to support synthesizing expressive data with the target speaker. The proposed method is evaluated on three different speaking styles, three different source speakers, and different amounts of source data. Experimental results show that the proposed method can significantly improve style similarity while providing a comparable performance with the baseline model on speaker similarity and audio quality. Furthermore, we conduct ablation studies to gain an in-depth understanding of cross-speaker style transfer as an out-of-distribution problem. 

Paper link: [arXiv](Not Available so far ...)  


## Cross-speaker Style Transfer Demo

## Baseline: The Fastpitch-based model without curriculum learning and data augmentation. (Target Speaker)
## Proposed: The proposed Fastpitch-based model without curriculum learning and data augmentation. (Target Speaker)
## Upperbound: Synthesizing utterances using three source speakers to see the upperbound style-similarity performance. (Source Speakers)


Source Documentation Style:    <audio src="wavs/source_styles/doc.wav" controls preload></audio> 
Source Chat Style:	<audio src="wavs/source_styles/chat.wav" controls preload></audio>
Source Game Style:	<audio src="wavs/source_styles/game.wav" controls preload></audio>
Target Speaker:   <audio src="wavs/target_speaker/target.wav" controls preload></audio> 


### Documentation Style

| **Baseline** | **Proposed** | **upperbound** |
| :--- | :--- | :--- |
| <audio src="wavs/baseline/doc/0.wav" controls preload></audio> | <audio src="wavs/proposed/doc/0.wav" controls preload></audio> | <audio src="wavs/upperbound/doc/0.wav" controls preload></audio> | 
| --- | --- | --- |
| <audio src="wavs/baseline/doc/1.wav" controls preload></audio> | <audio src="wavs/proposed/doc/1.wav" controls preload></audio> | <audio src="wavs/upperbound/doc/1.wav" controls preload></audio> |
| --- | --- | --- |
| <audio src="wavs/baseline/doc/2.wav" controls preload></audio> | <audio src="wavs/proposed/doc/2.wav" controls preload></audio> | <audio src="wavs/upperbound/doc/2.wav" controls preload></audio> |
| --- | --- | --- |
| <audio src="wavs/baseline/doc/3.wav" controls preload></audio> | <audio src="wavs/proposed/doc/3.wav" controls preload></audio> | <audio src="wavs/upperbound/doc/3.wav" controls preload></audio> |
| --- | --- | --- |
| <audio src="wavs/baseline/doc/4.wav" controls preload></audio> | <audio src="wavs/proposed/doc/4.wav" controls preload></audio> | <audio src="wavs/upperbound/doc/4.wav" controls preload></audio> |
| --- | --- | --- |



### Chat Style

| **Baseline** | **Proposed** | **upperbound** |
| :--- | :--- | :--- |
| <audio src="wavs/baseline/chat/0.wav" controls preload></audio> | <audio src="wavs/proposed/chat/0.wav" controls preload></audio> | <audio src="wavs/upperbound/chat/0.wav" controls preload></audio> |
| --- | --- | --- |
| <audio src="wavs/baseline/chat/1.wav" controls preload></audio> | <audio src="wavs/proposed/chat/1.wav" controls preload></audio> | <audio src="wavs/upperbound/chat/1.wav" controls preload></audio> |
| --- | --- | --- |
| <audio src="wavs/baseline/chat/2.wav" controls preload></audio> | <audio src="wavs/proposed/chat/2.wav" controls preload></audio> | <audio src="wavs/upperbound/chat/2.wav" controls preload></audio> |
| --- | --- | --- |
| <audio src="wavs/baseline/chat/3.wav" controls preload></audio> | <audio src="wavs/proposed/chat/3.wav" controls preload></audio> | <audio src="wavs/upperbound/chat/3.wav" controls preload></audio> |
| --- | --- | --- |
| <audio src="wavs/baseline/chat/4.wav" controls preload></audio> | <audio src="wavs/proposed/chat/4.wav" controls preload></audio> | <audio src="wavs/upperbound/chat/4.wav" controls preload></audio> |
| --- | --- | --- |




### Game Style

| **Baseline** | **Proposed** | **upperbound** |
| :--- | :--- | :--- |
| <audio src="wavs/baseline/game/0.wav" controls preload></audio> | <audio src="wavs/proposed/game/0.wav" controls preload></audio> | <audio src="wavs/upperbound/game/0.wav" controls preload></audio> |
| --- | --- | --- |
| <audio src="wavs/baseline/game/1.wav" controls preload></audio> | <audio src="wavs/proposed/game/1.wav" controls preload></audio> | <audio src="wavs/upperbound/game/1.wav" controls preload></audio> |
| --- | --- | --- |
| <audio src="wavs/baseline/game/2.wav" controls preload></audio> | <audio src="wavs/proposed/game/2.wav" controls preload></audio> | <audio src="wavs/upperbound/game/2.wav" controls preload></audio> |
| --- | --- | --- |
| <audio src="wavs/baseline/game/3.wav" controls preload></audio> | <audio src="wavs/proposed/game/3.wav" controls preload></audio> | <audio src="wavs/upperbound/game/3.wav" controls preload></audio> |
| --- | --- | --- |
| <audio src="wavs/baseline/game/4.wav" controls preload></audio> | <audio src="wavs/proposed/game/4.wav" controls preload></audio> | <audio src="wavs/upperbound/game/4.wav" controls preload></audio> |
| --- | --- | --- |






