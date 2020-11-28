# Syntorial Notes

* [Lesson 1: Your Basic Sound](#lesson-1-your-basic-sound)

## Lesson 1: Your Basic Sound
### Notes
* Oscillator
    * Responsible for generating initial raw sound, the waveform.
* [Saw Waveform](https://en.wikipedia.org/wiki/Sawtooth_wave)
    * Bright and edgy.
    * Popular all-purpose waveform.
    * Thin and buzzy in the lower register.
* [Pulse Waveform](https://en.wikipedia.org/wiki/Pulse_wave)
    * More video-game-esque quality.
    * More artificial sounding than the saw waveform. 
    * Also buzzy, but *thicker* than the saw in the lower register.
    * Pulse Width
        * Decreasing the pulse width makes the sound thinner, edgier, and almost saw-like.
        * In the upper register, a *thin* pulse sounds very similar to a saw wave.
    * A [**square waveform**](https://en.wikipedia.org/wiki/Square_wave) is a special type of pulse waveform in which the amplitude alternates at a steady frequency between fixed minimum and maximum values.

### On Your Own
1. Ensure the synth of choice is **subtractive**.
2. Initialize
    * Does your synth initialize with a preset?
    * Is there a reset button?
    * Does it load in an initialized state with just a plain waveform?
3. What waveforms does your synth offer?
4. How does your synth implement pulse width?
    * Pulse Width knob
        * Maybe be labelled something else like "Symmetry".
    * A set of preset pulse waveforms with different widths.
