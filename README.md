# CA2 Freqz
The assignment is to write a python implementation of scipy.signal.freqz. freqz calculates the frequency response (Fourier transform) of an IIR filter (difference equation).  We will discuss this further on Friday.

Your function should operate the same way as the scipy function (except that you don't need to implement the plot functionality within freqz).

You should test against scipy.signal.freqz, but your code cannot call scipy.signal.freqz.  Do not copy the source for freqz.  In particular, do not use a FFT. Compute the frequency response directly. 
