# wav2lip-576x576 introduction
This is a project about talking faces. We use 576X576 sized facial images for training, which can generate 2k, 4k, 6k, and 8k digital human  videos.

We have optimized in the following areas:
1. Using Hubert for audio processing, there is a significant improvement compared to wav2lip-96 and wav2lip-288.
2. Optimized dataset processing, eliminating the need to manually cut videos into seconds.
3. We have optimized the network structure to better extract features,Our idea is not to train the discriminator separately, but to train the generator directly..
4. We trained the base model with a high-definition dataset of hundreds of people. Although its generalization ability is not strong, the effect is very good after single or multi person fine-tuning.

# wav2lip-576x576 Project situation
<p align='center'>
  <b>
    <a href="https://www.bilibili.com/video/BV1zK421v7wh/?vd_source=7720ff9e037156b51374d14ee8f76b51">Video </a>
    | 
    <a href="https://github.com/langzizhixin">Project Page</a>
    |
    <a href="https://github.com/langzizhixin/wav2lip-576x576">Code</a> 
  </b>
</p> 
  <p align='center'>  
    <img src='576x576-CorrespondingVideo.jpg' width='1000'/>
  </p>

# wav2lip-576x576 Code Release Plan
This project is not yet mature enough.
We will gradually release the code, first release the data processing code, then release the inference code, and when the time is ripe, we will release the training code.

# acknowledge
The code is mainly borrowed from wav2lip, wav2lip-288, wav2lip-384, ER-NeRF, etc.
Thank you for their wonderful work.

# author
Project  made by Lu Rui from Langzizhixin Technology company in Chengdu, China, 2024.

# Code contribution
At present, the video preprocessing, facial cropping, and audio Hubert processing codes have been completed. Welcome everyone to contribute code related to network structure, training, and inference.
