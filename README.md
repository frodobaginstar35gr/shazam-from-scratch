# Shazam From Scratch 🎵

A music recognition engine built in Java — identifying songs from short audio clips 
using audio fingerprinting, FFT frequency analysis, and hash-based pattern matching.

Built to deepen my understanding of signal processing, hashing algorithms, and 
real-world system design.

---

## How It Works

1. **Audio Input** — Load an audio clip (WAV format)
2. **FFT Analysis** — Convert audio signal into frequency spectrum using Fast Fourier Transform
3. **Peak Detection** — Identify dominant frequency peaks across time windows
4. **Fingerprinting** — Generate a unique hash from frequency peak combinations
5. **Matching** — Compare fingerprint against database to identify the song

---

## Tech Stack

- Java 17
- FFT via TarsosDSP library
- HashMap-based fingerprint database
- WAV audio processing

---

## Project Status

🚧 In Progress — Started March 2025

- [ ] Audio loading & WAV parsing
- [ ] FFT implementation
- [ ] Peak detection algorithm
- [ ] Fingerprint hash generation
- [ ] Song database + matching engine
- [ ] CLI interface
- [ ] Accuracy testing

---

## What I'm Learning

- Fast Fourier Transform and signal processing fundamentals
- How audio fingerprinting works at a low level
- Applying hashing algorithms to real-world problems
- Java audio libraries and byte-level data processing


