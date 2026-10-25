# 02 Backlit Hair Rainbow

**▶ Play it:** https://hanji-xu.github.io/backlit-hair-rainbow/

**Observation:** hold your forearm so it just hides the sun, and the fine hairs along its edge light up in short sparks of colour: violet, gold, green, pink. They are not reflecting and not acting as prisms. Each hair is a slit in reverse: it diffracts sunlight.

**What it does:** the first page is just the picture and its tuning. Drag the sun to move it, drag anywhere else to turn the arm, pick a hair type and set the diameter. Every glint is computed from diffraction around a cylinder, convolved with the real size of the sun's disk, weighted by the solar spectrum and converted to colour with the CIE 1931 observer. The second page (**How it works**) holds the explanation, a chart of colour against angle from the sun, the equations, the constants table and sources.

**Physics (documented in the page):**
- Fraunhofer/Babinet strip diffraction, σ = (d²/λ)·sinc²(πd sinθ/λ), with dark fringes at sin θ = mλ/d.
- Cone condition (s − v)·t = 0: only stretches of hair lying across the sun direction glint, so you see short sparks that slide along curved hairs.
- Convolution with the limb-darkened solar disk (R = 0.2666°) washes out colour on hairs thicker than about 60 µm, which is why fine vellus hair (10–30 µm) is vivid and scalp hair (70–120 µm) is not.
- Planck 5772 K spectrum with Rayleigh air-mass reddening; CIE 1931 colour matching (Wyman 2013 fit).
- Refraction through the hair (TT lobe after Marschner 2003 / pbrt melanin model) is included and shown not to be the rainbow.

**Flagged:** the cuticle-scale grating is optional and off by default, because its transmission efficiency is unmeasured. The faint arm and the eye-like tone curve are display aids. Estimated constants are tagged in the page's constants table.

---

Part of **Art Insights**, a series of interactive pieces by Hanji Xu. Open `index.html` in a current browser; it is a single self-contained file with no network access or libraries. See also [01 Stubble Field](https://github.com/Hanji-Xu/stubble-vector-field).
