# Black Hole Renderer: Live Demo

A real-time, physically based black hole running in your browser: Kerr ray tracing, a relativistic accretion disk, the hot flow seen by the Event Horizon Telescope, relativistic jets, and a camera you can fly into the horizon.

### [▶ Try it live](https://cannoli-cat.github.io/black-hole-demo/)

<table>
  <tr>
    <td><img src="https://raw.githubusercontent.com/cannoli-cat/black-hole-renderer/main/Documentation~/interstellar.gif" alt="Interstellar preset"></td>
    <td><img src="https://raw.githubusercontent.com/cannoli-cat/black-hole-renderer/main/Documentation~/m87.gif" alt="M87 preset"></td>
    <td><img src="https://raw.githubusercontent.com/cannoli-cat/black-hole-renderer/main/Documentation~/sgra.gif" alt="Sgr A preset"></td>
  </tr>
</table>

This is the demo for **[Black Hole Renderer](https://github.com/cannoli-cat/black-hole-renderer)**, a Unity URP package. Everything you see here is what the package renders.

## What you can do

- **Explore:** switch between presets (Interstellar, Realistic, M87, M87 EHT, Sgr A, Flare, Quasar) and three views:
  - **Orbit:** drag to rotate around the hole, scroll to zoom.
  - **Ride along:** orbit with the gas, at the radius, height and speed you choose.
  - **Fall in:** drop freely through the event horizon from any angle.
- **Advanced:** every setting of the renderer, from spin and disk temperature to jets and the hot flow.
- **Filters:** stylized screen effects from [Stylized Rendering](https://github.com/cannoli-cat/stylized-rendering): dithering, palette swapping (load your own palette as an image, a .hex file or pasted hex colors), ink contours and sharpening.
- **Capture:** save screenshots up to 4K and record MP4 video.

## Performance

The demo starts on **Low** quality, which runs smoothly on most laptops. **High** traces the exact light paths around a spinning black hole at full resolution and needs a stronger GPU. The frame rate is shown at the bottom of the panel.

It needs a desktop browser with WebGL 2 (current Chrome, Edge, Firefox or Safari). Phones may run it slowly.

## Credits

- **Black Hole Renderer** and **Stylized Rendering** by Tyler Wolfe ([cannoli-cat](https://github.com/cannoli-cat)).
- **Star map:** [Deep Star Maps 2020](https://svs.gsfc.nasa.gov/4851), NASA/Goddard Space Flight Center Scientific Visualization Studio. Gaia DR2: ESA/Gaia/DPAC.
- **Palettes** from [Lospec](https://lospec.com/palette-list):
  - [Berry Nebula](https://lospec.com/palette-list/berry-nebula) by LostInIndigo
  - [Borkfest](https://lospec.com/palette-list/borkfest) by clarigariccus
  - [Gothic Bit](https://lospec.com/palette-list/gothic-bit) by HiroHi
  - [JustParchment8](https://lospec.com/palette-list/justparchment8) by JustJimmy
  - [Midnight Ablaze](https://lospec.com/palette-list/midnight-ablaze) by Inkpendude
  - [Obra Dinn - IBM 8503](https://lospec.com/palette-list/obra-dinn-ibm-8503) by PureAsbestos
  - [Rust Gold 8](https://lospec.com/palette-list/rust-gold-8) by Trigo Mathmancer
  - [SLSO8](https://lospec.com/palette-list/slso8) by Luis Miguel Maldonado
- **Font:** [Inter](https://rsms.me/inter/) by Rasmus Andersson, under the SIL Open Font License.
- Built with Unity 6 and the Universal Render Pipeline.
