# Cronovisor MCP Spectrum

A scientific prototype of a **time-viewing machine** (Cronovisor) that connects the electromagnetic spectrum to temporal observation via the Model Context Protocol (MCP).

## Concept
The electromagnetic spectrum is pure energy traveling as waves. Each frequency band is a "channel." This app maps:

- **Past** → low-frequency radio & historical records (long wavelengths carry echoes of what already happened)
- **Present** → visible light & real-time sensors (what is happening now)
- **Future** → high-frequency bands + predictive models (short wavelengths, high energy, scenario projections)

## Spectrum Bands
| Band | Frequency | Role in Cronovisor |
|------|-----------|--------------------|
| Radio | 3 kHz – 300 GHz | Past channel — archives, signals, historical data |
| Infrared | 300 GHz – 430 THz | Thermal present — heat signatures, live activity |
| Visible | 430 – 750 THz | Live present — real-time observation |
| Ultraviolet | 750 THz – 30 PHz | Near-future — UV damage, short-term trends |
| X-Ray | 30 PHz – 30 EHz | Deep future — high-energy projections |
| Gamma | > 30 EHz | Extreme scenarios — rare, high-impact events |

## MCP Tools
The `mcp_server.py` exposes tools an AI agent can call:

- `list_spectrum_bands` — list all bands with roles
- `tune_channel(band, temporal_mode)` — tune to a band + past/present/future
- `observe(band, temporal_mode, query)` — get a simulated observation
- `predict_future(band, horizon_years)` — project scenarios

## Run
```bash
python mcp_server.py
```
Then open `index.html` in a browser for the interactive viewer.

## Honest note
This is a **conceptual + data-driven** prototype. The future is not written; the machine shows *possible scenarios* based on patterns, not fixed destinies.
