# AOSP_kiss_fft
Porting kiss_fft to AOSP external framework
## Background
Support test FFT speed in Android Native code.
## How to use it
Copy the kiss_fft folder into "/platform/external/" path of AOSP.
## Version
kiss_fft version is 1.3.0
## Others
Only bm_kiss_int16_t support
./bm_kiss_int16_t -x 100000 -n 512 (512 points FFT, calculate 100000 times)
