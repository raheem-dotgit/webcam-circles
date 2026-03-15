# Webcam Circles

An interactive webcam effect that creates mesmerizing circular visualizations from your camera feed. Built with modern web technologies for smooth, real-time performance.

![Next.js](https://img.shields.io/badge/Next.js-16.1.6-black?style=flat-square&logo=next.js)
![React](https://img.shields.io/badge/React-19.2.4-61DAFB?style=flat-square&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat-square&logo=typescript)

## Live Demo

[View Live Demo on Vercel](https://webcam-circles.vercel.app)

## Features

- Real-time webcam capture and processing
- Circular pixel visualization effect
- Smooth animations at 60fps
- Responsive canvas sizing
- Camera permission handling
- Modern, clean UI

## Tech Stack

- **Framework:** Next.js 16 (App Router)
- **UI:** React 19
- **Graphics:** HTML5 Canvas API
- **Language:** TypeScript

## Getting Started

### Prerequisites

- Node.js 18+
- pnpm (recommended)
- A webcam

### Installation

```bash
# Clone the repository
git clone https://github.com/raheem-dotgit/webcam-circles.git

# Navigate to the project directory
cd webcam-circles

# Install dependencies
pnpm install

# Start the development server
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) and allow camera access to see the effect.

## How It Works

The application captures video from your webcam, then samples pixels from the video feed and renders them as circles on a canvas. This creates a unique, artistic visualization of your camera input in real-time.

## Customization

- Adjust circle size and spacing in the `WebcamCircles` component
- Modify colors and effects
- Change sampling resolution

## Author

**Raheem**

- GitHub: [@raheem-dotgit](https://github.com/raheem-dotgit)
- LinkedIn: [ab-raheem](https://www.linkedin.com/in/ab-raheem)
- Email: raheem.dev7@gmail.com

## License

MIT License - feel free to use this project for your own purposes.
