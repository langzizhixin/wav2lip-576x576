# wav2lip-576x576
This is a project about talking faces. We use 576X576 sized facial images for training, which can generate 2k, 4k, 6k, and 8k digital human  videos.

We have optimized in the following areas:
1. Using Hubert for audio processing, there is a significant improvement compared to wav2lip-96 and wav2lip-288.
2. Optimized dataset processing, eliminating the need to manually cut videos into seconds.
3. We have optimized the network structure to better extract features.
4. We trained the base model with a high-definition dataset of hundreds of people. Although its generalization ability is not strong, the effect is very good after single or multi person fine-tuning.

# SyncTalk: The Devil😈 is in the Synchronization for Talking Head Synthesis
The official repository of the paper [SyncTalk: The Devil is in the Synchronization for Talking Head Synthesis](https://arxiv.org/abs/2311.17590)

<p align='center'>
  <b>
    <a href="https://arxiv.org/abs/2311.17590">Paper</a>
    | 
    <a href="https://ziqiaopeng.github.io/synctalk/">Project Page</a>
    |
    <a href="https://github.com/ZiqiaoPeng/SyncTalk">Code</a> 
  </b>
</p> 
  <p align='center'>  
    <img src='image/synctalk.png' width='1000'/>
  </p>
