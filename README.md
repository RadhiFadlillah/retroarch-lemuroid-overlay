# Lemuroid Overlay for RetroArch

[Lemuroid](https://github.com/Swordfish90/Lemuroid) is a Libretro front end for Android. Its main goal is ease of use, so it comes with a nice UI and pleasant UX. As much as I love it, there are several deal breaker features for me that missing from Lemuroid:

- No cheat support.
- No 7-zip support.
- No custom shader.

Thanks to those issues, I come back to RetroArch. However, I really like the overlay that used by Lemuroid, so I decided to clone it for RetroArch.

This overlay is designed for 20:9 screen, which is what my phone use, and apparently is the [most popular](https://gs.statcounter.com/screen-resolution-stats/mobile/worldwide) aspect ratio right now.

## Available Platforms

This overlay is available for several platforms, each has both landscape and portrait mode:

- PSX (with and without analog)
- SNES
- GBA
- NES (which can also used for GB and GBC)

## Project Structure

```
retroarch-lemuroid-overlay
├── dist ...... the final result that can be used directly in RetroArch
├── doc	....... files that used for this readme
└── src
    ├── ods ... spreadsheet that I use to generate the cfg file
    └── svg ... svg images that I use to design the overlay
```

## Installation

Download the overlay from `dist/` directory or from the [release page](https://github.com/RadhiFadlillah/retroarch-lemuroid-overlay/releases/), then use it in RetroArch.

## Recommended Configuration

Set "Overlay Opacity" to 1.0, since it's already a bit transparent.

## Screenshots

<details>
	<summary><b>PSX with analog</b></summary><br/>
	<img src="/doc/psx-analog-landscape.jpg" alt="Screenshot of PSX with analog in landscape mode"/>
</details>

<details>
	<summary><b>PSX without analog</b></summary><br/>
	<img src="/doc/psx-landscape.jpg" alt="Screenshot of PSX in landscape mode"/>
</details>

<details>
	<summary><b>SNES</b></summary><br/>
	<img src="/doc/snes-landscape.jpg" alt="Screenshot of SNES in landscape mode"/>
</details>

<details>
	<summary><b>GBA</b></summary><br/>
	<img src="/doc/gba-landscape.jpg" alt="Screenshot of GBA in landscape mode"/>
</details>

<details>
	<summary><b>GBC</b></summary><br/>
	<img src="/doc/gbc-landscape.jpg" alt="Screenshot of GBC in landscape mode"/>
</details>

<details>
	<summary><b>All in portrait mode</b></summary><br/>
	<img src="/doc/all-portrait.jpg" alt="Screenshot of all platform in portrait mode"/>
</details>

## Acknowledgements

- [**Swordfish90**](https://github.com/Swordfish90) for creating [Lemuroid](https://github.com/Swordfish90/Lemuroid).
- [**Valent-in**](https://github.com/Valent-in) for creating [RetroPad Editor](https://github.com/Valent-in/retropad-editor).

## License

Since both Lemuroid and RetroArch use GPLv3, I think it just follows that here we use GPLv3 as well.
