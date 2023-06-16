## 1. Render grass
### Mesh Grass
- Turn off background lighting, mix the Principle BSDF with Translucent BSDF (25%) -> sunlight will pass through grass 25% -> more realistic. 
- Add randomness to the grass color using Object Info and ColorRamp
- Add contrast to the grass using Noise Texture, then mixing it with Object Info (use Overlay)
### Particle Grass
- Mix Hair BSDF (Reflection and Transmission) and Fresnel (Layer Weight) together
- Add randomness to the grass color using Object Info and ColorRamp
- Add contrast using Noise Texture, then mixing it with Object Info (use Overlay)

![Grass](./rendered_grass.png)



