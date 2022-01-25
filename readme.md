# End-to-end speech synthesis with use of architecture of FastSpeech 2
## General note
This is the presentation of the project made initially as diploma project in Warsaw University of Technology, postgraduate course on Deep Neural Networks.
The architectures used are [FastSpeech 2](https://arxiv.org/abs/2006.04558) and [HiFi-GAN](https://arxiv.org/pdf/2010.05646.pdf) as vocoder.
Main focus was on results.

The repository contains a thesis in a form of Google Colaboratory notebook with additional folder for images used in it.

Audio samples are presented in separate [Audio Samples Notebook](https://colab.research.google.com/drive/1Cgr0z_vuYeb_zHGAsphcTvbg98GuFQyT?usp=sharing), which contain samples from dataset as well as from various experiments described in thesis.

![](https://drive.google.com/uc?id=1qWGDeQQKxGyRcIG3seLmnHVBnR9PCnw2)

*Hello again. I am synthesized and generally cool.*

## Implementation
Implementatios was based on [ming024's FastSpeech 2 - PyTorch Implementation](https://github.com/ming024/FastSpeech2).


##  Dataset
Own dataset was used, created from scratch and with parameters based on [LJ Speech dataset](https://keithito.com/LJ-Speech-Dataset/).

# Abstract
In this thesis, artificial neural networks based end-to-end speech synthesis was presented with use of FastSpeech2 architecture. First, in introduction general problem of speech synthesis is introduced, followed by descriptions of dataset and architectures used. Next parts contain information about implementation of the model, and the results are presented and discussed. Last part summarizes the thesis with possible plans for future.

# References
[X. Tan, T. Qin, F. Soong, and T.-Y. Li, *Survey on Neural Speech Synthesis*](https://arxiv.org/pdf/2106.15561.pdf)

[K. Ito and L. Johnson, *The LJ Speech Dataset*](https://keithito.com/LJ-Speech-Dataset/)

[*Project Guthenberg*](https://www.gutenberg.org/)

[J. Shen, R. Pang, R. J. Weiss,et al., *Natural TTS Synthesis By Conditioning Wavenet On Mel Spectrogram Predictions*](https://arxiv.org/pdf/1712.05884.pdf)

[R. Yamamoto, E. Song, and J.-M. Kim, *Parallel wavegan: A fast waveform generationmodel based on generative adversarial networks with multi-resolution spectro-gram*](https://arxiv.org/abs/1910.11480)

[N. Li, S. Liu, Y. L. S. Zhao, and M. Liu, *Neural speech synthesis with transformer network*](https://ojs.aaai.org/index.php/AAAI/article/view/4642)

[Y. Ren, Y. Ruan, X. Tan,et al., *FastSpeech: Fast, Robust and Controllable Text to Speech*](https://arxiv.org/pdf/1905.09263.pdf)

[Y. Ren, C. Hu, X. Tan, et al., *FastSpeech 2: Fast and High-Quality End-to-End
Text-to-Speech*](https://arxiv.org/abs/2006.04558)

[M. McAuliffe, M. Socolof, S. Mihuc, M. Wagner, and M. Sonderegger, *Montreal Forced Aligner*](https://github.com/MontrealCorpusTools/Montreal-Forced-Aligner)

[D. Povey, A. Ghoshal, G. Boulianne,et al., *Kaldi*](http://kaldi-asr.org/)

[C. M. Chien, J. H. Lin, C. Y. Huang, P. C. Hsu, and H. Y. Lee, *FastSpeech 2 - PyTorch Implementation*](https://github.com/ming024/FastSpeech2)

[W. Ping, K. Peng, A. Gibiansky,et al., *Deep Voice 3: Scaling Text-to-Speech with Convolutional Sequence Learning*](https://arxiv.org/pdf/1710.07654.pdf)

[A. van den Oord, S. Dieleman, H. Zen,et al., *WaveNet: A generative model for rawaudio*](https://arxiv.org/abs/1609.03499)

[R. Prenger, R. Valle, and B. Catanzaro, *WaveGlow: A flow-based generative net-work for speech synthesis model based on generative adversarial networks withmulti-resolution spectrogram*](https://arxiv.org/abs/1811.00002)

[K. Jungil, K. Jaehyeon, and B. Jaekyoun, *HiFi-GAN: Generative Adversarial Networks for Efficient and High Fidelity Speech Synthesis*](https://arxiv.org/pdf/2010.05646.pdf)

__________________________________________________________________________

Attachment: [K. Papis, *End-to-end speech synthesis with use of architecture of FastSpeech 2. Attachment - Audio samples*](https://colab.research.google.com/drive/1Cgr0z_vuYeb_zHGAsphcTvbg98GuFQyT?usp=sharing).
