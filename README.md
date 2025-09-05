# Turbo Speedo Video

A Raycast extension to adjust video playback speed using FFmpeg. Speed up or slow down your videos with ease!

## Features

- **Speed Range**: Adjust video speed from 0.25x to 40x
- **Smart Audio Handling**: Automatically adjusts audio speed for optimal quality
- **Multiple Formats**: Supports MP4, MOV, AVI, MKV, WebM, FLV, WMV, M4V, 3GP, OGV
- **Easy to Use**: Simple dropdown interface with clear speed options
- **Fast Processing**: Powered by FFmpeg for reliable video processing

## Requirements

- **FFmpeg**: Must be installed on your system
  - Install via Homebrew: `brew install ffmpeg`
  - Or download from [ffmpeg.org](https://ffmpeg.org/download.html)

## Usage

1. Open Raycast (`Cmd + Space`)
2. Type "Adjust Video Speed"
3. Select your video file
4. Choose your desired speed multiplier (0.25x - 40x)
5. Set your output path
6. Press Enter to process!

## Speed Options

- **0.25x - 2x**: Full audio quality maintained
- **2.5x - 40x**: Audio speed adjusted for optimal playback

## Installation

This extension will be available in the Raycast Store once published.

## Development

```bash
# Install dependencies
npm install

# Build the extension
npm run build

# Run tests
npm test

# Publish to Raycast Store
npm run publish
```

## License

MIT