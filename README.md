# Syntorial Notes

* [Lesson 1: Your Basic Sound](#lesson-1-your-basic-sound)
* [Lesson 2: Brightness](#lesson-2-brightness)
* [Lesson 3: Volume, Press, and Release](#lesson-3-volume-press-and-release)
* [Lesson 4: Expanding Your Basic Sound](#lesson-4-expanding-your-basic-sound)
* [Lesson 5: Brightness, Press and Release](#lesson-5-brightness-press-and-release)
* [Lesson 6: Echos](#lesson-5-echos)

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

## Lesson 4: Expanding Your Basic Sound
### Notes
* One of the most common ways to combine two oscillators is *doubling and transposing*.
    * Set the *Mix knob*
        * Determines the balance between Oscillator 1 and 2.
    * Set the *Semi knob*.
        * Moves Oscillator 2's pitch a **semi**-tone.
        * Can't just set semi-knob to *any* value as it can create *dissonance*.
        * Common Values:
            * One octave (12 semi-tones)
            * Two octaves (24 semi-tones)
            * One-fifth (7 semi-tones)
            * An octave and a fifth (19 semi-tones)

### On Your Own
Volume:
1. Does you synth have a mix knob or individual volume knobs?

Pitch:
1. How do you change the pitch of each oscillator?

Double and transpose three previous patches.

## Lesson 5: Brightness, Press, and Release
### Notes
* Filter Envelope
    * Modulates filter's cutoff.
    * Attack
        * Gradually brightens sound.
    * Release
        * Starts when you release key.
        * Determines how fast your sound drops from it's current brightness to the cutoff knob's brightness.
* Cutoff Knob
    * Determines the *darkest* your sound will ever get.
* Envelope Amount Knob
    * Determines the *brightest* your sound will ever get.
    * Really determines this distance between the cutoff knob and brightest point.
    * Thus, changes to the Cutoff Knob raise or lower the brightest point accordingly.
* Process
    1. Set Cutoff Knob to darkest point.
    2. Set Envelope Amount Knob to brightest point.
    3. Set the Attack.
* Amp release needs to be the same or greater than the filter release to hear it.
    * Set the amp envelope first as it's easier to hear *volume* changes.

### On Your Own
* Some synths may *not* give an envelope dedicated to the filter.
    * Some synths provied a Mod (modulation) Envelope instead, and you can set the destination to the filter cutoff.
* Design 3 pads
    * Soft texture
    * Low cutoff, and raise the release
    * Use the filter envelope for movement

## Lesson 6: Echos

* Delay
    * Delay creates echos
    * Delay mix knob determines balance between initial sound (dry) & echos (wet)
    * 100% Dry / 0% Wet - No echos
    * 50% Dry / 50% Wet - Maximum echos
    * Reduces volume
    * Can increase main volume to make up for the decrease
    * Two purposes:
        1. Rythmic patterns
        2. Create space (like reverb to make sound bigger)
