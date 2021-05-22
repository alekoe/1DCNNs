# 1D CNN Architectures for Music Genre Classification

### Safaa Allamy, Alessandro Lameiras Koerich
This paper proposes a 1D residual convolutional neural network (CNN) architecture for music genre classification and compares it with other recent 1D CNN architectures. The 1D CNNs learn a representation and a discriminant directly from the raw audio signal. Several convolutional layers capture the time-frequency characteristics of the audio signal and learn various filters relevant to the music genre recognition task. The proposed approach splits the audio signal into overlapped segments using a sliding window to comply with the fixed-length input constraint of the 1D CNNs. As a result, music genre classification can be carried out on a single audio segment or on the aggregation of the predictions on several audio segments, which improves the final accuracy. The performance of the proposed 1D residual CNN is assessed on a public dataset of 1,000 audio clips. The experimental results have shown that it achieves 80.93% of mean accuracy in classifying music genres and outperforms other 1D CNN architectures.

##### https://arxiv.org/abs/2105.07302

#### bibtex:
@article{Allamy2021,
  author    = {Safaa Allamy and
               Alessandro Lameiras Koerich},
  title     = {1D {CNN} Architectures for Music Genre Classification},
  journal   = {CoRR},
  volume    = {abs/2105.07302},
  year      = {2021},
  url       = {https://arxiv.org/abs/2105.07302},
  archivePrefix = {arXiv},
  eprint    = {2105.07302}}
  
