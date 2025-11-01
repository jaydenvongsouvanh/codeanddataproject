## Table of contents
* [Overview](#Overview)
* [Concept](#Concept)
* [Technical Details](#Technical-Details)
* [Code Breakdown](#code-breakdown)
* [Inspiration](#Inspiration)

# Overview
This project reimagines “This Is How It Feels” by d4vd and Laufey through a custom-coded composition in TunePad. It focuses on blending melodic piano phrasing with subtle harmonic progressions to capture the song’s introspective and cinematic tone while adding a personal reinterpretation through timing, chord voicing, and rhythm variation. The piece was created as part of a music coding and composition task, demonstrating how Python-based music logic can be used to reconstruct and reinterpret contemporary music.

## Concept
The aim was not just to recreate the original melody, but to reinterpret it through: 
Layered right- and left-hand piano sequences 
Emphasis on emotional phrasing through altered sustain lengths 
Simplified rhythmic texture that preserves the song’s nostalgic atmosphere 
Gradual dynamic build from the intro to chorus

### Technical Details
Platform: TunePad (Python-based music platform) 
Tempo: 80 BPM 
Key: C Major 
Meter: 4/4 
Instruments: Piano

#### Code Breakdown
The code is broken down into 3 sections, intor, verse and chorus. Each section is programmed using TunePsd's playNote() functions specifying pitch, beat timing and sustain.
Right hand tracks represent melody
Left hand tracks represent the songs harmonic rhythm and bass foundation
Chorus uses repetitive ascending notes and structure to emulate a string-like swell effect
#### Code Example
playNote(54, beats=0.00, sustain=1.5)
playNote(57, beats=1.5)
playNote(64, beats=0.5)

##### Inspiration
This code was inspired by the song “This Is How It Feels” by d4vd and Laufey using sheet music on Musescore created by [@squeet] (https://musescore.com/user/55653428/scores/12830704)
