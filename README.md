# LUT Generator

**LUT Generator** is a lightweight, single-page HTML tool that allows you to generate Lookup Tables (LUTs) for use in embedded systems, synthesizers, DAC playback, and more.  
You can easily create waveforms like sine, cosine, triangle, square, sawtooth, inverted sawtooth, white noise, or even define your own custom formulas.

🔗 **Online Demo**: [https://nonamedcat.github.io/lutcalc/](https://nonamedcat.github.io/lutcalc/)

---

## Features

- **Arbitrary Bit Resolution**: Choose any resolution between 1 and 32 bits.
- **Configurable Samples per Period**: Define how many samples compose one complete waveform cycle.
- **Waveform Types**:
  - Sine
  - Cosine
  - Triangle
  - Square
  - Sawtooth
  - Inverted Sawtooth
  - White Noise
  - Custom (define your own formula)
- **Custom Formulas**: Enter your own mathematical expressions based on a normalized time `t` (0 to 1).
- **Signed/Unsigned Output**: Select between signed or unsigned samples.
- **Output Format Options**:
  - Decimal
  - Hexadecimal
- **Preview Audio Playback**: Hear the generated waveform at a specified playback frequency.
- **Waveform Visualization**: View a discrete plot of the generated waveform.
- **Export Options**:
  - `.h` C/C++ header file
  - `.csv` file
  - `.js` JavaScript array
  - `.bin` raw binary data
- **Copy to Clipboard**: Quickly copy the generated LUT for easy pasting into your projects.

---

## How to Use

1. Select the **number of samples** and **bit resolution**.
2. Choose a **waveform type** or enter a **custom formula**.
3. Configure **signed/unsigned output** and **number format**.
4. (Optional) Set the **playback frequency** for preview.
5. Press **Play Audio** to hear the result.
6. Download the LUT in your preferred format or copy it to the clipboard.

---

## License

This project is released under the [MIT License](LICENSE).
