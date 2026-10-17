# Assets to create for ping-zapper

## logo.png вЂ” 256x256, transparent, dark theme
🏓 Neon shield/gear motif matching $ping-zapper$ brand color. See master prompt in _shared docs.

## banner.png вЂ” 1280x640, background #0d1117
Large bold title $ping-zapper$, subtitle gray #8b949e, thin gradient line #00ff9dв†’#bc8cff.

## screenshots/main.png вЂ” 1280x800
Multi-server dashboard — live latency lines per target

## screenshots/settings.png вЂ” 1280x800
Traceroute view — hop table with per-hop loss bars

## screenshots/results.png вЂ” 1280x800
Alert settings — jitter/loss thresholds with tray actions

## gifs/demo.gif вЂ” 800x500, 8s, 12fps, <8MB
1. Open app, 2. click main action, 3. status turns green, 4. toggle a feature, 5. return.
ffmpeg: -vf "fps=12,scale=800:-1:flags=lanczos,split[s0][s1];[s0]palettegen[p];[s1][p]paletteuse"