# modem

## Status

- Convert string of ASCII characters to their 7-bit representation. E.g., "A" is 65, or 1000001.
- Convert the binary representation into octave frequencies. Eg, if 0001000 is 1, then 1000001 is a superpositive of 1/8x and 8x frequencies
- Using 440 Hz as the base frequency, convert the superpositions of frequencies to a waveform
- Play it!

## To do

- Figure out how to extract the frequencies from a recording
    - Butterworth filters seem OK but not great
    - FFT should be the way, but it doesn't hit exactly the frequencies I need
    - https://en.wikipedia.org/wiki/Goertzel_algorithm seems to do what I want?
    - Or notch filters?
- Consider a Raspberry Pi, if this isn't going to work

## Done

- Figure out how to produce noise on Windows