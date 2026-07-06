# THE ULTIMATE MATRIX RAIN

> *"The Matrix has you... Follow the white rabbit. But not too closely, or you'll miss the glitch."*


## The Story Behind the Code

In the depths of the Matrix, the Architect sits beyond the simulation, surrounded by flickering screens, the Architect oversees the perfect creation. 

On another side in reality, Tank is watching the code flowning, but something's wrong, it's too chaotic, too unreadable. He's been asking for a better version, one where the characters are clear, where the symbols are decipherable, where the data flows in perfect harmony.

So we had an idea. We've decrypted the Architect's secret: the Matrix isn't meant to be read in cerebral pain, it's meant to be experienced like art. So we've created **The Ultimate Matrix Rain**, a 2.5D WebGL masterpiece that lets you *see* the code, *feel* the glitch, and *understand* the chaos.

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
    layers: 8, // max 11
    frontLayerSize: 250.0,
    sizeRatio: 0.6,
    frontOpacity: 0.1,
    matrixColor: 0x44ff88, // or Flash green 0x00ff44 , Cyberppunk blue 0x0088ff, Ghost white "#3ff3ee3"
    bloomStrength: 2.2,
    // Add more if you need
});
```


### Parameter Descriptions

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


## The Architecture Secret

Tank just wanted a clean, readable Matrix, but we gave him something better: a simulation that feels alive. The characters fall, the trails flow, and the distortions are real. You can see it, but you can’t touch it.

So, what’s the secret? It’s not just about reading the code—it’s about feeling its rhythm. And that’s exactly what this Matrix Rain does.


## How to Use

1. **Move your mouse** to pan around the Matrix.
2. **Click** anywhere to trigger a glitch.
3. **Double-click** to warp into the Matrix.

**Mouse or Touch** it works on desktop and mobile devices.


## The Final Thought

The Matrix is not a place. It’s a system. We’ve built an experience that shows it for what it really is: a beautiful, chaotic, and deeply immersive digital reality.
