# ScrollEd

Turn a textbook chapter into a scrollable feed of short lessons, each with a quiz question.

Runs fully in the browser. No server. Uses Google's free Gemini API tier with your own key.

## Use it
1. Get a free key at https://aistudio.google.com/apikey
2. Open the site, paste the key, upload a PDF/.txt/.md or paste text.
3. Scroll. Tap "Listen" to hear a lesson read aloud.

## Host it free on GitHub Pages
1. Create a GitHub repo and add `index.html` and this README.
2. Settings > Pages > Deploy from branch > `main` / root.
3. Your site goes live at `https://<you>.github.io/<repo>/`.

## Notes
- Your key is stored in your browser's localStorage and sent only to Google.
- Only upload material you have the right to use.
- Next ideas: scanned-PDF OCR, spaced repetition, saved progress, AI voices.
