# LEGOAnimations Studio

A professional 3D LEGO animation application designed for filmmaking and creative professionals.

## Features

### Core
- Clean, beginner-friendly interface inspired by Blender
- Optimized for LEGO filmmaking
- Fast performance with GPU acceleration
- Professional dark UI with customizable layout

### Scene Editor
- 3D viewport with orbit, pan, zoom, and camera controls
- Grid and LEGO baseplate system
- Drag-and-drop scene building
- Object hierarchy (Outliner)
- Properties panel
- Asset Browser
- Multiple cameras
- Unlimited undo/redo
- Autosave and crash recovery

### Mecabricks Support
- Import: .mbx, .dae, .obj, .fbx, .glb, .gltf
- Preserve LEGO colors, materials, groups, pivots, and part names
- Keep models editable

### LEGO Library
- Built-in searchable parts library (Bricks, Plates, Tiles, Technic, Minifigures, Plants, Vehicles, Accessories)
- Color picker
- Brick snapping with magnetic stud connections

### Animation
- Professional timeline with keyframes
- Dope Sheet and Graph Editor
- Camera and character animation
- IK/FK rigs
- Pose Library and Animation Layers
- Motion Paths
- Onion Skin
- Playback controls

### Rendering
- Fast GPU rendering
- Export: PNG, JPEG, MP4, MOV, Image Sequence
- Support for 1080p, 1440p, 4K, 8K
- Motion Blur and Depth of Field

### Physics (Optional)
- Gravity, brick collisions, rigid bodies, cloth, soft bodies

### Audio
- Import music, voice recordings, sound effects
- Waveform display with timeline synchronization

## Tech Stack

**Frontend:** React, TypeScript, Electron
**Rendering:** Three.js, WebGPU
**State:** Zustand
**Storage:** IndexedDB, Local filesystem
**Build:** Electron Builder

## Project Structure

```
Lego-animation-app/
├── public/
├── src/
│   ├── components/
│   ├── context/
│   ├── hooks/
│   ├── pages/
│   ├── store/
│   ├── services/
│   ├── types/
│   ├── utils/
│   ├── styles/
│   └── App.tsx
├── electron/
│   ├── main/
│   ├── preload/
│   └── utils/
├── assets/
├── package.json
└── tsconfig.json
```

## Development

```bash
npm install
npm start          # Development mode
npm run build      # Build for production
npm run electron   # Run Electron
```

## License

MIT
