# Horror-Post-Processing-For-Unity-6-URP
-----

## SETUP INSTRUCTIONS

### STEP 1: INSTALL URP

  * **Window** \> **Package Manager**
  * Search for "**Universal RP**" and install it

### STEP 2: CREATE URP ASSET

  * Right-click in the Project window: **Create** \> **Rendering** \> **URP Asset**
  * **Edit** \> **Project Settings** \> **Graphics**
  * Drag the URP Asset into the "**Scriptable Render Pipeline Settings**" field

### STEP 3: ENABLE POST-PROCESSING

  * Select the **Main Camera**
  * In the Camera Component, check the "**Post Processing**" box

### STEP 4: ATTACH SCRIPT

  * Drag this script onto the **Main Camera**
  * The Volume will be created automatically\!

### STEP 5: SEE THE RESULTS\!

  * **NO PLAY MODE REQUIRED\!**
  * The effects are immediately visible in the **Scene View**
  * Change the sliders in the Inspector, and the effects update instantly

-----

## CONTROLABLE FEATURES

### VISUAL EFFECTS:

| Feature | Description |
| :--- | :--- |
| **Vignette** | Darkening edges |
| **Film Grain** | Old film noise |
| **Chromatic Aberration** | Color separation |
| **Color Grading** | Desaturated horror color |
| **Lens Distortion** | Lens warping |
| **Bloom** | Glowing light |
| **Motion Blur** | Movement blur |
| **Depth of Field** | Focus blur |
| **Split Toning** | Shadow/Highlight color tinting |
| **Tonemapping** | ACES, Neutral, etc. |

### DYNAMIC EFFECTS:

| Feature | Description |
| :--- | :--- |
| **Breathing** | Pulsating Vignette effect |
| **Flicker** | Brightness flickering |
| **Screen Distortion** | Animated screen warping |

### RUNTIME COMMANDS:

```csharp
SetIntensity(0.8f);        // Change horror intensity
TriggerJumpScare(0.5f);    // Jumpscare effect
TriggerGlitch(0.2f);       // Glitch effect
```

-----

## PRESET RECOMMENDATIONS:

### CLASSIC HORROR:

  * Vignette: **0.7**
  * Saturation: **-50**
  * Film Grain: **0.5**
  * Breathing: **ON**

### PARANORMAL:

  * Chromatic Aberration: **0.6**
  * Bloom: **2.0**
  * Color Filter: **Blue tint**
  * Flicker: **ON**

### SLASHER:

  * Contrast: **30**
  * Saturation: **-30**
  * Motion Blur: **0.4**
  * Grain: **0.6**

### FOUND FOOTAGE:

  * Film Grain: **0.8**
  * Vignette: **0.8**
  * Chromatic: **0.5**
  * Lens Distortion: **-0.3**

-----
