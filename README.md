# kimi-traffic-
Traffic flow simulator

## Highway Traffic Flow Simulator

A single self-contained HTML file (`index.html`) — no dependencies, no build step. Open it in any browser.

### Features
- Microscopic traffic model (Intelligent Driver Model) with lane changing, cars and trucks, across 3 lanes plus an on-ramp merge bottleneck.
- **▶ Play Demo** mode: a scripted scenario that shows a road segment becoming congested (rush-hour on-ramp surge creates a stop-and-go wave at the merge zone) and then resolving as inflow drops and the jam dissolves.
- Free-play mode with **💥 Trigger Surge**, speed control (0.5×–4×), and base-traffic density slider.
- Live stats: elapsed time, vehicle count, average speed, and throughput.

### Run it
Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```
