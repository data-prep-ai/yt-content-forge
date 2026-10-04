# TOOLCHAIN REQUIREMENTS

Muse must inventory the actual environment during bootstrap. Do not assume a tool exists because a workflow mentions it.

## Required capabilities

### Research
- web search/browser
- source downloading
- PDF/document inspection
- image inspection
- metadata capture

### Media preparation
- FFmpeg or equivalent video/audio encoding
- image resizing/cropping
- waveform/audio inspection
- subtitle/caption processing
- format conversion

### Voice
At least one repeatable TTS/voice path with:
- consistent voice identity
- controllable pacing
- WAV/PCM output where possible
- pronunciation controls or a pronunciation workaround
- commercial-use rights suitable for the channel

### Visual/animation
At least one reliable path for:
- 2.5D archival movement
- maps
- diagrams
- text/annotation animation
- simple timeline graphics
- restrained lower thirds
- disclosed reconstruction

Possible implementation: NLE + compositor, Blender, SVG/HTML animation, Remotion, or another deterministic renderer. Muse must record what is actually available.

### Editing
The system must be able to create an actual timeline, not merely an edit decision list.

At minimum it needs:
- video tracks
- still images
- voice track
- music track
- SFX/primary-audio track when permitted
- text/graphics overlays
- basic keyframes/motion
- cuts
- audio gain/ducking
- final export

### QA
- final render inspection
- duration/codec/resolution checks
- audio presence/loudness inspection where supported
- missing media detection
- source/rights audit

## Bootstrap output

Write actual detected tools + versions to `09_SYSTEM/tooling/TOOLCHAIN_INVENTORY.md`.

Do not mark a capability as available until it has been tested with a real command or real short render/export.
