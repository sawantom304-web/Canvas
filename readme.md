**Welcome 2026 — Canvas Landing**

**Summary**: A simple single-page landing effect with a full-window animated particle canvas and a centered glassmorphism content card. The page uses a rising-particles animation drawn on a `<canvas>` and lightweight CSS for layout, gradients, and responsive scaling.

**Files**
- **HTML:** [Canvas.html](Canvas.html) — main markup and inline canvas animation script.
- **CSS:** [style.css](style.css) — typography, layout, glass effect, animations, and responsive rules.
- **README:** [readme.md](readme.md) — this file.

**How to run**
Open the page in any modern browser (no build step required):

```bash
open Canvas.html
```

**Quick notes & customization**
- Particle count: change the `for (let i = 0; i < 60; i++)` value in [Canvas.html](Canvas.html) to reduce/increase particles.
- Particle size/speed: adjust `radius` and `speedY` in the particle initialization for different motion styles.
- Background colors: edit the `background` gradient in [style.css](style.css) to change the mood.
- Font: the page loads `Poppins` from Google Fonts — swap the link in the head to change type.
- Button: the visible `Start the Journey` button is decorative; add a click listener in the script to enable navigation or actions.

**Accessibility & performance**
- Canvas is purely decorative. Consider adding a short textual fallback or `role="img"` with `aria-label` for assistive tech.
- On low-power devices, reduce the particle count or stop the animation to save CPU/battery.
- The layout is responsive — test smaller viewports and reduce heavy shadow/blur if performance issues appear.

**Notes**
- Uses `requestAnimationFrame` for smooth animation and updates canvas size on `resize`.
- No external build tools required; works as a static page.

If you want, I can: add a button click handler, expose particle settings via a small UI, or add an accessible fallback. Which would you like next?
