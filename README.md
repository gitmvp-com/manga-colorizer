# Manga Colorizer 🎨

An AI-powered web application that transforms black and white manga images into vibrant colored artwork using advanced AI models.

## Features

✨ **AI-Powered Colorization** - Uses Gemini 2.5 Flash via OpenRouter to intelligently colorize manga images

🖼️ **Easy Image Upload** - Drag-and-drop interface supporting JPG, PNG, and WebP formats (up to 10MB)

⚡ **Real-time Progress** - Multi-stage loading with progress tracking and time estimates

💾 **Download Options** - Save your colorized manga in PNG or JPEG format

🌙 **Dark Mode** - Full dark mode support for comfortable viewing

📱 **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices

## Tech Stack

- **Framework:** Next.js 15.5.2 (App Router)
- **Language:** TypeScript 5
- **Styling:** Tailwind CSS v4
- **AI Integration:** OpenRouter AI SDK with Gemini 2.5 Flash
- **Runtime:** React 19.1.0

## Getting Started

### Prerequisites

- Node.js 18.x or higher
- pnpm (recommended) or npm
- OpenRouter API key ([Get one here](https://openrouter.ai/))

### Installation

1. Clone the repository:
```bash
git clone https://github.com/gitmvp-com/manga-colorizer.git
cd manga-colorizer
```

2. Install dependencies:
```bash
pnpm install
# or
npm install
```

3. Create a `.env.local` file in the root directory:
```env
OPENROUTER_API_KEY=your_api_key_here
```

4. Run the development server:
```bash
pnpm dev
# or
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## Usage

1. **Upload** - Click or drag-and-drop a black and white manga image
2. **Generate** - Click the "Colorize Manga" button
3. **Wait** - The AI processes your image (typically 30-60 seconds)
4. **Download** - Save your colorized manga in your preferred format

## Environment Variables

| Variable | Description | Required |
|----------|-------------|----------|
| `OPENROUTER_API_KEY` | Your OpenRouter API key for accessing Gemini 2.5 Flash | Yes |

## How It Works

The application uses Google's Gemini 2.5 Flash model through OpenRouter to:
1. Analyze the manga image's content, characters, and context
2. Intelligently determine appropriate colors based on typical manga conventions
3. Apply colorization while preserving original line art and details
4. Return a high-quality colorized version

## Limitations

- Maximum image size: 10MB
- Supported formats: JPG, PNG, WebP
- Processing time varies based on image complexity
- Requires active internet connection
- API usage is subject to OpenRouter rate limits

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the MIT License.

## Acknowledgments

- Built with [Next.js](https://nextjs.org/)
- Powered by [OpenRouter](https://openrouter.ai/)
- AI Model: Google Gemini 2.5 Flash
- Inspired by [filiksyos/ai_outfit_app](https://github.com/filiksyos/ai_outfit_app)

## Support

If you encounter any issues or have questions, please [open an issue](https://github.com/gitmvp-com/manga-colorizer/issues).
