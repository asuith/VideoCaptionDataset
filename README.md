# VideoCaptionDataset

What are datasets for video captioning and where can I download them?

This repo is here to help!

TODO:
- [x] MSR-VTT
- [ ] MSVD
- [ ] ActivityNet

## MSR-VTT

The MSR-VTT dataset can be downloaded by the json file the contest organizors have provided, however, some of the videos have been deleted from YouTube.

In the issue [here](https://github.com/VisionLearningGroup/caption-guided-saliency/issues/6), [ramanishka](https://github.com/ramanishka) provided [a downloadable link](https://www.mediafire.com/folder/h14iarbs62e7p/shared). It is worth noting that in the same issue , [akonstantinou](https://github.com/akonstantinou) pointed out that audioes of many videos are missing. I randomly checked some of the videos and find one such example, namely `video6446`. It should work just fine if your model only need the visual features.

### Info

The train/val set has 7010 videos (from `video0.mp4` to `video7009.mp4`) and test set has 2990 videos (from `video7010.mp4` to `video9999.mp4`), both of which have annotions. This dataset was released in 2016. In 2017, 3000 more videos was introduced by the contest organizors but never was the annotation.

A common split scheme is to use the 2016 version (10000 videos combined) and use sequential 6513, 497, 2990 videos for train, val and test respectively.

### Downloadable Links

[Link](https://www.mediafire.com/folder/h14iarbs62e7p/shared) from ramanishka, hosted at Media File.

[Backup Link](https://mega.nz/folder/Lpo0QaCb) hosted at MEGA.

[Backup Link](https://disk.pku.edu.cn:443/link/2796E06228387AF1DF6625E23E9722E1) hosted at PKU Disk (Will expire around 7/2022).

