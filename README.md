# Immigration POC Frontend

AI-Powered Immigration Document Analysis Platform

## Features

- 📄 Document upload and analysis
- 🤖 AI-powered immigration case analysis
- ⏰ Deadline tracking and alerts
- 📚 Legal citations and references
- 📊 Confidence scoring
- 📱 Responsive design

## Deployment

This is a static HTML site ready for deployment on Vercel.

### Local Development

```bash
# Serve locally
python -m http.server 3000

# Or use any static server
npx serve .
```

### Vercel Deployment

1. Connect your GitHub repository to Vercel
2. Set the build command to: `echo 'Static site - no build needed'`
3. Set the output directory to: `.`
4. Deploy!

## API Integration

The frontend is configured to work with the Immigration POC backend API. Update the API endpoint in the JavaScript code to point to your deployed backend.

## Technologies Used

- HTML5
- Tailwind CSS
- Vanilla JavaScript
- Vercel for deployment
