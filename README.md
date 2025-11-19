# LinkedIn Post Generator

A specialized tool for marketing executives to generate high-quality, zero-fluff LinkedIn posts from articles or news.

## Features
- **Zero Marketing Fluff**: Generates professional, concrete content suitable for executives.
- **Dual Language**: Automatically creates English and Hebrew versions.
- **News Integration**: Fetches trending "AI in Marketing" news for quick content generation.
- **Visuals**: Generates DALL-E 3 images tailored to the post topic.
- **Smart Scraping**: Extracts meaningful content from URLs.

## Setup

1. **Install Dependencies**
   ```bash
   npm install
   ```

2. **Environment Variables**
   Create a `.env.local` file in the root directory with the following keys:
   
   ```env
   GOOGLE_API_KEY=your_gemini_api_key_here
   OPENAI_API_KEY=your_openai_api_key_here
   # NEWS_API_KEY is not currently used as we use RSS fallback
   ```

   - Get Gemini Key: [Google AI Studio](https://makersuite.google.com/app/apikey)
   - Get OpenAI Key: [OpenAI Platform](https://platform.openai.com/api-keys)

3. **Run Development Server**
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser.

## Usage
1. **Paste a URL**: Enter a link to an article or research paper and click "Generate".
2. **Find News**: Click "Find Trending News" to see recent articles on AI & Marketing, then generate a post from one.
3. **Review**: Copy the English or Hebrew text (hashtags included).
4. **Create Image**: Click "Generate AI Image" to create a matching visual using DALL-E 3.
