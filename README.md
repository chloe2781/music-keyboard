# music-keyboard
Building my own keyboard on the web using WebAudio.

## Check it out here:
https://chloe2781.github.io/music-keyboard/

## How does it work?
I built a simple keyboard interface that plays a single note when a key is pressed down. Try it out!

## Mapping:
```
  key - note
    Z - C
    S - C#
    X - D
    D - D#
    C - E
    V - F
    G - F#
    B - G
    H - G#
    N - A
    J - A#
    M - B
    Q - C
    2 - C#
    W - D
    3 - D#
    E - E
    R - F
    5 - F#
    T - G
    6 - G#
    Y - A
    7 - A#
    U - B
    I - C
```

## Features
Waveform selection:
- sine
- square
- sawtooth
- triangle

ADSR envelopes for notes to prevent zero-ing clicks

Polyphonic mode - allowing the user to play two keys at once, preventing “clipping” (no amp levels >1)
