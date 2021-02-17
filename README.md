# arduino_fbench
fbench port to Arduino (compatible with LGT8Fx)

This is a quick and dirty port of the [John Walker's Floating Point Benchmark](https://www.fourmilab.ch/fbench/fbench.html) to Arduino.

This port is mainly intended to compare performances between ATmega328p and LGT8F328p, and between different compilation optimization levels.

| optimization | LGT8F328p @ 32MHz | LGT8F328p @ 16MHz | ATmega328p @ 16MHz |
|:-:|:-:|:-:|:-:|
| Os | 4.670s |||
| O0 | 5.105s |||
| O1 | 4.657s |||
| O2 | 4.651s |||
| O3 | 4.651s | 9.301s | 10.894s |
| Ofast | 4.605s | 9.209s | 10.774s |

# License

The license is any license that is compatible with the original license of Fbench visible into the source code.
