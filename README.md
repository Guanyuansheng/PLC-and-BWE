# PLC-and-BWE
Proposed joint algorithm is implemented by a temporal-frequency hybrid generative adversarial framework as shown in Fig.1 and make several optimizations toward computational efficiency and speech quality. First, We transform the end-to-end model into streaming inference for real-time communication, generating wideband speech frame-by-frame with low latency and reasonable computational complexity. Second, we propose a novel UNet-style generator combined with proposed gated vector quantizers, which learns to map the intra-frame and inter-frame speech information to a highlevel abstract space. The proposed gated vector quantizer performs secondary encoding of the speech features and demonstrates that audio representation learning can capture important content features in speech and reduce the impact of lost perturbations. Third, to further improve the reconstruction quality, a multi-resolution temporal discriminator and a complex spectrum discriminator are integrated for our speech reconstruction task. Inspired by high-fidelity speech synthesis with multi-resolution time-frequency features in GAN, we consider both the waveform and complex spectrum optimization to alleviate the transitional distortion caused by the lost speech frames. We verify the reconstruction performance of proposed model through experiments, and the results indicate that the proposed streaming method is still competitive among state-of-the-art offline algorithms.
In this project, we will show the mapping results from 4 kHz narrowband, lost speech to 8 kHz broadband complete speech, in the form of audio and pictures.
