# Vernacular Vibe Coder

A multilingual web app generator that uses AI to create applications from natural language descriptions in various Indian languages and English.

## Features

- **Multilingual Support**: Supports Hindi, Marathi, Tamil, Telugu, Bengali, Kannada, Gujarati, Punjabi, and English
- **AI-Powered Generation**: Uses Google Gemini AI to generate complete HTML applications
- **Live Preview**: Instant preview of generated applications
- **Code Export**: Download generated HTML files
- **Responsive Design**: Works on all device sizes

## Setup

1. **Get a Gemini API Key**:
   - Go to [Google AI Studio](https://makersuite.google.com/app/apikey)
   - Create a new API key
   - Copy the API key

2. **Configure the API Key**:
   - Open `index.html`
   - Find the `CONFIG` object (around line 200)
   - Replace the demo API key with your actual key:
   ```javascript
   const CONFIG = {
       API_KEY: "your-actual-api-key-here",
       // ... other config
   };
   ```

3. **Run the Application**:
   ```bash
   npm install
   npm run dev
   ```

## Usage

1. Select your preferred language from the dropdown
2. Describe the app you want to build in the text area
3. Click "Generate App" to create your application
4. View the live preview or download the HTML code

## Example Prompts

- **Hindi**: "एक कैलकुलेटर बनाओ जो जोड़, घटाव, गुणा और भाग कर सके"
- **English**: "Create a todo list with add, delete, and mark complete features"
- **Tamil**: "ஒரு எளிய கடிகாரம் உருவாக்கவும்"

## Deployment

The application is a static HTML file and can be deployed to any static hosting service like:
- Netlify
- Vercel
- GitHub Pages
- Bolt Hosting

## License

MIT License