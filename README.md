# SENTINEL demo

A replay demo of SENTINEL, a multimodal language model that fuses camera, passive RF and audio into one decision: is a drone present? It was made for the IE4422 Multimodal Large Language Models group project (Table 1) at NTU.

**Open the demo:** https://jjietay.github.io/sentinel-demo/

The page replays saved model outputs from our Version 2 evaluation. No model runs in the browser.

## How to use it

| Key | Action |
|---|---|
| `R` | Open the list of recordings |
| `1` to `5` | Open a recording |
| `Space` | Start the replay |
| `1`, `2`, `3` | During a replay: switch the camera, RF or audio off or on |
| `X` | Show the inside of the model for the current decision |
| `N` | Next recording |
| `M` | Map |
| `T` | Light or dark mode |

On the map, drag to move, scroll to zoom, and use the arrow keys.

## Sources

- TRIDENT dataset: I. Alla, S. Yahia and V. Loscri, "TRIDENT: Tri-modal real-time intrusion detection engine for new targets," arXiv:2504.06417, 2025. https://github.com/trimodaldataset/multi-modal-drone-data
- Halmstad drone dataset: F. Svanström, F. Alonso-Fernandez and C. Englund, "A dataset for multi-sensor drone detection," Data in Brief, vol. 39, 107521, 2021.
- RFVS dataset: https://github.com/Stella050527/RFVS
- Map data: OpenStreetMap contributors, https://www.openstreetmap.org/copyright

The sensor site on the map is an example. No recording was made at NTU.
