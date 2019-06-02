## Dual-Tone Multi-Frequency decoding and encoding


### Part1 : Encoding
- [DTMF_table_provider.m](./DTMF_table_provider.m)
- [encoder.m](./encoder.m)

The first Matlab code saves DTMF table as a structural array which contains characters and analogous frequencies. The second one gets a string of characters and reads the array provided by the former code and for each of valid characters play the analogous dual tone for 250 ms.


------
### Part2 : decoding
- [DTMF_matVec_provider.m](./DTMF_matVec_provider.m)
- [decoder.m](./decoder.m)

The first Matlab code saves characters of DTMF table as a matrix and each of two frequency axis as a vector. The second code gets a string of path file of a .wav file and outputs analogous string.
----
#### Learn more
- DTFM <br/>
  - [WikiPedia](https://en.wikipedia.org/wiki/Dual-tone_multi-frequency_signaling) <br/>
- Goertzel algorithm <br/>
 - [WikiPedia](https://en.wikipedia.org/wiki/Goertzel_algorithm)<br/>
 - [Matlab Doc](https://www.mathworks.com/help/signal/ref/goertzel.html)
- Descrete Fourier Transform
 - [Lecture 7 - TheDiscreteFourierTransform](http://www.robots.ox.ac.uk/%7Esjrob/Teaching/SP/l7.pdf)
 - [How to Interpret FFT results – complex DFT, frequency bins and FFTShift](https://www.gaussianwaves.com/2015/11/interpreting-fft-results-complex-dft-frequency-bins-and-fftshift/)
