# Face-Controlled 3D Model Viewer (React + TensorFlow\.js + Three.js)

## Overview

This project is a real-time 3D model controller built with React, Three.js, and TensorFlow\.js. It uses webcam input to detect face landmarks and translates those movements to manipulate a 3D GLB model on screen. Ideal for interactive applications like virtual try-ons, AR previews, and gesture-based 3D navigation.

## Features

- Real-time face landmark detection using TensorFlow\.js
- 3D model manipulation powered by Three.js
- GLB file rendering with dynamic transformations
- Live webcam input with `react-webcam`
- Responsive React-based UI

## Tech Stack

- **React.js**: Frontend framework
- **Three.js**: 3D rendering
- **TensorFlow\.js**: Face landmark detection
- **@tensorflow-models/face-landmarks-detection**: Pre-trained model
- **react-webcam**: Webcam access for browser

## Getting Started

### Prerequisites

- Node.js (v16 or later)
- Yarn (or npm)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/onoboaits/face-tracking-3d-control.git
   cd face-tracking-3d-control
   ```
2. Install dependencies:
   ```bash
   yarn
   # or
   npm install
   ```

### Running the App

```bash
yarn start
# or
npm start
```

The app will start at `http://localhost:3000`.

### Building for Production

```bash
yarn build
# or
npm run build
```

The production build will be in the `build/` folder.


## Demo

(Include a GIF or link to a video demonstrating real-time model control via face landmarks.)

## Contact

For collaboration or inquiries, contact: [onoboaits@gmail.com]

