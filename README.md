# THE ULTIMATE MATRIX RAIN

> *"The Matrix has you... Follow the white rabbit. But not too closely, or you'll miss the glitch."*


## The Story Behind the Code

In the depths of the Matrix, the Architect sits beyond the simulation, oversees the perfect creation, surrounded by flickering screens. 

On another side in reality, Tank is watching the same thing, but for him it's Matrix code flowning. Something's wrong, it's too chaotic, too unreadable. Tank's been asking for a better version to the Rebels Operator Division for a long time, one where the characters are clear, where the symbols are decipherable, where the data flows in perfect harmony.

So we had an idea and find out that the Matrix isn't meant to be read in cerebral pain, it's meant to be experienced like art. So we've created **The Ultimate Matrix Rain**, a 2.5D WebGL masterpiece that lets you *see* the code, *feel* the glitch, and *understand* the chaos.

When you click on the screen, the Matrix glitches because you can't access it. Why? Because the Matrix is a simulation of reality, and the Architect's secrets are meant to remain hidden. You can *see* it, but you can't *access* it. That's the point to to preserve the illusion.

This Matrix Rain is available as a web component (see below) or a screensaver for linux GNOME (see sreensaver dir).


## Features & Glitches

- **2.5D WebGL Rendering**: Experience the Matrix in a new dimension with depth and perspective.
- **Dynamic Glitch Effects**: Click anywhere to trigger a glitch, but don't expect to gain access.
- **FOV Warp**: Double-tap to warp your view into the Matrix's core. If you are really trying to enter.
- **Scanning Lines**: Scanlines add that classic CRT feel to your experience.
- **Bloom Effects**: The Matrix glows with a soft, neon light that makes everything pop.


## JavaScript Configuration

The Ultimate Matrix Rain is highly configurable. You can create multiple rain on the same page, run it full screen or in specific div. Here's what each parameter does:

```javascript
// Create a new Matrix Rain
new MatrixRain('matrix1', {
    // --- LAYER
    layers: 8, // Max 11
    volumeHeight: 1200,
    frontLayerSize: 250,
    sizeRatio: 0.6,
    frontOpacity: 0.2,
    // --- TAIL
    matrixColor: 0x19e88e,
    tailLength: 18,
    tailParallax: 0.4,
    tailFade: 0.7,
    charRerollRate: 1.0,
    // --- DROP SPEED
    baseDropSpeed: 280,
    speedParallax: 45,
    // --- BLOOM
    bloomStrength: 2,
    bloomRadius: 0.4,
    bloomThreshold: 0.15,
    bloomGradientSize: 0.55,
    // --- MATRIX ERRORS
    errorRate: 0.001,
    errorRateGlitchingChar: 0.5,
    partialErrorRate: 0.01,
    partialErrorSize: 0.4,
    errorColor: 0xff0000,
    // --- DECRYPT HEAD
    decryptColor: 0x3ff3ee3,
    decryptStrength: 1.1,
    decryptMix: 0.8,
    decryptFlashSize: 0.2,
    decryptScrambleSize: 1.2,
    // --- DESTRUCT TAIL
    destructColor: 0xffffff,
    destructStrength: 1.8,
    destructMix: 0.8,
    destructFlashSize: 1.5,
    destructAlphaBoost: 0.8,
    // --- RAIN DENSITY
    layerRainPerc: 0.7,
    layerDensityRamp: 1,
    repulsionRadius: 20,
    repulsionDepth: 2.5,
});
```


### Parameter Descriptions

This is the operators controls everything you need to read the matrix without pain:


| Parameter         | Description |
|------------------|-------------|
| `layers`         | Number of layers in the Matrix rain (max 11). More layers = more depth. |
| `volumeHeight`   | The height of the 3D volume the rain falls through. |
| `frontLayerSize` | Size of the front layer of characters. |
| `sizeRatio`      | Ratio by which each layer shrinks as it goes back. |
| `frontOpacity`   | Opacity of the front layer (0 = invisible, 1 = solid). |
| `matrixColor`    | Color of the Matrix characters (use hex values). |
| `tailLength`     | Length of the tail behind each falling character. |
| `tailParallax`   | Controls how much the tail length changes with depth (0 = uniform, 1 = exponential). |
| `baseDropSpeed`  | Base speed of the falling characters. |
| `speedParallax`  | Speed variation between layers (higher = more variation). |
| `bloomStrength`  | Intensity of the glow effect. |
| `bloomRadius`    | Radius of the bloom effect. |
| `bloomThreshold` | Threshold for the bloom effect to kick in. |
|`enableMoveFX` / `enableClickFX` | true by default |


## The Architecture Secret

Tank just wanted a clean, readable Matrix, but we gave him something better: a simulation that feels alive. An engine where he can set everything. The characters fall, the trails flow, and the distortions are real. You can see it, but you can’t touch it.

So, what’s the secret? It’s not just about reading the code—it’s about feeling its rhythm. And that’s exactly what this Matrix Rain does.


## How to Use

1. **Move your mouse** to pan around the Matrix.
2. **Click** anywhere to trigger a glitch.
3. **Double-click** to warp into the Matrix.

**Mouse or Touch** it works on desktop and mobile devices.


## The Final Thought

The Matrix is not a place. It’s a system. We’ve built an experience that shows it for what it really is: a beautiful, chaotic, and deeply immersive digital reality.


## Author note

I made a complete pack with screensaver and shadertoy :
- For sceensaver see the `screensaver/` dir.
- [Shadertoy Pixel Rain](https://www.shadertoy.com/view/Nfc3zN)
- [Shadertoy Rain](https://www.shadertoy.com/view/sc33R4)

Linux screen saver is in final testing and coming soon.


## Release mote
- v7 - The Ultimate Matrix Rain Engine! Coming soon.
- v6 - Added the decrypting head and new settings. This is now a fully customisable Matrix Engine, The Ultimate Matrix Engine! 
- v5 - I start adding what was missing, since I moved to a class structure in v4. Lots of subtle details and calibration.
- v1-4 - This started for fun. We were making a Matrix Rain contest with a friend (who introduced the webgl and the beautiful destruct effect on the contest but in a too heavy way). Then v4 is the begin of a new story, and I decided to release this because I think it a cool work that Matrix Rain lover will approciate.


## Licence

GPL-3.0 license
