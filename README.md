<p align="center">
  <img src="assets/header.svg" alt="Hitaishi V, photonics and laser research" width="100%">
</p>

<p align="center">
  <a href="https://hitaishiv.com">hitaishiv.com</a> &middot;
  <a href="https://hitaishi2222.github.io/photonics_helper/">photonics_helper docs</a> &middot;
  <a href="https://github.com/hitaishi2222?tab=repositories">all repositories</a>
</p>

---

## What I work on

I study how light behaves inside chalcogenide waveguides: mid-infrared supercontinuum generation, dispersion engineering, and inverse design for structured light in fiber systems. My Ph.D. at VIT-AP University (2025) was on mid-infrared supercontinuum generation and photonic device design.

Alongside the physics, I write the software that the physics needs: a numerical library for nonlinear propagation, a GUI for analysing and plotting data, and small tools for the terminal and the lab.

## Selected work

| Project | What it does |
|---|---|
| [**photonics_helper**](https://github.com/hitaishi2222/photonics_helper) | Python library for photonics: GNLSE propagation (scalar, vector and multimode), DBR transfer matrices, SHG-FROG trace generation and PCGPA retrieval, Raman models, inverse design. Documentation at [hitaishi2222.github.io/photonics_helper](https://hitaishi2222.github.io/photonics_helper/). |
| [**GraphMatrix**](https://github.com/hitaishi2222/GraphMatrix) | Python-first scientific plotting and analysis GUI: typed worksheet columns, publication-quality figures, scriptable automation. An open alternative to OriginPro. |
| [**imli.nvim**](https://github.com/hitaishi2222/imli-nvim) | A warm ember and coffee colorscheme for Neovim: dark and light variants, Treesitter-first, with LSP semantic overrides. |
| [**labs**](https://github.com/hitaishi2222/lab-inventory) | Self-hosted inventory tracker for a research lab: equipment check-out, consumable usage, low-stock alerts, chemical safety records (CAS, GHS, expiry). Docker and Cloudflare Tunnel. |
| [**numpy_visualizer**](https://github.com/hitaishi2222/numpy_visualizer) | Local web dashboard for exploring `.npz` archives: browse named arrays, assign X and Y, and chart them in the browser, with no code required. |
| [**herdr-fingers**](https://github.com/hitaishi2222/herdr-fingers) and [**herdr-llama**](https://github.com/hitaishi2222/herdr-llama) | Herdr plugins: pick paths, URLs, IPs and hashes out of the focused pane with vimium-style letter keys, and drive `llama-server` as an agent with a live tokens-per-second dashboard. |

Smaller tools I keep reaching for: [**gghf**](https://github.com/hitaishi2222/gghf) downloads and converts Hugging Face models to GGUF with provenance tracking, [**h5extra**](https://github.com/hitaishi2222/h5extra) does fzf-style surgery inside `.h5` files, [**bro**](https://github.com/hitaishi2222/bro) searches the web from a Rust CLI, [**kinv**](https://github.com/hitaishi2222/kinv) is an expiry-first inventory TUI, [**my_cv_typst**](https://github.com/hitaishi2222/my_cv_typst) renders this CV in Typst, and [**manim_slides_skill**](https://github.com/hitaishi2222/manim_slides_skill) teaches an agent to author Manim presentations.

## Currently

- Multimode supercontinuum in chalcogenide waveguides: the four gaps that used to block it are closed, so per-mode effective area and nonlinearity now come from a real mode solve (femwell and tidy3d exports), and the engine handles multimode Raman, self-steepening with two-photon absorption and free carriers, and full-β four-wave mixing beyond the degenerate slice.
- GraphMatrix, where linked brushing between worksheets and graphs is underway on top of the digitizer, the command palette, and the color-mapped figure types.
- photonics_helper, with the documentation site and the reproductions of published results.

## Elsewhere

- Website, CV and publications: [hitaishiv.com](https://hitaishiv.com)
- Colorscheme: [imli.nvim](https://github.com/hitaishi2222/imli-nvim)
- I read issues on the tools above, and I am open to collaborations on ultrafast optics and nonlinear propagation.
