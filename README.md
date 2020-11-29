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
1. Initialize
    * Does your synth initialize with a preset?
    * Is there a reset button?
    * Does it load in an initialized state with just a plain waveform?
2. What waveforms does your synth offer?
3. How does your synth implement pulse width?
    * Pulse Width knob
        * Maybe be labelled something else like "Symmetry".
    * A set of preset pulse waveforms with different widths.

## Lesson 2: Brightness
### Notes
* The [**low pass filter**](https://en.wikipedia.org/wiki/Low-pass_filter) determines the brightness of the sound.
    * It is controlled by the **cutoff knob**.
* Slightly reducing the cutoff is good for when you want a bright sound, but with less sizzle.
* A common side-effect of a low-pass filter is a decrease in volume.
    * To compensate, you can turn up the synth's *main volume*.
    * Great for bass patches with a round and heavy sound.
* Focus on the most obvious effect on the sound first.

### On Your Own
1. Try out the **Low Pass Filter**.
2. Program a couple of bass patches.

## Lesson 3: Volume, Press, and Release
### Notes
* Amp Envelope
    * Modulates synth's volume over time.
    * Modulate = Change
    * Attack
        * How long it takes for your sound to go from silence to full volume.
    * Release
        * Begins when you release a key.
        * How long it takes for your sound to go from it's current sound to silence.

### On Your Own
Program a Bass, Lead, and Pad.

1. Bass
    * Low Cutoff
    * Square Wave
    * Zero Amp Attack
    * Set Release to desired
2. Lead
    * Bright
    * Zero Amp Attack
    * Set Release to desired
3. Pad
    * Soft Attack
    * Long Release
    * Low Cutoff
