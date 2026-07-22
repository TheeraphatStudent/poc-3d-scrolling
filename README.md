# POC 3D Scrolling

## Prompt

```
1. Apple-Scroll-Animation (code prompt — Gemini/coding)

Using this folder of image frames, build a scroll-linked image sequence on an HTML canvas. Preload all the frames first, then map the scroll position to the frame index so the animation plays frame by frame as the user scrolls, the same technique Apple uses on the AirPods page. Use GSAP and ScrollTrigger. Pin the canvas while the sequence plays, scrub it smoothly to scroll so there's no stutter, keep it sharp and centered on mobile, and add a graceful fallback if the frames are still loading. Give me a single self-contained file I can drop straight into my site.

2. Start Frame (image prompt)

High-end studio product photograph of [YOUR PRODUCT], fully assembled and intact, floating dead center against a seamless matte light-grey studio background. Straight-on view, perfectly level camera, soft even studio lighting, one subtle soft shadow directly beneath the product, photorealistic, ultra sharp, high detail. Keep the product small enough in frame that there is generous empty space on every side. No text, no watermark, no hands, no props, no brand logos. Landscape 16:9.

3. End Frame (image prompt)

High-end studio product photograph of the same [YOUR PRODUCT] as a clean exploded view: the outer casing separated and every major internal component pulled apart and floating in an organized, evenly spaced arrangement along one axis, like a technical teardown render. Same straight-on view, same perfectly level camera, same soft even studio lighting, same seamless matte light-grey studio background, one subtle soft shadow beneath. The core body of the product stays in the exact center at the same size, with the parts spreading outward around it. Photorealistic, ultra sharp, high detail. No text, no watermark, no hands, no props, no brand logos. Landscape 16:9.
```

## How it work

1. Create an start frame / end frame usage ai to generated an image or something else!

2. Asking agent with Prompt > Start Frame + End Frame to generate an video

3. Go to ezgif for convert video to gif

4. Convert gif to actual image like ezgif-split

5. Usage Prompt Apple-Scroll-Animation (code prompt — Gemini/coding) to asking agent to setting up an scrolling

6. Enjoy :)
